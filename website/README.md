Created by Bernardo Goncalves

bernardovm@DESKTOP-639SD90:~/Development/code/Bretts-website$ code --help
code 1.96.0

Usage: code [options][paths...]

To read from stdin, append '-' (e.g. 'ps aux | grep code | code -')

Options
  -d --diff <file> <file>                    Compare two files with each other.
  -m --merge <path1> <path2> <base> <result> Perform a three-way merge by providing paths for two modified versions of a file, the common origin of both modified versions and the
                                             output file to save merge results.
  -a --add <folder>                          Add folder(s) to the last active window.
  -g --goto <file:line[:character]>          Open a file at the path on the specified line and character position.
  -n --new-window                            Force to open a new window.
  -r --reuse-window                          Force to open a file or folder in an already opened window.
  -w --wait                                  Wait for the files to be closed before returning.
  -h --help                                  Print usage.

Extensions Management
  --list-extensions                   List the installed extensions.
  --show-versions                     Show versions of installed extensions, when using --list-extensions.
  --category <category>               Filters installed extensions by provided category, when using --list-extensions.
  --install-extension <ext-id | path> Installs or updates an extension. The argument is either an extension id or a path to a VSIX. The identifier of an extension is
                                      '${publisher}.${name}'. Use '--force' argument to update to latest version. To install a specific version provide '@${version}'. For example:
                                      'vscode.csharp@1.2.3'.
  --uninstall-extension <ext-id>      Uninstalls an extension.
  --update-extensions                 Update the installed extensions.

Troubleshooting
  -v --version Print version.
  --verbose    Print verbose output (implies --wait).
  -s --status  Print process usage and diagnostics information.