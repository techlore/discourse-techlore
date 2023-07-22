# discourse-techlore

![screenshot](categories.png)

**This is the theme for the [Techlore Discussions](https://discuss.techlore.tech) forum.** It is a fork of the [discourse-air](https://github.com/discourse/discourse-air) theme. We do not provide support for self-hosting. This theme is installed alongside a handful of theme components as well:

- [Dark Light Scheme Toggle](https://github.com/discourse/discourse-color-scheme-toggle.git)
- [DiscoTOC](https://github.com/discourse/DiscoTOC.git)
- [Clickable Topics](https://github.com/discourse/discourse-clickable-topic.git)
- [Discourse Search Banner](https://github.com/discourse/discourse-search-banner.git)
- [Experimental User Card](https://github.com/discourse/experimental-usercard.git)
- [Highlight Groups](https://git.jonaharagon.net/jonah/discourse-highlight-groups.git)
- [Modern Category + Group Boxes](https://github.com/jordanvidrine/discourse-category-group-boxes.git)
- [Techlore Sidebar Sponsors](https://github.com/techlore/discourse-sidebar-sponsors.git)

---

## Tips

> :exclamation: Please read through these tips upon installation, as there are a couple of settings that **NEED TO BE ENABLED** for this to theme to render properly.

### Dark Light Scheme Toggle

For this to work properly, at least 2 color scheme choices need to be enabled in your `/admin/customize/colors` area. At least two colors need to have `color scheme can be selected by users` enabled.

![image](https://user-images.githubusercontent.com/5862206/214545647-e0544474-b6bf-4b9c-8c64-6a8bfa6ba83a.png)

Once this is done, users should be able to choose between two color schemes as their `light` and `dark` preferences in their user preferences interface menu.

![image](https://user-images.githubusercontent.com/5862206/214545707-170a6b88-8ccd-4d31-af59-f0834a4fad3c.png)

### Discourse Search Banner

In the options for the `discourse-search-banner` theme component, the `plugin-outlet` options needs to be set to **BELOW-SITE-HEADER** for this theme to render properly.

![image](https://user-images.githubusercontent.com/5862206/214545774-ed8f1322-9a95-4958-bba0-adf7ff6dea3f.png)

### Modern Category + Group Boxes

This theme component requires your categories to use the **CATEGORY BOXES WITH SUBCATEGORIES** setting in your `/admin/site_settings/category/all_results?filter=categories` area.

![image](https://user-images.githubusercontent.com/5862206/214545903-c4bd61b9-1893-48e0-84e7-502efc26c46d.png)

This theme component also allows the forum admin to organize their category page with header titles, and choose which categories appear under each header. To keep things simple, I have only allowed up to 5 headings to be used. **If no categories + heading settings are chosen, all categories will render as they do above, this is the default rendering option.**
