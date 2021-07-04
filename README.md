# Icecast

**Icecast** is a streaming media server which currently supports Ogg Vorbis and MP3 audio streams. It can be used to create an Internet radio station or a privately running jukebox and many things in between. It is very versatile in that new formats can be added relatively easily and supports open standards for communication and interaction.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/icecast
$ dnf install -y icecast
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y icecast
```

## Remove

```
$ dnf erase -y icecast
$ dnf copr remove pkgstore/icecast
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/icecast).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/icecast) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
