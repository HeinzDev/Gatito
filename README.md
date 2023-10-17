# Gatito

Just a cute terminal ascii art display for people who like cats.

<img src="https://i.imgur.com/rX90lPb.png">

## Running⚡

Remember to activate the execute permissions:

```bash
chmod +x gatito.sh
```

and

```bash
./gatito.sh
```

## Custom command

For an even smoother experience, I suggest creating a symbolic link in a custom folder that's part of your $PATH. Here's how to do it:

1. Open your ~/.bashrc file:

```bash
nano ~/.bashrc
```

2. Add the following line to the file, replacing `/my/custom/folder` with the actual path to your custom folder:

```bash
export PATH=$PATH:/my/custom/folder
```
3. Create the symbolic link replacing `/path/to/gatito.sh` with the path to the script and `/my/custom/folder/gatito` with your custom folder's path:

```bash
ln -s /path/to/gatito.sh /my/custom/folder/gatito
```

Now you can display the ASCII art with just:

<img src="https://i.imgur.com/MhQbeTB.png">



## Thanks✨

Enjoy the cuteness! 😸

<div id="header" align="center">
  <a href="https://github.com/HeinzDev/">
    <img src="https://i.imgur.com/RtsYtRt.png" width="100"/>
  </a>
  <h3>HeinzDev</h3>
</div>
