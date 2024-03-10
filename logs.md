2024-03-09T14:47:06+01:00 Process is gone
2024-03-09T14:47:06+01:00 GET http://10.2.163.154:8080/ returned 502!
2024-03-09T14:47:06+01:00 goodbye to uWSGI.
2024-03-09T14:47:06+01:00 worker 2 buried after 1 seconds
End of logs for deployment 10 - 2024-03-09 14:46 - Status: FAIL
Beginning of logs for deployment 11 - 2024-03-09 14:55 - Status: FAIL
2024-03-09T14:55:28+01:00 (CRON) INFO (running with inotify support)
2024-03-09T14:55:28+01:00 (CRON) STARTUP (1.7.1)
2024-03-09T14:55:28+01:00 (CRON) INFO (RANDOM_DELAY will be scaled with factor 11% if used.)
2024-03-09T14:55:28+01:00 WARNING: Nokogiri was built against libxml version 2.11.4, but has dynamically loaded 2.11.7
2024-03-09T14:55:28+01:00 WARNING: Nokogiri was built against libxslt version 1.1.38, but has dynamically loaded 1.1.39
2024-03-09T14:55:28+01:00 WARNING: Nokogiri was built against libxslt version 1.1.38, but has dynamically loaded 1.1.39
2024-03-09T14:55:28+01:00 WARNING: Nokogiri was built against libxml version 2.11.4, but has dynamically loaded 2.11.7
2024-03-09T14:55:28+01:00 Setting up system
2024-03-09T14:55:28+01:00 Created symlink /etc/systemd/system/multi-user.target.wants/telegraf.service → /usr/x86_64-pc-linux-gnu/lib/systemd/system/telegraf.service.
2024-03-09T14:55:28+01:00 Created symlink /etc/systemd/system/multi-user.target.wants/action-dispatcher.service → /usr/x86_64-pc-linux-gnu/lib/systemd/system/action-dispatcher.service.
2024-03-09T14:55:28+01:00 Configuring /etc/vector/vector.conf to crawl logs...
2024-03-09T14:55:28+01:00 Preparing application environment…
2024-03-09T14:55:28+01:00 Starting vector.service...
2024-03-09T14:55:28+01:00 Created symlink /etc/systemd/system/multi-user.target.wants/rsyslog.service → /usr/x86_64-pc-linux-gnu/lib/systemd/system/rsyslog.service.
2024-03-09T14:55:29+01:00 Created symlink /etc/systemd/system/multi-user.target.wants/vector@cc-runtime.service → /usr/x86_64-pc-linux-gnu/lib/systemd/system/vector@.service.
2024-03-09T14:55:30+01:00 Added sourceable file /home/bas/applicationrc
2024-03-09T14:55:30+01:00 Inject APP_ID
2024-03-09T14:55:30+01:00 Inject PORT
2024-03-09T14:55:30+01:00 Inject CC_OWNER_ID
2024-03-09T14:55:30+01:00 Inject CC_DEPLOYMENT_ID
2024-03-09T14:55:30+01:00 Inject INSTANCE_NUMBER
2024-03-09T14:55:30+01:00 vector.service started
2024-03-09T14:55:30+01:00 Cloning into '/home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94'...
2024-03-09T14:55:30+01:00 Inject CC_APP_ID
2024-03-09T14:55:30+01:00 Inject CC_COMMIT_ID
2024-03-09T14:55:30+01:00 Inject CC_INSTANCE_ID
2024-03-09T14:55:30+01:00 Inject CC_REVERSE_PROXY_IPS
2024-03-09T14:55:30+01:00 Inject CC_PRETTY_INSTANCE_NAME
2024-03-09T14:55:30+01:00 Inject COMMIT_ID
2024-03-09T14:55:30+01:00 Inject managetasks
2024-03-09T14:55:30+01:00 Inject CC_USE_PULSAR_LOGSCOLLECTION
2024-03-09T14:55:30+01:00 Checking cache data: GET /api/builds/app_242bd1af-b099-4652-b690-cbe085b47c94/7e10a0c0d121ee18660c71beed032cdfb8e4e0a1/python-20240217
2024-03-09T14:55:30+01:00 Inject CC_PYTHON_VERSION
2024-03-09T14:55:30+01:00 Inject CC_PYTHON_MODULE
2024-03-09T14:55:30+01:00 Inject INSTANCE_TYPE
2024-03-09T14:55:30+01:00 Inject CC_APP_NAME
2024-03-09T14:55:30+01:00 No build cache archive has been detected. Performing a new build…
2024-03-09T14:55:30+01:00 Inject APP_HOME
2024-03-09T14:55:30+01:00 Inject INSTANCE_ID
2024-03-09T14:55:30+01:00 Inject CC_ENVIRON_UPDATE_URL
2024-03-09T14:55:30+01:00 Inject CC_ENVIRON_UPDATE_TOKEN
2024-03-09T14:55:30+01:00 Note: switching to '7e10a0c0d121ee18660c71beed032cdfb8e4e0a1'.
2024-03-09T14:55:30+01:00 Warning: Permanently added 'push-n3-par-clevercloud-customers.services.clever-cloud.com' (ED25519) to the list of known hosts.
2024-03-09T14:55:30+01:00 You are in 'detached HEAD' state. You can look around, make experimental
2024-03-09T14:55:30+01:00 changes and commit them, and you can discard any commits you make in this
2024-03-09T14:55:30+01:00 do so (now or later) by using -c with the switch command. Example:
2024-03-09T14:55:30+01:00 If you want to create a new branch to retain commits you create, you may
2024-03-09T14:55:30+01:00 state without impacting any branches by switching back to a branch.
2024-03-09T14:55:30+01:00 | o o + * |
2024-03-09T14:55:30+01:00 | o . o o + |
2024-03-09T14:55:30+01:00 The key's randomart image is:
2024-03-09T14:55:30+01:00 Your public key has been saved in /home/bas/.ssh/id_ed25519.pub
2024-03-09T14:55:30+01:00 Generating public/private ed25519 key pair.
2024-03-09T14:55:30+01:00 HEAD is now at 7e10a0c back to photo in settings.py
2024-03-09T14:55:30+01:00 Turn off this advice by setting config variable advice.detachedHead to false
2024-03-09T14:55:30+01:00 Or undo this operation with:
2024-03-09T14:55:30+01:00 git switch -c <new-branch-name>
2024-03-09T14:55:30+01:00 +----[SHA256]-----+
2024-03-09T14:55:30+01:00 | . . S o |
2024-03-09T14:55:30+01:00 |o.= * = * . |
2024-03-09T14:55:30+01:00 +--[ED25519 256]--+
2024-03-09T14:55:30+01:00 SHA256:lCyJyesnAA0iVoo9VnPnU50k7t9oCQJI3q/7pc7Fj2U bas@0599e4fa-bdf2-441e-8e57-45190e8eab77
2024-03-09T14:55:30+01:00 The key fingerprint is:
2024-03-09T14:55:30+01:00 Your identification has been saved in /home/bas/.ssh/id_ed25519
2024-03-09T14:55:30+01:00 git switch -
2024-03-09T14:55:30+01:00 | .o= . . |
2024-03-09T14:55:30+01:00 | o o + E . |
2024-03-09T14:55:30+01:00 | o . . = o |
2024-03-09T14:55:30+01:00 |=+.= B = + .o |
2024-03-09T14:55:30+01:00 |+...+ . . oo.. |
2024-03-09T14:55:31+01:00 Created symlink /etc/systemd/system/multi-user.target.wants/shiva-hand.service → /usr/x86_64-pc-linux-gnu/lib/systemd/system/shiva-hand.service.
2024-03-09T14:55:31+01:00 Mounting persistent file system
2024-03-09T14:55:31+01:00 No Clever Cloud specific configuration file detected. Continuing…
2024-03-09T14:55:31+01:00 Changing current directory to /home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94…
2024-03-09T14:55:31+01:00 using python version 3.11
2024-03-09T14:55:32+01:00 We are now in /home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94, let's build and run the app.
2024-03-09T14:55:32+01:00 Deploying commit ID 7e10a0c0d121ee18660c71beed032cdfb8e4e0a1
2024-03-09T14:55:41+01:00 requirements.txt found, using pip...
2024-03-09T14:55:42+01:00 Collecting sqlparse>=0.3.1 (from Django==5.0.3->-r requirements.txt (line 1))
2024-03-09T14:55:42+01:00 Obtaining dependency information for asgiref<4,>=3.7.0 from https://files.pythonhosted.org/packages/9b/80/b9051a4a07ad231558fcd8ffc89232711b4e618c15cb7a392a17384bbeef/asgiref-3.7.2-py3-none-any.whl.metadata
2024-03-09T14:55:42+01:00 Downloading Django-5.0.3-py3-none-any.whl (8.2 MB)
2024-03-09T14:55:42+01:00 Obtaining dependency information for sqlparse>=0.3.1 from https://files.pythonhosted.org/packages/98/5a/66d7c9305baa9f11857f247d4ba761402cea75db6058ff850ed7128957b7/sqlparse-0.4.4-py3-none-any.whl.metadata
2024-03-09T14:55:42+01:00 Collecting asgiref<4,>=3.7.0 (from Django==5.0.3->-r requirements.txt (line 1))
2024-03-09T14:55:42+01:00 Downloading Django-5.0.3-py3-none-any.whl.metadata (4.2 kB)
2024-03-09T14:55:42+01:00 Collecting Django==5.0.3 (from -r requirements.txt (line 1))
2024-03-09T14:55:42+01:00 Downloading sqlparse-0.4.4-py3-none-any.whl.metadata (4.0 kB)
2024-03-09T14:55:42+01:00 Downloading asgiref-3.7.2-py3-none-any.whl.metadata (9.2 kB)
2024-03-09T14:55:42+01:00 Obtaining dependency information for Django==5.0.3 from https://files.pythonhosted.org/packages/9c/5b/eed82065c5d938b17c4b7304ab5ebe762c7a5a7eaa8a10ab35541580d79a/Django-5.0.3-py3-none-any.whl.metadata
2024-03-09T14:55:42+01:00 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.2/8.2 MB 48.9 MB/s eta 0:00:00
2024-03-09T14:55:42+01:00 Downloading sqlparse-0.4.4-py3-none-any.whl (41 kB)
2024-03-09T14:55:42+01:00 Downloading asgiref-3.7.2-py3-none-any.whl (24 kB)
2024-03-09T14:55:42+01:00 Installing collected packages: sqlparse, asgiref, Django
2024-03-09T14:55:42+01:00 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 41.2/41.2 kB 5.3 MB/s eta 0:00:00
2024-03-09T14:55:45+01:00 Successfully installed Django-5.0.3 asgiref-3.7.2 sqlparse-0.4.4
2024-03-09T14:55:45+01:00 [notice] To update, run: pip install --upgrade pip
2024-03-09T14:55:45+01:00 [notice] A new release of pip is available: 23.2.1 -> 24.0
2024-03-09T14:55:46+01:00 tar: /home/bas/.local: Warning: Cannot stat: No such file or directory
2024-03-09T14:55:46+01:00 Creating build cache archive
2024-03-09T14:55:46+01:00 Created symlink /etc/systemd/system/multi-user.target.wants/nginx.service → /usr/x86_64-pc-linux-gnu/lib/systemd/system/nginx.service.
2024-03-09T14:55:46+01:00 Running as unit: bas-deploy.service; invocation ID: eb0e444324d542ff862d5a93851c6f7f
2024-03-09T14:55:46+01:00 Added envdir /home/bas/envdir
2024-03-09T14:55:46+01:00 build cache archive successfully created
2024-03-09T14:55:47+01:00 nginx: [warn] could not build optimal types_hash, you should increase either types_hash_max_size: 1024 or types_hash_bucket_size: 64; ignoring types_hash_bucket_size
2024-03-09T14:55:49+01:00 spawned uWSGI worker 1 (pid: 1978, cores: 1)
2024-03-09T14:55:49+01:00 *** Operational MODE: preforking ***
2024-03-09T14:55:49+01:00 python threads support enabled
2024-03-09T14:55:49+01:00 uwsgi socket 0 bound to TCP address 127.0.0.1:9000 fd 6
2024-03-09T14:55:49+01:00 thunder lock: disabled (you can enable it with --thunder-lock)
2024-03-09T14:55:49+01:00 your processes number limit is 4324
2024-03-09T14:55:49+01:00 chdir() to /home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94/
2024-03-09T14:55:49+01:00 nodename: 0599e4fa-bdf2-441e-8e57-45190e8eab77
2024-03-09T14:55:49+01:00 os: Linux-6.7.1-dirty #1 SMP Tue Jan 23 13:55:22 UTC 2024
2024-03-09T14:55:49+01:00 spawned uWSGI worker 2 (pid: 1979, cores: 1)
2024-03-09T14:55:49+01:00 spawned uWSGI master process (pid: 1977)
2024-03-09T14:55:49+01:00 mapped 329352 bytes (321 KB) for 2 cores
2024-03-09T14:55:49+01:00 your server socket listen backlog is limited to 500 connections
2024-03-09T14:55:49+01:00 Python main interpreter initialized at 0x7f69dbd36ed8
2024-03-09T14:55:49+01:00 Set PythonHome to /home/bas/venv
2024-03-09T14:55:49+01:00 Python version: 3.11.7 (main, Dec 6 2023, 20:03:57) [GCC 13.2.0]
2024-03-09T14:55:49+01:00 your memory page size is 4096 bytes
2024-03-09T14:55:49+01:00 detected binary path: /usr/x86_64-pc-linux-gnu/bin/uwsgi
2024-03-09T14:55:49+01:00 writing pidfile to /home/bas/uwsgi.pid
2024-03-09T14:55:49+01:00 current working directory: /home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94
2024-03-09T14:55:49+01:00 detected number of CPU cores: 1
2024-03-09T14:55:49+01:00 pcre jit disabled
2024-03-09T14:55:49+01:00 machine: x86_64
2024-03-09T14:55:49+01:00 *** Starting uWSGI 2.0.22 (64bit) on [Sat Mar 9 13:55:48 2024] ***
2024-03-09T14:55:49+01:00 [uWSGI] getting INI configuration from /home/bas/uwsgi.ini
2024-03-09T14:55:49+01:00 your mercy for graceful operations on workers is 60 seconds
2024-03-09T14:55:49+01:00 detected max file descriptor number: 65536
2024-03-09T14:55:49+01:00 *** uWSGI is running in multiple interpreter mode ***
2024-03-09T14:55:49+01:00 PEP 405 virtualenv detected: /home/bas/venv
2024-03-09T14:55:49+01:00 lock engine: pthread robust mutexes
2024-03-09T14:55:49+01:00 clock source: unix
2024-03-09T14:55:49+01:00 compiled with version: 13.2.0 on 28 November 2023 12:28:48
2024-03-09T14:55:49+01:00 Traceback (most recent call last):
2024-03-09T14:55:49+01:00 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
2024-03-09T14:55:49+01:00 ^^^^^^^^^^^^^^^^^^^^^^^
2024-03-09T14:55:49+01:00 File "/usr/host/lib/python3.11/importlib/__init__.py", line 126, in import_module
2024-03-09T14:55:49+01:00 ^^^^^^^^^^^^^^^^^^^^^^^
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/apps/config.py", line 178, in create
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/__init__.py", line 24, in setup
2024-03-09T14:55:49+01:00 app_config = AppConfig.create(entry)
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/apps/registry.py", line 91, in populate
2024-03-09T14:55:49+01:00 apps.populate(settings.INSTALLED_APPS)
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/__init__.py", line 24, in setup
2024-03-09T14:55:49+01:00 django.setup(set_prefix=False)
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/core/wsgi.py", line 12, in get_wsgi_application
2024-03-09T14:55:49+01:00 application = get_wsgi_application()
2024-03-09T14:55:49+01:00 File "/home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94/photoshare/photoshare/wsgi.py", line 16, in <module>
2024-03-09T14:55:49+01:00 SIGINT/SIGTERM received...killing workers...
2024-03-09T14:55:49+01:00 return _bootstrap._gcd_import(name[level:], package, level)
2024-03-09T14:55:49+01:00 mod = import_module(mod_path)
2024-03-09T14:55:49+01:00 ^^^^^^^^^^^^^^^^^^^^^^^
2024-03-09T14:55:49+01:00 mod = import_module(mod_path)
2024-03-09T14:55:49+01:00 app_config = AppConfig.create(entry)
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/core/wsgi.py", line 12, in get_wsgi_application
2024-03-09T14:55:49+01:00 ^^^^^^^^^^^^^^^^^^^^^^
2024-03-09T14:55:49+01:00 application = get_wsgi_application()
2024-03-09T14:55:49+01:00 Traceback (most recent call last):
2024-03-09T14:55:49+01:00 *** no app loaded. GAME OVER ***
2024-03-09T14:55:49+01:00 unable to load app 0 (mountpoint='') (callable not found or import error)
2024-03-09T14:55:49+01:00 ModuleNotFoundError: No module named 'photos'
2024-03-09T14:55:49+01:00 File "/usr/host/lib/python3.11/importlib/__init__.py", line 126, in import_module
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/apps/config.py", line 178, in create
2024-03-09T14:55:49+01:00 ^^^^^^^^^^^^^^^^^^^^^^^
2024-03-09T14:55:49+01:00 File "/home/bas/venv/lib/python3.11/site-packages/django/apps/registry.py", line 91, in populate
2024-03-09T14:55:49+01:00 apps.populate(settings.INSTALLED_APPS)
2024-03-09T14:55:49+01:00 django.setup(set_prefix=False)
2024-03-09T14:55:49+01:00 File "/home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94/photoshare/photoshare/wsgi.py", line 16, in <module>
2024-03-09T14:55:49+01:00 ^^^^^^^^^^^^^^^^^^^^^^
2024-03-09T14:55:49+01:00 unable to load app 0 (mountpoint='') (callable not found or import error)
2024-03-09T14:55:49+01:00 ModuleNotFoundError: No module named 'photos'
2024-03-09T14:55:49+01:00 *** no app loaded. GAME OVER ***
2024-03-09T14:55:50+01:00 OOPS ! failed loading app in worker 1 (pid 1978)
 Deploy failed in 0 minutes and 23 seconds. Please review the lines above to find out why
2024-03-09T14:55:50+01:00 Process is gone
2024-03-09T14:55:50+01:00 0599e4fa-bdf2-441e-8e57-45190e8eab77 nginx: 2024/03/09 13:55:50 [error] 1803#1803: *1 recv() failed (104: Connection reset by peer) while reading response header from upstream, client: 10.2.251.147, server: _, request: "GET / HTTP/1.1", upstream: "uwsgi://127.0.0.1:9000", host: "10.2.251.147:8080"
2024-03-09T14:55:50+01:00 goodbye to uWSGI.
2024-03-09T14:55:50+01:00 GET http://10.2.251.147:8080/ returned 502!
2024-03-09T14:55:50+01:00 worker 2 buried after 1 seconds
2024-03-09T14:55:50+01:00 Sat Mar 9 13:55:50 2024 - need-app requested, destroying the instance...
 Deploy failed
2024-03-09T14:55:50+01:00 nginx: [warn] could not build optimal types_hash, you should increase either types_hash_max_size: 1024 or types_hash_bucket_size: 64; ignoring types_hash_bucket_size