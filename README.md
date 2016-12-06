# Progressive Mobile UI Kits

The **Progressive Mobile UI Kits** are Sketch files containing defaults of all the components used in Mobify's products. Using the kits allows designers to quickly and efficiently create mockups for their projects, and helps developers leverage the SDK for their builds, as the kits maintain parity with the code components.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Using the Kit](#using-the-kit)
    1. [Using Symbols Within the Kit](#using-symbols-within-the-kit)
    2. [Sharing with Developers](#sharing-with-developers)
3. [Contributing to the Kit](#contributing-to-the-kit)
    1. [Making Changes and Pull Requests](#making-changes-and-pull-requests)
4. [Requesting a New Component](#requesting-a-new-component)

## Getting Started

**Before you begin, you should have…**
- The latest version of [Sketch](https://www.sketchapp.com/), and a working knowledge.
- The fonts [Roboto](https://fonts.google.com/specimen/Roboto) and [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) installed.

To start using the kits, just download one... or all of them! But before you open them, make sure the base fonts are installed or Sketch will have an conniption.

## Using the Kit

Each kit contains the following pages:

- **Introduction:** Basically what you've found here, but with a little more detail on the spacing system and how to work the Sketch file, including toggling the framing, margin, and padding styles.
- **Setup Steps:** The Setup pages contain all the type and layer styles through out the kit; changing them here will populate the changes through all the components, and will  give you a great headstart in customizing the components to match your client's brand.
- **Symbol Page:** Where all the Symbols live. We've put a lot of effort into arranging this page, for your (and our) benefit! Once you've completed your Setup steps, you'll want to peruse the symbols to make further adjustments and customizations.
- **Template examples:** These are basically a sampling of _what you can do_ with the UI Kit. These are not prescriptive, hard-and-fast recommendations of how your pages should look; they are common arrangements that reflect our best practices, but you should make the effort to customize your designs to your client—and their customer's—needs.

Once you open the kit, the first thing you'll want to do is take a look at the **Setup** pages.

### Using Symbols Within the Kit

The symbols included in the UI Kits are **named to be inline with their code counterparts**. This is intended to be a guide for the developers who will inherit the designs; by maintaining this naming scheme, the developers will have a reference of which components you've used and therefore which ones they need to include in the build.

As such, _we do not recommend renaming the of symbols_, either on the Symbol page or in individual instances, as that would remove the reference point. If you want to organize the symbols used in your design, we suggest doing so by wrapping them in groups and renaming those.

#### Symbol Naming

As mentioned above, the symbols are named to be inline with the code components. However, there's more to that. There are states, variants, and modifiers you need to be aware of.

- `[category]` - To make it easier to find symbols by organizing them by purpose or use.
    - `[action]` - calls to action (buttons)
    - `[form]` - all forms of form elements and inputs
    - `[general]` - general use components that could appear anywhere in the site
    - `[global]` - global symbols are major components that the entire site hinges on (navigation, header, etc.)
    - `[icon]` - all the icons an their variations
    - `[product]` - all symbols that are specific to products, or product options.
    - `[templates]` - sub-templates saved as symbols for convience.
    - `[type]` - basic type elements as symbols to preserve the spacing system.
- `--modifier` - Modifiers relfect our CSS naming convention for modified versions of a component, such as `--horizontal` for a horizontal layout or `--small` for a smaller version.
- `:state` - Different symbols that reflect its different states. Meant to reflect the states used in CSS, like `:disabled` or `:focus`.
- `~variant` - variant is a little different than a modifier, as it wouldn't be represented in the code. It's more about an option that you would choose over another. Example: `~right` or `~left` aligned options.

### Customizing Symbols

Customizing the components can be as simple as changing colours and icons — something that will filter through from your established design system — or as complex as rearranging the component’s internal elements or creating alternate views or variants. These are simply visual customizations that can be done with little impact to your development timeline. 

Though the default components included in the SDK should work for most situations, there may be times where you may need to further customize a component to satisfy the needs of the client or their user. In these cases, you may need to include additional elements to the components.

While you certainly can do this, you must be wary of the additional cost of developing these customizations. Before deciding on any custom components, first review your designs with your development team to ensure it’s feasible and will not threaten your project timelines.

### Sharing with Developers

Eventually you will need to pass them onto your developers. They may not have access to Sketch, and while you _could_ pass along flats, you'll be losing one of the benefits of using the UI Kit: the reference to its code counterparts.

If Sketch is unavailable to your development team, we suggest using another tool to pass the designs along. These tools allow developers to reference layer and symbol names without Sketch itself.

**We recommend:**
- [InVision Inspect](https://support.invisionapp.com/hc/en-us/articles/207950906-Introduction-to-Inspect)
- [Zeplin](https://zeplin.io/)

## Contributing to the Kit

The UI Kit is built on the following tenents:

- **Fast and Reliable:** The UI Kit should be fast. It should not become so large and unwiedly that Sketch crashes or the file does not sync with our tools. This is why we split the kit into multiple files, allowing them to be smaller and stabler.
- **Flexible and Future-facing:** The UI Kit should be easy to use for a variety of project types. That's why we include preset steps, making it easier to customize the  components for your project, and why all symbols are as resizable as is currently possible.
- **Organized:** We've put a lot of effort into carefully categorizing and organizing the Sketch symbols for easy reference and use. What's the point of using a UI Kit to speed up your design when you spend half your time searching for the right symbol?

When using and contributing to the UI Kits, please keep these tenets in mind.

### Making Changes and Pull Requests

Before you start editing files, take a moment to look around and assess the current situation.

1. **Check if there's pending pull requests for the file.** Since Sketch files cannot _truly_ be merged, we need to be vigiliant not to overwrite someone else's work. 
    1. If there is, please help review and merge the pull request.
    2. If not, you can begin work.
2. **Work from the correct branch.** All changes to the UI Kits should be made on their respective branches. Again, we can't have a bunch of separate branches because they won't merge properly, so we try to maintain a single branch per file to prevent this. Example: `ui-base-changes` and `ui-app-changes`
3. **Double check your work.** Do your changes follow the tenets of the UI Kit? This will be reviewed by your fellow designs when you create your pull request, so it doesn't hurt to save yourself and others some time by doing one last check beforehand.
    - Are the symbols appropriately named and filed?
    - Are all layers appropriately named and organized?
    - Is the symbol flexible? Can it be resized without breaking?
    - Is the symbol neatly integrated into the Symbol page?
If it all looks good, then you can pull away!
4. **Create your pull request.** In your pull request you need to make it clear what has changed and which file you've altered.
    - Your title should follow this format: `[FILE] Summary`
        - Example: _[BASE] Reduced the number of form symbols_
        - Example: _[APP] Added a new dialog type_
    - The body of the PR should contain a more detailed summary of the changes made, and where your reviewer may be able to find them. Include any symbol names!
    - Include approval checks for a fellow designer to review your changes.
5. **Wait for the pull request to get reviewed.** Ping or poke your fellow designers to take a look at your pull request.
6. **Merge your pull request.** Whoo-hoo! You did it! Now you can sit back and admire your work (but don't delete the branch).

## Requesting a New Component

Did you see something missing from the kit that we just _need_ to have? If you're not comfortable adding it to the Sketch file yourself, create an [issue](/issues) in the parent GitHub repo.