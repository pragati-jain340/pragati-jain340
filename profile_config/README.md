# Profile README Content Map

This folder is your editable content source for the GitHub profile README.

## Main file to edit
- `data.ts` → update text, links, section visibility, project details, and tech stack icons here.

## Images used in the profile
- `../mydp_image.png` → profile picture
- `../my_center_image.png` → center/hero illustration
- `../techstack_images/*.svg` → tech stack icons

## How to update things quickly

### Change intro text
Edit these fields in `data.ts`:
- `profileData.name`
- `profileData.title`
- `profileData.tagline`

### Change links
Edit:
- `profileData.email`
- `profileData.linkedin`
- `profileData.github`
- `profileData.portfolio`

### Add or remove tech stack icons
Use this format inside `techStack.languages` or `techStack.tools`:

```ts
{ name: "New Tech", icon: "./techstack_images/your-image.svg" }
```

### Add AI/ML keywords
Update the `techStack.aiMl` array.

### Add projects
Append a new object in `profileData.projects`:

```ts
{
  name: "Project Name",
  summary: "Short one-line description",
  tech: ["Tech 1", "Tech 2", "Tech 3"],
}
```

### Show/hide sections
Use the booleans in `readmeSections`:
- `showTypingBanner`
- `showHeroImage`
- `showProfileImage`
- `showStats`
- `showTrophies`
- `showSnake`
- `showQuote`

## Important note
GitHub renders `README.md`, not `data.ts` directly.

This setup is made so you can keep all your content organized in one place and easily copy/update the same values in the main `README.md` whenever you want to redesign your profile later.
