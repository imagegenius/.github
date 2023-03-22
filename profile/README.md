## ImageGenius

My focus with ImageGenius is all about creating minimal and monolithic Docker images. I believe that less is more when it comes to these images. By keeping them minimal, they're less likely to break and run faster. And by keeping them monolithic, it's easier to maintain them and keep track of what's going on. Plus, it just makes sense to me to keep things simple.

The images in this organisation use the _"LSIO Way"_, meaning that appdata is mounted to /config, support for proper GID/UID etc...

CI is also based on [linuxserver/docker-jenkins-builder](https://github.com/linuxserver/docker-jenkins-builder)

I created this organisation mainly as an education project for myself, but if anyone else finds it useful, that's just a bonus. I'm always happy to consider requests for new images, so if you're after something specific, just open an issue [here](https://github.com/imagegenius/.github/issues).

I can guarantee that I'll do my best to keep the images up-to-date and maintain them for as long as I'm using them in production. But let's be real, sometimes life gets in the way and I can't always be bothered. But I'll do my best.
