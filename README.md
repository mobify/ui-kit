# Progressive Mobile UI Kits

The **Progressive Mobile UI Kits** are design collections of components used in Mobify's products, allowing designers to quickly and efficiently create mockups for their projects. The kits also maintain parity with the code components, so building designs based on the kits is easier for developers too.

## Table of Contents

_Coming soon._

## Getting Started

**Before you begin, you should have…**
- The latest version of [Sketch](https://www.sketchapp.com/).
- The fonts [Roboto](https://fonts.google.com/specimen/Roboto) and [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) installed.

To start using the kits, just download one... or all of them! But before you open them, make sure the base fonts are installed or Sketch will have an conniption.

## Using the Kit

Once you open the kit, the first thing you'll want to do is take a look at the **Setup** pages. The Setup pages contain all the type and layer styles through out the kit; changing them here will populate the changes through all the components, and will  give you a great headstart in customizing the components to match your client's brand.

### Using Symbols Within the Kit

The symbols included in the UI Kits are **named to be inline with their code counterparts**. This is intended to be a reference for the developers who will inherit the designs; by maintaining this naming scheme, the developers will know which components you've used and what they need to include in their build.

As such, _we do not recommend renaming the of symbols_, either on the Symbol page or in individual instances, as that would remove the reference point. If you want to organize the symbols used in your design, we suggest doing so by wrapping them in groups and renaming those.

### Sharing with Developers

Eventually you will need to pass them onto your developers. They may not have access to Sketch, and while you _could_ pass along flats, you'll be losing one of the benefits of using the UI Kit: the reference to its code counterparts.

If Sketch is unavailable to your development team, we suggest using another tool to pass the designs along.

**We recommend:**
- [InVision Inspect](https://support.invisionapp.com/hc/en-us/articles/207950906-Introduction-to-Inspect)
- [Zeplin](https://zeplin.io/)

## Contributing to the Kit

The UI Kit is built on the following tenents:

- **Fast and Reliable:** The UI Kit should be fast. It should not become so large and unwiedly that Sketch crashes or the file does not sync with our tools. This why we split the kit into multiple Sketch files, allowing them to be smaller and stabler.
- **Flexible and Future-facing:** The UI Kit should be easy to use for a variety of project types. That's why we include Preset steps, making it easier to customize the  components for your project, and why all symbols are as resizable as they can be.
- **Organized:** We've put a lot of effort into carefully categorizing and organizing the Sketch symbols for easy reference and use. What's the point of using a UI Kit to speed up your design when you spend half your time searching for the right symbol?

When using and contributing to the UI Kits, please keep these tenets in mind.

### Making Changes and Pull Requests

Before you start editing files, take a moment to look around and assess the current situation.

1. **Check if there's pending pull requests for the file.** Since Sketch files cannot _truly_ be merged, we need to be vigiliant not to overwrite someone else's work. 
    1. If there is, please help review and merge the pull request.
    2. If not, you can begin work.
2. **Work from the correct branch.** All changes to the UI Kits should be made on their respective branches. Again, we can't have a bunch of separate branches because they won't merge properly, so we try to maintain a single branch per file to prevent this. Example: `ui-base-changes` and `ui-app-changes`
3. **Double check your work.** Do your changes follow the tenets of the UI Kit? This will be reviewed in the pull request anyway, so it doesn't hurt to save yourself and others some time by doing one last check beforehand.
    - Are the symbols appropriately named and filed?
    - Are all layers appropriately named and organized?
    - Is the symbol flexible? Can it be resized without breaking?
    - Is the symbol neatly integrated into the Symbol page?
If it all looks good, then you can pull away!
3. **Create your pull request.** In your pull request you need to make it clear what has changed and which file you've altered.
    - Your title should follow this format: `[FILE] Summary`
        - Example: [BASE] Reduced the number of form symbols
        - Example: [APP] Added a new dialog type
    - The body of the PR should contain a more detailed summary of the changes made, and where your reviewer may be able to find them. Include any symbol names!
    - Include approval checks for a fellow designer to review your changes.
4. **Wait for the pull request to get reviewed.** Ping or poke your fellow designers to take a look at your pull request.
5. **Merge your pull request.** Whoo-hoo! You did it! Now you can sit back and admire your work. Just don't delete the branch.

## Requesting a New Component

Did you see something missing from the kit that we just _need_ to have? If you're not comfortable adding it to the Sketch file yourself, create an [issue](/issues) in the parent GitHub repo.