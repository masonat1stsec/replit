
# Overview
Source: https://docs.replit.com/category/replit-deployments

Share your Replit Apps with the world in just a few clicks.

<YouTubeEmbed title="Publish your app on Replit" />

Publishing lets you share your Replit App with the world using a simplified process.

<Note>
  The action of making your app live is called "Publishing." This page describes the different types of deployments available.
</Note>

## What is Publishing?

Publishing is a feature that saves a **snapshot** of your Replit App to the cloud,
where everyone can interact with it. A snapshot captures the current state of the files in your
Replit App.

When you publish your Replit App, you create a **published app**. A published app is a running instance
of your app on Replit's cloud infrastructure. This makes the app reliably available on the internet,
separate from the version in the Project Editor.

<Info>
  Replit's infrastructure is backed by Google Cloud Platform (GCP). All
  published apps are hosted in the United States. Enterprise customers can
  contact sales to request their published apps to be hosted in the European
  Union instead.

  Every individual, organization, and enterprise customer receives a dedicated,
  single-tenant GCP project for their published apps. This means that published
  apps' compute resources, secrets, and storage are fully isolated and never
  shared with other customers' apps.
</Info>

Publishing includes tools to monitor your published app status and view web analytics.

Replit offers the following deployment types:

<CardGroup>
  <Card title="Autoscale Deployment" href="/cloud-services/deployments/autoscale-deployments" icon="layer-group">
    Automatically adjusts resources based on your app's usage.
  </Card>

  <Card title="Static Deployment" href="/cloud-services/deployments/static-deployments" icon="files">
    Provides an affordable way to host websites that don't change based on user input.
  </Card>

  <Card title="Reserved VM Deployment" href="/cloud-services/deployments/reserved-vm-deployments" icon="server">
    Provides a consistent amount of computing resources for your app to run continuously.
  </Card>

  <Card title="Scheduled Deployment" href="/cloud-services/deployments/scheduled-deployments" icon="clock">
    Runs your app at scheduled times that you choose.
  </Card>
</CardGroup>

## Getting started

Follow the steps below to publish your Replit App:

1. From your Project Editor, select <img alt="Publish icon" /> **Publish** at the top.
