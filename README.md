# LSP

Language Server Protocol support for Sublime Text 3

# Workable language servers

Python language server (Palantir) (https://github.com/palantir/python-language-server)
* Has not upgraded to LSP 3
* requires `rootPath` to be set
* raises KeyError on hover (workspace.py: `return self._docs[doc_uri]`)

Javascript/Typescript language server (Sourcegraph) (https://github.com/sourcegraph/javascript-typescript-langserver)
* Has some issues resolving types due to module loading strategy.

# Other language servers

Rust language server
Scala (dotty) language server
Microsoft's CPP service (not sure what dialect of LSP it speaks)

# Developing

If you are using Pyls, be sure the language server is running in a Python 3 interpreter (eg. on OS-X, you may need to activate a virtualenv before lauching subl)

