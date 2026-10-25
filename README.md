# Tokyo Night Cyan

A Discord theme for Vencord and Vesktop. It is a small set of overrides on top of frostqween's Tokyo Night theme: a cyan accent instead of blue, brighter secondary text, and no more white text on light fills.

This repo only contains my changes. The original theme is loaded from its own repository at runtime, so none of it is copied here.

## What it changes

- Cyan accent (#7dcfff) in place of the blue one.
- Secondary text (channel names, headers, placeholders, muted labels) is brighter, around 6:1 contrast against the background instead of under 3:1.
- Light cyan fills such as the new messages bar, bot tags and buttons get dark navy text and icons instead of white.
- Important fills are deep colors with white text instead of pastels: mention badges, danger and success buttons, banners, the Premium tab, and toggles that are on.

## Install

In Vencord or Vesktop, open Settings, then Vencord, then Themes. Paste this into Online Themes and turn it on:

    https://raw.githubusercontent.com/arch2kx/tokyo-night-cyan-discord/main/tokyo-night-cyan.theme.css

It imports the original theme, so you need to be online the first time Discord loads it.

## Notes

Discord renames its CSS classes now and then, and some of the rules here match those names, so an update can break a rule. If a badge or button looks wrong, open an issue with a screenshot.

I made and tested this on Discord with Vencord.

## Credits

Based on frostqween's Tokyo Night theme: https://github.com/frostqween/TokyoNightDiscordTheme. That theme credits Dyzean's Tokyo Night theme as inspiration, and the colors come from the Tokyo Night VS Code theme by enkia.

## License

MIT, for the overrides in this repo only. The original theme is not covered by this license and is not included here.
