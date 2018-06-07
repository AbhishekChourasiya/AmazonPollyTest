# AmazonPollyTest

This is a basic demo of how to use Amazon Polly to add Text-to-Speach feature into your java applications. we create a `AmazonPollyClient` and 'Voice` reference object.
We then create `DescribeVoicesRequest` and `DescribeVoicesResult` object which help us to initialize our voice assistant/TTS agent.

`voice = describeVoicesResult.getVoices().get(41);`
here, we have to provide voice id; id-41 is for English-India Female 1 version.


We cteate a `javazoom.jl.player AdvancedPlayer` Object to play the voice.
