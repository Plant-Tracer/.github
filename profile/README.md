<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

[Plant-Tracer](https://github.com/Plant-Tracer/) is a project to capture and analyze the movement of plants

There are multiple repositories in this Plant-Tracer GitHub Organization. This file describes only the public repositories.

[.github](https://github.com/Plant-Tracer/.github): This repository exists to hold the Plant-Tracer organization README.md file you are reading right now. That's all.

[legacy-ios-app](https://github.com/Plant-Tracer/legacy_ios_app): This is the Plant Tracer iOS app developed in 2017. It runs on iPhones and iPads, etc., but it hasn't been updated in a while and it doesn't run well on all newer devices. That's why it's called legacy. Also because it uses the Cordova framework which is no longer being maintained actively and we don't want to be in a world like that. It's a nice application that will analyze gravitropism and circumnutation videos using a block-matching algorithm, and if it works on your device, please feel free to use it. It will offer to upload the results of the analysis to a database, but that database is no longer running. The repo is also a source for requirements and implementations to be migrated to the webapp repo. This iOS app is available on Apple's iOS App Store as "Plant Tracer App"

[legacy_web_app](https://github.com/Plant-Tracer/legacy_web_app): This is the repository for what used to be on planttracer.com prior to about April 2023 when there was a big mostly unused database. The web-static repo is the newer one.

[webapp](https://github.com/Plant-Tracer/webapp): This is the new version of Plant Tracer. The plan is to replicate the functionality of legacy-ios-app as a multi-platform web application that will run on iOS, Android, and PC/Mac/Linux web browsers. It adds video capture functionality and will support multiple analysis algorithms. It will allow users to upload and manage their own videos, and it will let researchers and admins have access to all the videos and manage and analyze them further. The application supports its use in academic courses. We plan to have the first version live by early November 2023. (Gravitropism; block matching only in 1.0)

[web-static](https://github.com/Plant-Tracer/web-static): Content repository for the current planttracer.com static website. It has a description of the PlantTracer project, and a tutorial on how to use the legacy-ios-app.

[PlantTracerML](https://github.com/Plant-Tracer/PlantTracerML): This is a fork of [YixiangMao/PlantTracerML](https://github.com/YixiangMao/PlantTracerML). It is a U-Net machine learning model trained on a particular setup of arabadopsis circumnutations. The current Plant-Tracer team has taken up maintenance and enhancement of the app in this repository.
