# Setting Up Your Project

- What is a Pharo application?
  - What is an image? What is a VM?
  - How is it different from a Node package? etc
  - Can you make a *library* and an *executable*? What differences would that make in setting up a project?
  - The project in this book will be more of a traditional "executable", not a library.
- Create a new VM for every task?
- Where to get a clean VM?
- Get rid of classes you don't need? Tree shaking when finished?

This project will be a typical ETL "script":
- Get data from some API
- Format the JSON payload into a dataframe
- Convert the Dataframe to a CSV file
- Save the file on disk and email a copy to yourself

First thing's first: Get Pharo.
- PharoLauncher. It's a VM+image that manages your other images. Similar to Rust's `rustup` or Python's `conda env`?
- Use PharoLauncher to get Pharo 7. Pharo 7 is what works with Github.

Open the Pharo 7 development image and set up version control with Iceberg/Git/Github etc
