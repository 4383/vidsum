## Generate summary of any video

Generate a summary of any video through its subtitles.

This is the community driven approach towards the summarization by the **[OpenGenus](https://github.com/opengenus)** community.

# Installing vidsum

In order to install vidsum: 
- simply clone the repository to a local directory.
- install pbr as a dependency for building the package.
- install vidsum

You can do this by running the following commands:
```sh
$ git clone https://github.com/OpenGenus/vidsum.git
$ pip install pbr
$ python setup.py install
```
The previous command automaticaly install all requirements needed.

# Usage

To generate summary of a video file `sample.mp4` with subtitle file `subtitle.srt` :
```python
vidsum -i sample.mp4 -s subtitle.srt
```
To summarize a YouTube video from its url:
```python
vidsum -u <url>
```
If you want to remain the downloaded YouTube video and subtitles:
```python
vidsum -u <url> -k
```
 
# Future developments

For future development to this approach, see [Wiki](https://github.com/OpenGenus/vidsum/wiki/Future_developments) and check out other [approaches](https://github.com/OpenGenus/vidsum/wiki/Other-approaches).

# Contributions

All contributions are welcomed. Please see [COMMIT_TEMPLATE.md](https://github.com/OpenGenus/vidsum/blob/master/.github/COMMIT_TEMPLATE.md) before making pull requests to this repository. See all contributors [here](https://github.com/OpenGenus/vidsum/graphs/contributors).
