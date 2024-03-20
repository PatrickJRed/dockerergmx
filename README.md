# dockerergmx
public repository for docker images on https://hub.docker.com/u/dockerergmx

# project structure
- dir:base \
  basics like
- dir:building \
  contains tools and scripts for building
- dir:$IMAGE \
  foreach of my images a directory - dockerfiles, config-files and other needed files for $IMAGE

# images
- [ ] an alpine based tor node (https://hub.docker.com/r/dockerergmx/tor-alpine) \
      from alpine > install tor + add my own torrc-files
- [ ] unmodified youtube-dl (https://hub.docker.com/r/dockerergmx/ytdl) \
      from python(alpine-based) > install pip3 youtube-dl from github (URL) + add my own config
- [ ] modded youtube-dl (https://hub.docker.com/r/dockerergmx/ytdlmod) \
      from dockerergmx/ytdl > add more config + add modifications (e.g. for extractors and libraries)
- [ ] x1 (https://hub.docker.com/r/dockerergmx/x1) \
      from BASE > ACTIONS
- [ ] x2 (https://hub.docker.com/r/dockerergmx/x2) \
      from BASE > ACTIONS

# TODO
- [x] setup my local machine to work with this repo
- [x]? make folder structure locally (partially done)
- [ ] create tor-alpine and load files from private repo
- [ ] create ytdl and load files from private repo
- [ ] setup build-tools/-scripts
- [ ] setup CI/CD to automatically build, test and push images to https://hub.docker.com/u/dockerergmx
- [ ] TODO

# notice
for specific licenses see each dockerfile, image-directory or referenced software itself
