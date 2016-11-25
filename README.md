# Progressive Mobile UI Kits

The **Progressive Mobile UI Kits** are collections of components that are part of Mobify's suite of technologies, allowing designers to quickly and efficiently create designs for their projects. The kits also maintain parity with the code components, so building designs based on the kits is easier for developers too.

## Table of Contents

_Coming soon._

## Getting Started

**Before you begin, you should have…**
- The _latest version_ of [Sketch](https://www.sketchapp.com/).
- The fonts [Roboto](https://fonts.google.com/specimen/Roboto) and [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) installed (both are included in the kit repo).

To start using the kits, just download one... or all of them! But before you open them, make sure the base fonts are installed or Sketch will have an conniption.

## Using the Kit

Once you open the kit, the first thing you'll want to do is take a look at the **Setup** pages. The Setup pages contain all the type and layer styles through out the kit; changing them here will populate the changes through all the components, and will  give you a great headstart in customizing the components to match your client's brand.

## Using Symbols Within the Kit

The symbols included in the UI Kits are **named to be inline with their code counterparts**. This is intended to be a reference for the developers who will inherit the designs; by maintaining this naming scheme, the developers will know which components you've used and what they need to include in their build.

As such, _we do not recommend renaming the of symbols_, either on the Symbol page or in individual instances, as that would remove the reference point. 

If you want to organize the symbols used in your design, we suggest doing so by wrapping them in groups and renaming those.

### Sharing with Developers

Eventually you will need to pass them onto your developers. They may not have Sketch, and while you _could_ pass along flats, you'll be losing one of the benefits of using the UI Kit: the reference to its code counterparts.

If Sketch is unavailable to your development team, we suggest using another tool to pass the designs along.

**We recommend:**
- [InVision Inspect](https://support.invisionapp.com/hc/en-us/articles/207950906-Introduction-to-Inspect)
- [Zeplin](https://zeplin.io/)

## Contributing to the Kits

The UI Kits are built on the following tenents:

### Fast and Reliable
The UI Kit should be quick to open and easy to get started with; it should not become so unwiedly that Sketch crashes or the file does not sync with our appropriate tools.

**That's why we…**
- Split the kit into multiple files, allowing smaller file sizes.
- Include Preset steps, making it easier to customize your project.

### Flexiblity and Multi-Use
Making sure that the component symbols we do create can be resized and stretched helps us reduce the number of symbols we need (keeping things speedy!) as well as allowing us to design for multiple screen sizes with greater ease.

**That's why we…**
- Pet kitties!

### Organization
We've put a lot of effort into carefully categorizing and organizing the Sketch symbols for easy reference and use. What's the point of using a UI Kit to speed up your design when you spend half your time searching for the right symbol?

`[category]`
`--modifier`
`:state`
`~variant`

When using and contributing to the UI Kits, please keep these tenets in mind.

## Making Changes

All changes to the UI Kits should be made on their respective branches, and merged into `master` via a pull request. However, since Sketch files cannot _truly_ be merged, we need to be vigiliant not to overwrite someone else's work. 

Before you start editing files, take a moment to look around and assess the situation.

1. Check if there's pending pull requests for the file.
    1. If there is, please help review and approve the pull request. 
    2. If not, you can begin work.
2. Work from the correct branch.
3. Create a pull request.

1. **Is there already a pull request open for this file branch?** If there is, you can't edit the file until the request and change has been approved and merged into master. Is there anything you can do to help? If you can help review and approve the pull request, then you can start work faster!

2. If there's no pending pull requests, then you can go straight to work! Please **work from the correct branch.** We can't have a bunch of separate branches because they won't merge properly, so we try to maintain a changes branch per file to prevent this. Example: `ui-base-changes` and `ui-tablet-changes`

### Before you create a pull request

- Are all layers appropriately named?
- Is the symbol flexible? Can it be resized without breaking?
- Is the symbol appropriately named and filed?
- Is the symbol neatly integrated into the Symbol page?

### Requesting a New Component

Did you see something missing from the kit that we just _need_ to have? Create an [issue](/issues) in the parent GitHub repo.