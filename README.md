# reddit-username
Systematic search for available #-char usernames via the [Reddit API](https://www.reddit.com/dev/api/), using [Google 10,000 English](https://github.com/first20hours/google-10000-english) as the base dictionary.

### Setup
```bash
git clone <repo>
cd reddit-username/
```
In `reddit_username.py`, set `YOUR_USERNAME` to **your existing** reddit username.

### Usage

#### Search for availability of specific username
```
python reddit_username.py <username>
```
#### Search for availability of #-character usernames
In `reddit_username.py`, first set `NUM_CHARS` to the # of characters (default is 4).
```
python reddit_username.py
```
Advanced: to use a larger/different dictionary of words, modify `dictionary_link`
