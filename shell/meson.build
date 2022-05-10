
minicshell_shell_incl = [ include_directories('include') ]
minicshell_shell_srcs = [
    'src/source.c'
]
minicshell_shell_args = []
minicshell_shell_link = []
minicshell_shell_deps = []

## demo executable
minicshell_shell_exe = executable('minicshell',
                            minicshell_shell_srcs,
                            include_directories: minicshell_shell_incl,
                            c_args: minicshell_shell_args,
                            dependencies: minicshell_shell_deps,
                            link_with: minicshell_shell_link)