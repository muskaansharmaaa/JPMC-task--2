# JPMC-task--2

C:\Users\Muskaan\JPMC-tech-task-2-PY3>node-gyp configure --msvs_version=2017
gyp info it worked if it ends with ok
gyp info using node-gyp@6.1.0
gyp info using node@11.0.0 | win32 | x64
gyp info find Python using Python version 3.8.3 found at "C:\Users\Muskaan\AppData\Local\Programs\Python\Python38\python.exe"
gyp info find VS using VS2017 (15.9.28307.1146) found at:
gyp info find VS "C:\Program Files (x86)\Microsoft Visual Studio\2017\BuildTools"
gyp info find VS run with --verbose for detailed information
gyp info spawn C:\Users\Muskaan\AppData\Local\Programs\Python\Python38\python.exe
gyp info spawn args [ 'C:\\Users\\Muskaan\\AppData\\Roaming\\nvm\\v11.0.0\\node_modules\\node-gyp\\gyp\\gyp_main.py',
gyp info spawn args   'binding.gyp',
gyp info spawn args   '-f',
gyp info spawn args   'msvs',
gyp info spawn args   '-I',
gyp info spawn args   'C:\\Users\\Muskaan\\JPMC-tech-task-2-PY3\\build\\config.gypi',
gyp info spawn args   '-I',
gyp info spawn args   'C:\\Users\\Muskaan\\AppData\\Roaming\\nvm\\v11.0.0\\node_modules\\node-gyp\\addon.gypi',
gyp info spawn args   '-I',
gyp info spawn args   'C:\\Users\\Muskaan\\AppData\\Local\\node-gyp\\Cache\\11.0.0\\include\\node\\common.gypi',
gyp info spawn args   '-Dlibrary=shared_library',
gyp info spawn args   '-Dvisibility=default',
gyp info spawn args   '-Dnode_root_dir=C:\\Users\\Muskaan\\AppData\\Local\\node-gyp\\Cache\\11.0.0',
gyp info spawn args   '-Dnode_gyp_dir=C:\\Users\\Muskaan\\AppData\\Roaming\\nvm\\v11.0.0\\node_modules\\node-gyp',
gyp info spawn args   '-Dnode_lib_file=C:\\\\Users\\\\Muskaan\\\\AppData\\\\Local\\\\node-gyp\\\\Cache\\\\11.0.0\\\\<(target_arch)\\\\node.lib',
gyp info spawn args   '-Dmodule_root_dir=C:\\Users\\Muskaan\\JPMC-tech-task-2-PY3',
gyp info spawn args   '-Dnode_engine=v8',
gyp info spawn args   '--depth=.',
gyp info spawn args   '--no-parallel',
gyp info spawn args   '--generator-output',
gyp info spawn args   'C:\\Users\\Muskaan\\JPMC-tech-task-2-PY3\\build',
gyp info spawn args   '-Goutput_dir=.' ]
gyp: binding.gyp not found (cwd: C:\Users\Muskaan\JPMC-tech-task-2-PY3) while trying to load binding.gyp
gyp ERR! configure error
gyp ERR! stack Error: `gyp` failed with exit code: 1
gyp ERR! stack     at ChildProcess.onCpExit (C:\Users\Muskaan\AppData\Roaming\nvm\v11.0.0\node_modules\node-gyp\lib\configure.js:351:16)
gyp ERR! stack     at ChildProcess.emit (events.js:182:13)
gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:240:12)
gyp ERR! System Windows_NT 10.0.18362
gyp ERR! command "C:\\Program Files\\nodejs\\node.exe" "C:\\Program Files\\nodejs\\node_modules\\node-gyp\\bin\\node-gyp.js" "configure" "--msvs_version=2017"
gyp ERR! cwd C:\Users\Muskaan\JPMC-tech-task-2-PY3
gyp ERR! node -v v11.0.0
gyp ERR! node-gyp -v v6.1.0
gyp ERR! not ok


i am facing error in creating binding.gyp file ..please help me 
