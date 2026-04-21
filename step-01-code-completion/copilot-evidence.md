
# Copilot Evidence — Step 01

Replace all placeholders.

## Prompt 1

Lets build 2 small functions in python as an effort to normalize a username string.
The first function named normalize_username(name: str) -> str , will normalize a username string with the following rules:
- Trim outer whitespace.
    - Convert to lowercase.
    - Replace spaces with underscores.
    - Remove any character that is not a-z, 0-9, or underscore.
    - Collapse repeated underscores into one underscore.
    - Strip leading/trailing underscores.

    The second function named build_slug(title : str) -> str , will convert a title into a URL-friendly slug, following these rules:
    - Lowercase.
        - Keep letters and digits.
        - Replace any sequence of non-alphanumeric characters with a single '-'.
        - Strip leading/trailing '-'.

## Why you accepted/rejected the suggestion

The answer provided was very clear and clean and followed the rules in a very efficient way.

## Final check

It changes the way it uses regex to analize the strings. By chan ging the regex queery, it sometimes adds it all in one line or other times it separates the regex to be used in several lines
