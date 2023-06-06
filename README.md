# 2023-ios-hw3

### Meme Generator app
Main Screen - Meme Information Fill Screen:

- 3 TextFields (name, top text, bottom text)
- Button: On tap, make a request to https://apimeme.com/. Experiment with the site to view different memes and texts. This site automatically generates a URL. You need to understand how it is constructed and transform it to Moya.

Once you receive a response, you have two options:

1. If you receive an error, display an alert with an OK button.
2. If you receive image data, navigate to a new Result screen. 👇

Result screen:
- A single large image generated from the data. Make the image resizable so that it fits the screen.

Bonus:
- Create a TabView with two tabs: one for the main screen and one for the history screen. The history screen should contain a list of all generated memes.
