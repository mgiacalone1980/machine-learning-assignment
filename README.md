# machine-learning-assignment

2016-05-19 15:18:08,261 INFO: - App: Building service dependencies...
2016-05-19 15:18:08,297 INFO: - App: Copying files and filling templates...
2016-05-19 15:18:08,314 INFO: - App: Building app image without Dockerfile...
2016-05-19 15:18:08,370 INFO: - App: Sending build context to Docker daemon 294.9 kB
Sending build context to Docker daemon 294.9 kB
2016-05-19 15:18:08,392 INFO: - App: Step 0 : FROM gcr.io/generic-notebooks/binder-base
2016-05-19 15:18:08,408 INFO: - App:  ---> ec294b209d39
2016-05-19 15:18:08,421 INFO: - App: Step 1 : ADD repo/requirements.txt requirements.txt
2016-05-19 15:18:08,687 INFO: - App:  ---> 29815dc3a85d
2016-05-19 15:18:08,699 INFO: - App: Removing intermediate container 15474cf948c2
2016-05-19 15:18:08,719 INFO: - App: Step 2 : ADD handle-requirements.py handle-requirements.py
2016-05-19 15:18:09,015 INFO: - App:  ---> d58f0aaccecc
2016-05-19 15:18:09,025 INFO: - App: Removing intermediate container 2b5c6e41a102
2016-05-19 15:18:09,043 INFO: - App: Step 3 : RUN python handle-requirements.py
2016-05-19 15:18:09,159 INFO: - App:  ---> Running in cd66387cca84
2016-05-19 15:18:09,372 INFO: - App: Executing: ['pip', 'install', '-r', 'requirements.txt']
2016-05-19 15:18:09,975 INFO: - App: Collecting seaborn (from -r requirements.txt (line 1))
2016-05-19 15:18:10,111 INFO: - App:   Downloading seaborn-0.7.0.tar.gz (154kB)
2016-05-19 15:18:12,992 INFO: - App: Building wheels for collected packages: seaborn
2016-05-19 15:18:13,001 INFO: - App:   Running setup.py bdist_wheel for seaborn: started
2016-05-19 15:18:14,236 INFO: - App:   Running setup.py bdist_wheel for seaborn: finished with status 'done'
2016-05-19 15:18:14,259 INFO: - App:   Stored in directory: /home/main/.cache/pip/wheels/e0/94/01/731d82dc437e1c8b65130956028f3fe693943c3e499a676dc9
2016-05-19 15:18:14,284 INFO: - App: Successfully built seaborn
2016-05-19 15:18:14,313 INFO: - App: Installing collected packages: seaborn
2016-05-19 15:18:14,834 INFO: - App: Successfully installed seaborn-0.7.0
2016-05-19 15:18:15,025 INFO: - App: You are using pip version 8.1.1, however version 8.1.2 is available.
2016-05-19 15:18:15,058 INFO: - App: You should consider upgrading via the 'pip install --upgrade pip' command.
2016-05-19 15:18:15,080 INFO: - App: Executing: ['/home/main/anaconda2/envs/python3/bin/pip', 'install', '-r', 'requirements.txt']
2016-05-19 15:18:16,238 INFO: - App: Collecting seaborn (from -r requirements.txt (line 1))
2016-05-19 15:18:16,297 INFO: - App:   Using cached seaborn-0.7.0.tar.gz
2016-05-19 15:18:19,942 INFO: - App: Building wheels for collected packages: seaborn
2016-05-19 15:18:19,965 INFO: - App:   Running setup.py bdist_wheel for seaborn: started
2016-05-19 15:18:21,662 INFO: - App:   Running setup.py bdist_wheel for seaborn: finished with status 'done'
2016-05-19 15:18:21,685 INFO: - App:   Stored in directory: /home/main/.cache/pip/wheels/e0/94/01/731d82dc437e1c8b65130956028f3fe693943c3e499a676dc9
2016-05-19 15:18:21,706 INFO: - App: Successfully built seaborn
2016-05-19 15:18:21,717 INFO: - App: Installing collected packages: seaborn
2016-05-19 15:18:22,304 INFO: - App: Successfully installed seaborn-0.7.0
2016-05-19 15:18:22,375 INFO: - App: You are using pip version 8.1.1, however version 8.1.2 is available.
2016-05-19 15:18:22,398 INFO: - App: You should consider upgrading via the 'pip install --upgrade pip' command.
2016-05-19 15:18:23,208 INFO: - App:  ---> cb6cbbb15349
2016-05-19 15:18:23,268 INFO: - App: Removing intermediate container cd66387cca84
2016-05-19 15:18:23,276 INFO: - App: Step 4 : USER root
2016-05-19 15:18:23,408 INFO: - App:  ---> Running in dde7c549d2b7
2016-05-19 15:18:23,498 INFO: - App:  ---> 0d6986867ae6
2016-05-19 15:18:23,512 INFO: - App: Removing intermediate container dde7c549d2b7
2016-05-19 15:18:23,536 INFO: - App: Step 5 : RUN apt-get update -y &&    apt-get install -y python-psycopg2 libpq-dev python-dev &&    apt-get clean
2016-05-19 15:18:23,615 INFO: - App:  ---> Running in d58ec1abe820
2016-05-19 15:18:24,537 INFO: - App: Get:1 http://security.debian.org jessie/updates InRelease [63.1 kB]
2016-05-19 15:18:24,802 INFO: - App: Ign http://httpredir.debian.org jessie InRelease
2016-05-19 15:18:24,852 INFO: - App: Get:2 http://httpredir.debian.org jessie-updates InRelease [142 kB]
2016-05-19 15:18:25,067 INFO: - App: Get:3 http://security.debian.org jessie/updates/main amd64 Packages [311 kB]
2016-05-19 15:18:25,096 INFO: - App: Get:4 http://httpredir.debian.org jessie Release.gpg [2373 B]
2016-05-19 15:18:25,205 INFO: - App: Get:5 http://httpredir.debian.org jessie Release [148 kB]
2016-05-19 15:18:25,499 INFO: - App: Get:6 http://httpredir.debian.org jessie-updates/main amd64 Packages [9283 B]
2016-05-19 15:18:25,579 INFO: - App: Get:7 http://httpredir.debian.org jessie/main amd64 Packages [9034 kB]
2016-05-19 15:18:27,209 INFO: - App: Fetched 9710 kB in 2s (3438 kB/s)
2016-05-19 15:18:28,769 INFO: - App: Reading package lists...
2016-05-19 15:18:30,469 INFO: - App: Reading package lists...
2016-05-19 15:18:30,768 INFO: - App: Building dependency tree...
2016-05-19 15:18:30,791 INFO: - App: Reading state information...
2016-05-19 15:18:30,875 INFO: - App: python-dev is already the newest version.
2016-05-19 15:18:30,899 INFO: - App: The following extra packages will be installed:
2016-05-19 15:18:30,913 INFO: - App:   comerr-dev krb5-multidev libgssapi-krb5-2 libgssrpc4 libk5crypto3
2016-05-19 15:18:30,933 INFO: - App:   libkadm5clnt-mit9 libkadm5srv-mit9 libkdb5-7 libkrb5-3 libkrb5support0
2016-05-19 15:18:30,953 INFO: - App:   libpq5 python-egenix-mxdatetime python-egenix-mxtools
2016-05-19 15:18:30,986 INFO: - App: Suggested packages:
2016-05-19 15:18:30,998 INFO: - App:   doc-base krb5-doc krb5-user postgresql-doc-9.4 python-egenix-mxdatetime-dbg
2016-05-19 15:18:31,066 INFO: - App:   python-egenix-mxdatetime-doc python-egenix-mxtools-dbg
2016-05-19 15:18:31,078 INFO: - App:   python-egenix-mxtools-doc python-psycopg2-doc
2016-05-19 15:18:31,098 INFO: - App: The following NEW packages will be installed:
2016-05-19 15:18:31,123 INFO: - App:   comerr-dev krb5-multidev libgssrpc4 libkadm5clnt-mit9 libkadm5srv-mit9
2016-05-19 15:18:31,137 INFO: - App:   libkdb5-7 libpq-dev libpq5 python-egenix-mxdatetime python-egenix-mxtools
2016-05-19 15:18:31,154 INFO: - App:   python-psycopg2
2016-05-19 15:18:31,174 INFO: - App: The following packages will be upgraded:
2016-05-19 15:18:31,208 INFO: - App:   libgssapi-krb5-2 libk5crypto3 libkrb5-3 libkrb5support0
2016-05-19 15:18:32,611 INFO: - App: 4 upgraded, 11 newly installed, 0 to remove and 48 not upgraded.
2016-05-19 15:18:32,625 INFO: - App: Need to get 1702 kB of archives.
2016-05-19 15:18:32,638 INFO: - App: After this operation, 4678 kB of additional disk space will be used.
2016-05-19 15:18:32,644 INFO: - App: Get:1 http://security.debian.org/ jessie/updates/main libpq5 amd64 9.4.6-0+deb8u1 [123 kB]
2016-05-19 15:18:32,670 INFO: - App: Get:2 http://httpredir.debian.org/debian/ jessie/main libgssapi-krb5-2 amd64 1.12.1+dfsg-19+deb8u2 [152 kB]
2016-05-19 15:18:32,710 INFO: - App: Get:3 http://httpredir.debian.org/debian/ jessie/main libkrb5-3 amd64 1.12.1+dfsg-19+deb8u2 [303 kB]
2016-05-19 15:18:32,747 INFO: - App: Get:4 http://security.debian.org/ jessie/updates/main libpq-dev amd64 9.4.6-0+deb8u1 [163 kB]
2016-05-19 15:18:32,923 INFO: - App: Get:5 http://httpredir.debian.org/debian/ jessie/main libgssrpc4 amd64 1.12.1+dfsg-19+deb8u2 [86.1 kB]
2016-05-19 15:18:32,965 INFO: - App: Get:6 http://httpredir.debian.org/debian/ jessie/main libkadm5clnt-mit9 amd64 1.12.1+dfsg-19+deb8u2 [68.5 kB]
2016-05-19 15:18:32,976 INFO: - App: Get:7 http://httpredir.debian.org/debian/ jessie/main libkrb5support0 amd64 1.12.1+dfsg-19+deb8u2 [59.1 kB]
2016-05-19 15:18:33,012 INFO: - App: Get:8 http://httpredir.debian.org/debian/ jessie/main libkdb5-7 amd64 1.12.1+dfsg-19+deb8u2 [68.5 kB]
2016-05-19 15:18:33,057 INFO: - App: Get:9 http://httpredir.debian.org/debian/ jessie/main libk5crypto3 amd64 1.12.1+dfsg-19+deb8u2 [115 kB]
2016-05-19 15:18:33,076 INFO: - App: Get:10 http://httpredir.debian.org/debian/ jessie/main libkadm5srv-mit9 amd64 1.12.1+dfsg-19+deb8u2 [83.0 kB]
2016-05-19 15:18:33,115 INFO: - App: Get:11 http://httpredir.debian.org/debian/ jessie/main comerr-dev amd64 2.1-1.42.12-1.1 [38.4 kB]
2016-05-19 15:18:33,184 INFO: - App: Get:12 http://httpredir.debian.org/debian/ jessie/main krb5-multidev amd64 1.12.1+dfsg-19+deb8u2 [145 kB]
2016-05-19 15:18:33,254 INFO: - App: Get:13 http://httpredir.debian.org/debian/ jessie/main python-egenix-mxtools amd64 3.2.8-1 [77.7 kB]
2016-05-19 15:18:33,354 INFO: - App: Get:14 http://httpredir.debian.org/debian/ jessie/main python-egenix-mxdatetime amd64 3.2.8-1 [71.3 kB]
2016-05-19 15:18:33,456 INFO: - App: Get:15 http://httpredir.debian.org/debian/ jessie/main python-psycopg2 amd64 2.5.4+dfsg-1 [149 kB]
2016-05-19 15:18:33,784 INFO: - App: debconf: delaying package configuration, since apt-utils is not installed
2016-05-19 15:18:33,803 INFO: - App: Fetched 1702 kB in 1s (1328 kB/s)
2016-05-19 15:18:33,998 INFO: - App: (Reading database ... 
(Reading database ... 5%
(Reading database ... 10%
(Reading database ... 15%
(Reading database ... 20%
(Reading database ... 25%
(Reading database ... 30%
(Reading database ... 35%
(Reading database ... 40%
(Reading database ... 45%
(Reading database ... 50%
(Reading database ... 55%
(Reading database ... 60%
(Reading database ... 65%
(Reading database ... 70%
(Reading database ... 75%
(Reading database ... 80%
(Reading database ... 85%
(Reading database ... 90%
(Reading database ... 95%
(Reading database ... 100%
(Reading database ... 26429 files and directories currently installed.)
2016-05-19 15:18:34,011 INFO: - App: Preparing to unpack .../libgssapi-krb5-2_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,018 INFO: - App: Unpacking libgssapi-krb5-2:amd64 (1.12.1+dfsg-19+deb8u2) over (1.12.1+dfsg-19+deb8u1) ...
2016-05-19 15:18:34,148 INFO: - App: Preparing to unpack .../libkrb5-3_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,182 INFO: - App: Unpacking libkrb5-3:amd64 (1.12.1+dfsg-19+deb8u2) over (1.12.1+dfsg-19+deb8u1) ...
2016-05-19 15:18:34,327 INFO: - App: Preparing to unpack .../libkrb5support0_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,346 INFO: - App: Unpacking libkrb5support0:amd64 (1.12.1+dfsg-19+deb8u2) over (1.12.1+dfsg-19+deb8u1) ...
2016-05-19 15:18:34,432 INFO: - App: Preparing to unpack .../libk5crypto3_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,466 INFO: - App: Unpacking libk5crypto3:amd64 (1.12.1+dfsg-19+deb8u2) over (1.12.1+dfsg-19+deb8u1) ...
2016-05-19 15:18:34,548 INFO: - App: Selecting previously unselected package libgssrpc4:amd64.
2016-05-19 15:18:34,555 INFO: - App: Preparing to unpack .../libgssrpc4_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,565 INFO: - App: Unpacking libgssrpc4:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:34,611 INFO: - App: Selecting previously unselected package libkadm5clnt-mit9:amd64.
2016-05-19 15:18:34,619 INFO: - App: Preparing to unpack .../libkadm5clnt-mit9_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,628 INFO: - App: Unpacking libkadm5clnt-mit9:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:34,694 INFO: - App: Selecting previously unselected package libkdb5-7:amd64.
2016-05-19 15:18:34,708 INFO: - App: Preparing to unpack .../libkdb5-7_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,739 INFO: - App: Unpacking libkdb5-7:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:34,788 INFO: - App: Selecting previously unselected package libkadm5srv-mit9:amd64.
2016-05-19 15:18:34,834 INFO: - App: Preparing to unpack .../libkadm5srv-mit9_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:34,862 INFO: - App: Unpacking libkadm5srv-mit9:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:34,952 INFO: - App: Selecting previously unselected package libpq5:amd64.
2016-05-19 15:18:34,968 INFO: - App: Preparing to unpack .../libpq5_9.4.6-0+deb8u1_amd64.deb ...
2016-05-19 15:18:35,030 INFO: - App: Unpacking libpq5:amd64 (9.4.6-0+deb8u1) ...
2016-05-19 15:18:35,138 INFO: - App: Selecting previously unselected package comerr-dev.
2016-05-19 15:18:35,174 INFO: - App: Preparing to unpack .../comerr-dev_2.1-1.42.12-1.1_amd64.deb ...
2016-05-19 15:18:35,206 INFO: - App: Unpacking comerr-dev (2.1-1.42.12-1.1) ...
2016-05-19 15:18:35,254 INFO: - App: Selecting previously unselected package krb5-multidev.
2016-05-19 15:18:35,291 INFO: - App: Preparing to unpack .../krb5-multidev_1.12.1+dfsg-19+deb8u2_amd64.deb ...
2016-05-19 15:18:35,318 INFO: - App: Unpacking krb5-multidev (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:35,382 INFO: - App: Selecting previously unselected package libpq-dev.
2016-05-19 15:18:35,406 INFO: - App: Preparing to unpack .../libpq-dev_9.4.6-0+deb8u1_amd64.deb ...
2016-05-19 15:18:35,444 INFO: - App: Unpacking libpq-dev (9.4.6-0+deb8u1) ...
2016-05-19 15:18:35,481 INFO: - App: Selecting previously unselected package python-egenix-mxtools.
2016-05-19 15:18:35,499 INFO: - App: Preparing to unpack .../python-egenix-mxtools_3.2.8-1_amd64.deb ...
2016-05-19 15:18:35,551 INFO: - App: Unpacking python-egenix-mxtools (3.2.8-1) ...
2016-05-19 15:18:35,572 INFO: - App: Selecting previously unselected package python-egenix-mxdatetime.
2016-05-19 15:18:35,581 INFO: - App: Preparing to unpack .../python-egenix-mxdatetime_3.2.8-1_amd64.deb ...
2016-05-19 15:18:35,618 INFO: - App: Unpacking python-egenix-mxdatetime (3.2.8-1) ...
2016-05-19 15:18:35,652 INFO: - App: Selecting previously unselected package python-psycopg2.
2016-05-19 15:18:35,695 INFO: - App: Preparing to unpack .../python-psycopg2_2.5.4+dfsg-1_amd64.deb ...
2016-05-19 15:18:35,709 INFO: - App: Unpacking python-psycopg2 (2.5.4+dfsg-1) ...
2016-05-19 15:18:35,859 INFO: - App: Setting up libkrb5support0:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:35,898 INFO: - App: Setting up libk5crypto3:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:35,927 INFO: - App: Setting up libkrb5-3:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:35,955 INFO: - App: Setting up libgssapi-krb5-2:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:35,967 INFO: - App: Setting up libgssrpc4:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:35,991 INFO: - App: Setting up libkadm5clnt-mit9:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:36,017 INFO: - App: Setting up libkdb5-7:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:36,046 INFO: - App: Setting up libkadm5srv-mit9:amd64 (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:36,061 INFO: - App: Setting up libpq5:amd64 (9.4.6-0+deb8u1) ...
2016-05-19 15:18:36,083 INFO: - App: Setting up comerr-dev (2.1-1.42.12-1.1) ...
2016-05-19 15:18:36,115 INFO: - App: Setting up krb5-multidev (1.12.1+dfsg-19+deb8u2) ...
2016-05-19 15:18:36,158 INFO: - App: Setting up libpq-dev (9.4.6-0+deb8u1) ...
2016-05-19 15:18:36,197 INFO: - App: Setting up python-egenix-mxtools (3.2.8-1) ...
2016-05-19 15:18:36,351 INFO: - App: Setting up python-egenix-mxdatetime (3.2.8-1) ...
2016-05-19 15:18:36,542 INFO: - App: Setting up python-psycopg2 (2.5.4+dfsg-1) ...
2016-05-19 15:18:36,796 INFO: - App: Processing triggers for libc-bin (2.19-18) ...
2016-05-19 15:18:40,325 INFO: - App:  ---> 09e74d98cd5a
2016-05-19 15:18:40,379 INFO: - App: Removing intermediate container d58ec1abe820
2016-05-19 15:18:40,385 INFO: - App: Step 6 : USER main
2016-05-19 15:18:40,523 INFO: - App:  ---> Running in 8173a8ddcb52
2016-05-19 15:18:40,695 INFO: - App:  ---> cabd74cfc2df
2016-05-19 15:18:40,709 INFO: - App: Removing intermediate container 8173a8ddcb52
2016-05-19 15:18:40,717 INFO: - App: Step 7 : RUN pip install psycopg2
2016-05-19 15:18:40,842 INFO: - App:  ---> Running in 4aec8338d4f7
2016-05-19 15:18:41,671 INFO: - App: Collecting psycopg2
2016-05-19 15:18:41,782 INFO: - App:   Downloading psycopg2-2.6.1.tar.gz (371kB)
2016-05-19 15:18:42,979 INFO: - App: Building wheels for collected packages: psycopg2
2016-05-19 15:18:42,990 INFO: - App:   Running setup.py bdist_wheel for psycopg2: started
2016-05-19 15:18:51,978 INFO: - App:   Running setup.py bdist_wheel for psycopg2: finished with status 'done'
2016-05-19 15:18:51,985 INFO: - App:   Stored in directory: /home/main/.cache/pip/wheels/21/21/80/89c21755b92a5874b6a8930d015bf1c4fc1b253f24e8d880cb
2016-05-19 15:18:52,018 INFO: - App: Successfully built psycopg2
2016-05-19 15:18:52,058 INFO: - App: Installing collected packages: psycopg2
2016-05-19 15:18:52,499 INFO: - App: Successfully installed psycopg2-2.6.1
2016-05-19 15:18:52,589 INFO: - App: You are using pip version 8.1.1, however version 8.1.2 is available.
2016-05-19 15:18:52,615 INFO: - App: You should consider upgrading via the 'pip install --upgrade pip' command.
2016-05-19 15:18:53,066 INFO: - App:  ---> 0e6c86a4d7d6
2016-05-19 15:18:53,084 INFO: - App: Removing intermediate container 4aec8338d4f7
2016-05-19 15:18:53,096 INFO: - App: Step 8 : ADD repo $HOME/notebooks
2016-05-19 15:18:53,378 INFO: - App:  ---> f818914840fa
2016-05-19 15:18:53,396 INFO: - App: Removing intermediate container acfed57772fe
2016-05-19 15:18:53,413 INFO: - App: Step 9 : USER root
2016-05-19 15:18:53,591 INFO: - App:  ---> Running in 80765c8e5a1b
2016-05-19 15:18:53,642 INFO: - App:  ---> 9ff57ef6d49b
2016-05-19 15:18:53,652 INFO: - App: Removing intermediate container 80765c8e5a1b
2016-05-19 15:18:53,665 INFO: - App: Step 10 : RUN chown -R main:main $HOME/notebooks
2016-05-19 15:18:53,779 INFO: - App:  ---> Running in a8619e659c97
2016-05-19 15:18:54,440 INFO: - App:  ---> 26efae2bfa78
2016-05-19 15:18:54,457 INFO: - App: Removing intermediate container a8619e659c97
2016-05-19 15:18:54,463 INFO: - App: Step 11 : USER main
2016-05-19 15:18:54,611 INFO: - App:  ---> Running in f9327e27150c
2016-05-19 15:18:54,686 INFO: - App:  ---> d5a0ecfaab31
2016-05-19 15:18:54,695 INFO: - App: Removing intermediate container f9327e27150c
2016-05-19 15:18:54,704 INFO: - App: Step 12 : RUN find $HOME/notebooks -name '*.ipynb' -exec ipython trust {} \;
2016-05-19 15:18:54,806 INFO: - App:  ---> Running in 42033b94d6fd
2016-05-19 15:18:55,976 INFO: - App: [TerminalIPythonApp] WARNING | Subcommand `ipython trust` is deprecated and will be removed in future versions.
2016-05-19 15:18:56,001 INFO: - App: [91m[TerminalIPythonApp] WARNING | You likely want to use `jupyter trust`... continue in 5 sec. Press Ctrl-C to quit now.
2016-05-19 15:19:01,191 INFO: - App: [91m[TrustNotebookApp] Writing notebook-signing key to /home/main/.local/share/jupyter/notebook_secret
2016-05-19 15:19:01,206 INFO: - App: Signing notebook: /home/main/notebooks/index.ipynb
2016-05-19 15:19:01,643 INFO: - App:  ---> 600f0af4fe3a
2016-05-19 15:19:01,666 INFO: - App: Removing intermediate container 42033b94d6fd
2016-05-19 15:19:01,688 INFO: - App: Step 13 : WORKDIR $HOME/notebooks
2016-05-19 15:19:01,771 INFO: - App:  ---> Running in 8f4a89a3e298
2016-05-19 15:19:01,876 INFO: - App:  ---> d9ec5a0c503c
2016-05-19 15:19:01,920 INFO: - App: Removing intermediate container 8f4a89a3e298
2016-05-19 15:19:01,945 INFO: - App: Successfully built d9ec5a0c503c
2016-05-19 15:19:01,957 INFO: - App: Squashing and pushing gcr.io/generic-notebooks/mgiacalone1980-machine-learning-assignment to private registry...
2016-05-19 15:19:27,733 INFO: - App: Preloading app image onto all nodes...
2016-05-19 15:20:53,780 INFO: - App: Successfully built app mgiacalone1980-machine-learning-assignment
