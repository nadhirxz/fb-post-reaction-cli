# fb-post-reaction-cli
Facebook post reaction CLI tool using [fb-post-reaction](https://github.com/nadhirxz/fb-post-reaction)

## Usage

Install dependencies

```
npm install
```

Run

```
node index [options] <post>
```
> *If you don't pass a username or password as arguments, the program will prompt you to write them.*

## Link

Use `npm link` to create a symlink to run `pwned` from anywhere

Now you can run
```
fb-post-reaction-cli [options] <post>
```

Use `npm unlink` to remove symlink


## Options
```
Arguments:
  post                           facebook post id

Options:
  -V, --version                  output the version number
  -u, --username <username>      facebook username/email/phone
  -p, --password <password>      facebook password
  -r, --reaction <reaction>      facebook reaction (choices: "like", "love", "care", "haha", "wow", "sad", "angry", default: "like")
  -h, --help                     display help for command
```