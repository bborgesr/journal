---
title: Sprint 1 show & tell and restrospective
author: Barbara
date: '2018-03-05'
slug: sprint-1-show-tell-and-restrospective
categories:
  - journal
tags:
  - scrum
  - show & tell
  - restrospective
  - sprint
  - shinyRecorder
---

# Show and Tell -- some highlights

- Here's a cool little link that you need to bookmark, if you are interested in knowing all bout the lastest dev feature in shiny: async operations and promises: <https://rstudio.github.io/promises/>

- Alan and I demoed a locally running recording of a Shiny app session using: 
  ```r
  shinyRecorder::recordSession(
      targetAppUrl = "http://localhost:3923/", 
      outputFile = "output.log"
  )
  ```
  where: 
   - `"http://localhost:3923/"` is the _URL_ where local app is currently running (the simplest way to achieve this is to open up a terminal window and enter: `R -e 'shiny::runExample("01_hello", port=3923)'`); 
   
   - and `"output.log"` is the destination + file name, where the new recording log will be stored once you close the recording browesr (usually: `"http://localhost:8600/"`, though `recordSession` takes a `host` and a `port` argumnents so you can specify the desired host and port to your heart's content).

# Retrospective -- some highlights

Will borrow from: https://goo.gl/eh2M2P

To be continued...
