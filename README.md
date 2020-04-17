# DJ Playlist Generator Using Deep Learning
- Developed a DJ Mix Playlist recommender that enables seamless transition between tracks as it takes into account similarity in musical textures, frequencies, keys, energy level, etc. 
- Utilized spotify API to collect useful metadata using python library Spotipy.
- Converted over 1500 mp3 audio files into image representation of spectrograms and chromagrams, using python library Librosa
- Used a Convolutional Neural Network (transfer learning with VGG16) to train spectrograms and chromagrams
- Developed a recommendation system using content-based filtering and cosine similarities of spectrogram and chromagram feature vectors
- All data storage and full scale model computation done within Google Cloud Platform
