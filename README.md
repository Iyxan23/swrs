# SWRS
A rusty library that reads, parses and re-constructs sketchware projects.

This might look dumb to use rust, but I'm currently planning to do something bigger with this.

## Development state
This project is **In-progress (unfinished; partly finished)**. I really do hope in getting this project finished lmao

Stuff:
 - [x] Encrypting & Decrypting a sketchware project
 - [x] Parsing `project`
 - [x] Parsing `file`
 - [x] Parsing `library`
   > Note: I'm planning to do something better, the current implementation only works one-way (only deserializing)
 - [x] Parsing `resource`
 - [x] Parsing `view`
   > Note: This is a simple implementation, I'm planning to create a way to neglect unnecessary fields depending on its view type (something like TextView, it only cares about `text` and other stuff, fields like `spinner_mode` will be erased) and convert them back into its root form to serialize/reconstruct it.
 - [ ] Parsing `logic`
   WIP as of 22 Oct 2021
 - [ ] Reconstructing `project`
 - [ ] Reconstructing `file`
 - [ ] Reconstructing `library`
 - [ ] Reconstructing `resource`
 - [ ] Reconstructing `view`
 - [ ] Reconstructing `logic`

## Curious?
If you're wondering on how to read a sketchware project's data yourself, I have been writing details about the sketchware project structure and how to read & parse them on [`docs/`](docs/reading-a-sketchware-project.md), go ahead and give it a little bit of a read

## Cool, I want to help!
I'd be very very thankful for those that are interested in contributing to this project. I'm new to rust and my code needs some reviewing from an actual rust user and I would love to hear feedbacks from it!

If you are interested in contributing to the code or documentation, go ahead! :^)
