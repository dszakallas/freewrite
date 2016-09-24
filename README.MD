# freewrite

Little tool that helps you freewrite every day. Opens up your `$EDITOR`
to write, then saves and encrypts it with `gpg`, so you can open it later.

The basic rules of free writing were captured pretty nicely by Natalie Goldberg (lightly edited version of the Wikipedia entry):
 1. Give yourself a word limit. Write for 1, 2, or 3 pages, and then stop.
 2. Keep writing until the time is up. Do not pause to stare into space or to read what you’ve written. Write quickly but not in a hurry.
 3. Pay no attention to grammar, spelling, punctuation, neatness, or style. Nobody else should ever read what you produce here. The correctness and quality of what you write do not matter; the act of writing does.
 4. If you get off the topic or run out of ideas, keep writing anyway. If necessary, write nonsense or whatever comes into your head: anything to keep the words flowing.
 5. If you feel bored or uncomfortable as you’re writing, ask yourself what’s bothering you and write about that.

Additionally: encrypt your writing with a password to make sure others don't have a chance reading it!

## Usage

```
usage:
  freewrite [create]            create today's writing
  freewrite open <yyyy-mm-dd>   open a writing
  freewrite edit <yyyy-mm-dd>   edit a writing
```

Note: Your writings will be at `$HOME/.freewrite`
