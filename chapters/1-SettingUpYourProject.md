# Setting Up Your Project

# What is a Pharo application?
- What is an image? What is a VM?
- How is it different from a Node package? etc
- Can you make a *library* and an *executable*? What differences would that make in setting up a project?
- The project in this book will be more of a traditional "executable", not a library.
- Create a new VM for every project?
- Where to get a clean VM?
- Get rid of classes you don't need? Tree shaking when finished?

## What lies ahead
This project will be a typical ETL "script":
- Get data from some API
- Format the JSON payload into a dataframe
- Convert the Dataframe to a CSV file
- Save the file on disk and email a copy to yourself

## Installing Pharo
- PharoLauncher. It's a VM+image that manages your other images. Similar to Rust's `rustup` or Python's `conda env`?
- Use PharoLauncher to get Pharo 7. Pharo 7 is what works with Github.
- [Get Pharo ZeroConf](get.pharo.org)

Open the Pharo 7 development image and set up version control with Iceberg/Git/Github etc

## Startup
- Entry points to your image
  - Similar to Java, in Pharo you would write a small launcher shell script that calls the VM with the right image and arguments
  - Some Pharo methods can have `<script>` or `<example>` pragmas
  - Startup actions
  - CommandLineHandlers and soon Clap will provide "entry points" in a way as well
  - `save:andQuit:` and sessions explanation