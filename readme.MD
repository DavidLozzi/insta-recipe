# InstaRecipe

Converts an Instagram recipe video to an actual recipe to cook with!

Currently, it's just in a Jupyter notebook.

## TODO

- Add transcription, Had to do it manually in AWS. Consider OpenAI Whisper.

## TODO: Scaling it out

- Front end to accept URL
- Post to an API, which puts it into SQS and DB
- Front end pings for status
- Listener pulls request and processes the file
- Front end displays full recipe, with export options (AnyList, Amazon?, FreshCart? etc?)

## TODO: Accept payments

- Roughly $.15 a video
- Per video
- Per video bulk
- Monthly Subscriptions
