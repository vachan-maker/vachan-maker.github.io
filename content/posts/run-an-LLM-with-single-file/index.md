+++
title = "Run an LLM with a single file"
date = 2024-06-25T11:59:00+05:30
draft = false
description = "Using an LLM on your computer is not rocket science"
+++
Last month, I came across a video by NetworkChuck on [hosting AI locally](https://www.youtube.com/watch?v=Wjrdr0NU4Sk). In short, he built a server specifically for running LLMs using Ollama and other tools. From his video I learned that running an LLM on your machine is actually not a complicated task.

But then a few weeks later, I discovered Mozilla's llamafile project which makes it even more easier to use LLMs on your computer. There is nothing to install. All you have to do is run a single file. It even comes with a web chat interface.

One of the big advantages of using an LLM locally is privacy. Everything runs offline and you don't need to worry about your data being used to train AI models.

To start using llamafile on Linux, 

1. Go to the project's repo by clicking [here](https://github.com/Mozilla-Ocho/llamafile?tab=readme-ov-file#other-example-llamafiles) and download the model you want to run. I downloaded the `TinyLlama-1.1B-Chat-v1.0.F16.llamafile` file because of it's relatively small size. Download the model which you prefer.

2. Go to the folder where you downloaded your llamafile and open the terminal there. You will need to give permission to run the file so type the command below in the terminal. 

    `chmod +x TinyLlama-1.1B-Chat-v1.0.F16.llamafile`

    (If you downloaded a different model, remember to change the file name.)

3. Run the file by entering the following command

    `./TinyLlama-1.1B-Chat-v1.0.F16.llamafile`

4. Your browser should open automatically and that is all. If it doesn't go to http://localhost:8080/ . That is all. See how easy that was!

*Instructions are from the llamafile [quick start guide](https://github.com/Mozilla-Ocho/llamafile?tab=readme-ov-file#quickstart)*

I use a really old laptop and it was able to run the model alright. Sometimes, my desktop environment would freeze for a few moments.

Anyway, I hope you got a good idea on how simple it is to a run an LLM on your machine. Cheers!

{{<figure src = "llamafile.webp" caption = "The TinyLlama model running on my computer" alt = "Screenshot of the web interface of running a llamafile.">}}

This is day 30 of [#100DaystoOffload](https://100daystooffload.com)