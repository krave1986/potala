# potala
Container workflow for random repo.

## The problem I hope to solve
For example, there is a book I want to read with companion code examples.
I surely hope to use the entire code base in container without poluting my file trees.
No need say that the code base is Linux based and my working system is Windows.

My current workflow is to fork the repo. Add devcontainer files. Clone the repo and build the container.

Given that most of the official images are minimized. The problem is that I need to try many times to get what really works for me.

The ideal solution would be that I do not need to fork and write down devcontainer files by myself. And devcontainer files can be infered automatically.