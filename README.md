Issue Template to add your project

name: 🚀 Request to Add Project
description: Submit your project to be listed under Codeyatri organization
title: "[Project Request] <Project Name>"
labels: [project-request]
body:
  - type: input
    id: project-name
    attributes:
      label: 📛 Project Name
      placeholder: Enter your project name
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: 📝 Short Description
      placeholder: Write a 1–2 line summary of your project
    validations:
      required: true

  - type: input
    id: tech-stack
    attributes:
      label: 🛠️ Tech Stack Used
      placeholder: (e.g., Reac
