<img width="350" alt="Mobify UI Kit logo" src="https://cloud.githubusercontent.com/assets/6453968/26260652/d02ec66a-3c82-11e7-94bd-e841dd48b764.png" />

The **Mobify UI Kit** is a series of Sketch files containing all the components and patterns from Mobify's PWA SDK, AMP SDK and Astro plugins for native apps.
The Kit allows designers to quickly and efficiently create mockups and patterns for their projects, and parity with supported SDK components makes it easy for developers turning design mocks into code.

## Getting Started

**Before you begin, you should have…**
- The latest version of [Sketch](https://www.sketchapp.com/updates/), and a working knowledge.
- The font [Roboto](https://fonts.google.com/specimen/Roboto) installed.

**To start using the kit:**

1. Download the kit from the [latest release](https://github.com/mobify/pwa-ui-kit/releases)
2. Install the fonts
3. Open the file, then either:
    1. Begin customizing the presets, components and layouts to fit the design of your PWA/AMP/App templates.
    2. Create a new file and use the UI Kit as a sticker sheet, copy and pasting the components as and when you need them.

## Using the Kit

Each kit contains the following pages:

- **Introduction:** Basically what you've found here, but with a little more detail on the spacing system and how to work the Sketch file, including toggling the framing, margin, and padding styles.
- **Setup:** The Setup pages contain all the type and layer styles used through out the kit; changing them here will populate the changes through all the components, and will give you a great head start in customizing the components to match your client's brand
- **Components:** Where you will find the building blocks to craft your PWA, AMP and Native app pages. This page acts as a directory of the components supported in the Mobify SDK.
- **Layouts:** A page of Mobify’s recommended best practice mobile commerce templates. These templates are designed as starting points and examples of a typical shopping experience, but you should make the effort to customize your designs to your client—and their customer's—needs.
- **Symbols:** Where most component customization will take place. Double clicking on a component layer will take you to this page where you can make changes and apply those to components across the Sketch file.

### Renaming components

The component included in the UI Kit are **named to be inline with their code counterparts**. This gives developers a reference of which components you've used. Renaming components is not recommended as it removes this parity.

### Finding components

To help locate certain components we've organized them into logical groups:

- `[action]` - calls to action (buttons)
- `[form]` - all form elements and inputs
- `[general]` - general use components that could be used anywhere
- `[global]` - components that appear on any and every page (navigation, search, etc.)
- `[icon]` - icons and their variations
- `[product]` - components specific to viewing and buying products
- `[type]` - headings, notes and paragraphs

### Customizing Components

Customizing colors and icons are done within the setup pages. Double click on a color to edit the Symbol and use the refresh buttons in the Inspector window to apply the new color across all components. Rearranging a component’s internal elements is possible, and often required by the brand, but it is important to be aware that these deviations from the standard components may impact development velocity.

Before heavily customizing components, first review your designs with your development team to ensure it’s feasible and will not threaten your project timelines.

## Sharing with Developers

Eventually you will need to pass them onto your developers. They may not have access to Sketch, and while you _could_ pass along flats, you'll be losing one of the benefits of using the UI Kit: the reference to its code counterparts and CSS values.

We recommend using [InVision Inspect](https://support.invisionapp.com/hc/en-us/articles/207950906-Introduction-to-Inspect) to communicate the designs. These tools allow developers to reference component names without the need to have Sketch itself installed.

## Requesting a New Component

Did you see something missing from the kit that we just _need_ to have? If you're not comfortable adding it to the Sketch file yourself, create an [issue](/issues) in the parent GitHub repo.
