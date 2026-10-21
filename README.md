# Predict InceptionV1 neuron 4e:55

A static guessing game: see an ImageNet photo, guess whether InceptionV1 neuron mixed4e:55 is in its top or bottom percentiles.
Play at https://ulissemini.github.io/4e55-game/

- `img/<i>.jpg`: 224×224 crops the network sees (ImageNet photos, research use)
- `data.json`: per photo: peak activation as a fraction of the neuron's max, ImageNet class, percentile, sampling weight
- `maps.bin`: 14×14 uint8 heatmap per photo (196 bytes each)
