# .github
Plant-Tracer is a project to capture and analyze the movement of plants

There are multiple repositories in this Plant-Tracer GitHub Organization. Not all of them are public.

.github: This repository exists to hold the Plant-Tracer organization README.md file you are reading right now. That's all

legacy-ios-app: This is the Plant Tracer iOS app developed in 2017. It runs on iPhones and iPads, etc., but it hasn't been updated in a while and it doesn't run well on all newer devices. That's why it's called legacy. Also because it uses the Cordova framework which is no longer being maintained actively and we don't want to be in a world like that. It's a nice application that will analyze gravitropism and circumnutation videos using a block-matching algorithm, and if it works on your device, please feel free to use it. It will offer to upload the results of the analysis to a database, but that database is no longer running. The repo is also a source for requirements and implementations to be migrated to the webapp repo. This iOS app is available on Apple's iOS App Store as "Plant Tracer App"

legacy-webapp: This is the current (September 2023) static website for planttracer.com. It's called legacy because we want to migrate to something more maintainable. But there's nothing wrong with it otherwise. It has a description of the PlantTracer project, and a tutorial on how to use the legacy-ios-app.

webapp: This is the new version of Plant Tracer. The plan is to replicate the functionality of legacy-ios-app as a multi-platform web application that will run on iOS, Android, and PC/Mac/Linux web browsers. It adds video capture functionality and will support multiple analysis algorithms. It will allow users to upload and manage their own videos, and it will let researchers and admins have access to all the videos and manage and analyze them further. We plan to have the first version live by early November 2023. (Gravitropism; block matching only in 1.0)

management: A private repository for the project team to plan and manage Plant-Tracer projects.

demo-repository (Private): The default GitHub demo-repository that GitHub just put there. We're not using this for anything. Feel free to ignore it.

klt (Private): An implementation of the Kanade-Lucas-Tomasi (KLT) feature tracker algorithm (https://en.wikipedia.org/wiki/Kanade–Lucas–Tomasi_feature_tracker) from Professor Yixiang Mao. We're planning to use KLT in a later version of the new Plant Tracer webapp, but we aren't there yet.
