# LibrePCB.github.io

Official Website of LibrePCB

## Development

The website is made with [Hugo](https://gohugo.io/).

There are two branches in this repository:
- source: The source (content) to build the website with hugo
- master: The generated output (static HTML website)

### Steps to build the website

1. Switch to the ```source``` branch
2. Modify the content
3. Run ```hugo server``` --> the output is automatically witten into the ```master``` branch (see submodule ```public```)
4. Review the generated website
5. Commit the updated output in the submodule ```public```
6. Commit your changes in the ```source``` branch (inclusive the updated submodule)

