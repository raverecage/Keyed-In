# Keyed In

A typing practice app for people who learn a few new keys every day. Tell it which keys you know, and it gives you endless words made only from those keys. It's one HTML file. No install, no build, no dependencies. Just open it and type.

## Heads up: this was made with AI

I made this for my own personal use, and I don't know how to program. The whole app was written by an AI (Claude), and no human has reviewed or verified the code. It works for me, but the code could be messy, inefficient or just plain wrong in places, and there may be bugs I haven't noticed. Use it at your own risk, and don't expect it to be polished or well maintained.

## What it does

- **Pick your keys.** Click keys on the on-screen QWERTY keyboard, one at a time or a whole row at once (number, top, home, bottom). You only get words made from the keys you've picked.
- **Capital letters.** Tick "Include capital letters" next to the rest setting and some words will start with a capital, with the occasional short word in all caps. The hint tells you which Shift key to use (the one on the opposite hand).
- **Real words when possible.** There are about 2,900 built-in words. If your keys can't make many real words (say, just `a s d f`), it mixes in practice patterns and tells you how many real words it found.
- **Advanced words.** Around 530 long, awkward words like "rhythm", "queue" and "mischievous". They unlock once all 26 letter keys are on.
- **Rests for your fingers.** Every 3, 5, 8 or 10 minutes of actual typing, you get a short rest with a few stretches, and a longer break every so often. The clock only runs while you're typing.
- **Hints.** It highlights the next key and tells you which finger to use. You can turn that off.
- **Feedback.** Live words per minute, accuracy and word count. Wrong letters show red, and letters you fixed after a mistake show yellow.
- **Missed keys.** Keys you keep getting wrong get a red dot and show up more in your practice. Also optional.
- **Light and dark mode.** Follows your system setting and works fine on a phone screen.

## How to use it

1. Download `keyed-in.html`.
2. Open it in your browser.
3. Click the keys you've learned.
4. Start typing. Space moves to the next word, Backspace fixes mistakes.

The timer starts with your first keystroke. When it's rest time, you'll get a countdown and some stretches. Hit Enter or click the button when you're ready to go again.

## Saving your progress

Your keys, settings and stats save automatically in the browser. Some browsers wipe that (private windows, strict privacy settings, Safari), so there are two backups:

- **Save into this file** (Chrome and Edge): click it once, pick the HTML file, and your progress gets written into the file itself. After reopening the file you might see a Reconnect button, which just lets it keep saving.
- **Export / Import backup** (any browser): makes a small `Keyed_in_data.json` you can restore later.

If you swap in a newer version of the app, export a backup first and import it afterwards.

## Good to know

- QWERTY only for now.
- It checks that you typed the right character, but not which Shift key you held. The hint shows the proper one.
- Shifted symbols like `!` and `?` aren't added yet, just capital letters.
- Caps Lock shows up as a warning because it makes every letter count as a mistake.
- Fonts load from Google Fonts. Offline, it falls back to your system fonts and works the same.

## Contributing

The whole app lives in one file (markup, then styles, then script), so it's easy to dig into and fork. I do not know if I will come back to this repo.

## License

MIT. Do pretty much whatever you like with it. See `LICENSE` for the details. As the license says, it comes with no warranty.
