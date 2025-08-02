# github-reuse-actions
history
=======
1  27/05/25 08:30:59 cd /opt
2  27/05/25 08:31:08 df -h
3  27/05/25 08:31:54 curl -L -o sonar.zip curl -L -o sonarqube.zip https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-7.6.zip
4  27/05/25 08:32:03 ls
5  27/05/25 08:32:08 unzip sonarqube.zip
6  27/05/25 08:32:12 ls
7  27/05/25 08:32:25 ls -l
8  27/05/25 08:32:40 useradd sonar
9  27/05/25 08:32:42 ls
10  27/05/25 08:32:47 cd /home
11  27/05/25 08:32:48 ls
12  27/05/25 08:32:51 cd sonar
13  27/05/25 08:33:03 unzip /root/sonar.zip
14  27/05/25 08:33:25 mv /root/sonar /home/sonar
15  27/05/25 08:33:42 cd /opt
16  27/05/25 08:33:43 ls
17  27/05/25 08:34:04 mv /opt/sonarqube-7.6 /home/sonar
18  27/05/25 08:34:08 ls
19  27/05/25 08:34:13 cd /home/sonar
20  27/05/25 08:34:14 ls
21  27/05/25 08:34:18 ls -l
22  27/05/25 08:34:36 chown -R sonar:sonar /home/sonar
23  27/05/25 08:34:38 ls
24  27/05/25 08:34:40 ls -l
25  27/05/25 08:34:57 cd sonarqube-7.6
26  27/05/25 08:34:59 ls
27  27/05/25 08:35:05 cd conf
28  27/05/25 08:35:05 ls
29  27/05/25 08:35:10 cat sonar.properties
30  27/05/25 08:35:22 cd ..
31  27/05/25 08:35:23 ls
32  27/05/25 08:35:25 cd bin
33  27/05/25 08:35:26 ls
34  27/05/25 08:35:32 cd linux-x86-64
35  27/05/25 08:35:33 ls
36  27/05/25 08:35:41 ./sonar.sh start
37  27/05/25 08:35:52 ./sonar.sh
38  27/05/25 08:36:09 ls -l
39  27/05/25 08:36:15 sudo su - sonar
40  27/05/25 08:42:09 cd ../..
41  27/05/25 08:42:12 cd
42  27/05/25 08:42:21 dnf list | grep java
43  27/05/25 08:43:44 dnf install java-17-openjdk.x86_64 -y
44  27/05/25 08:44:25 sudo su - sonar
45  27/05/25 08:52:23 cd /opt
46  27/05/25 08:52:24 ls
47  27/05/25 08:52:29 history
48  27/05/25 08:52:46 ls
49  27/05/25 08:52:52 unzip sonar.zip
50  27/05/25 08:53:02 unzip sonarqube.zip
51  27/05/25 08:53:06 ls
52  27/05/25 08:53:15 sudo su - sonar
53  27/05/25 08:54:14 java -version
54  27/05/25 08:54:45 sudo su - sonar
55  27/05/25 09:02:35 ls -l
56  27/05/25 09:02:38 rm -rf *
57  27/05/25 09:02:39 ls
58  27/05/25 09:03:15 curl -L -o sonar.zip https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-25.5.0.107428.zip
59  27/05/25 09:03:19 ls
60  27/05/25 09:03:21 ls -l
61  27/05/25 09:03:44 mv /opt/sonar.zip /home/sonar
62  27/05/25 09:04:16 unzip sonar.zip
63  27/05/25 09:04:25 ls
64  27/05/25 09:04:44 mv /opt/sonarqube-25.5.0.107428 /home/sonar
65  27/05/25 09:05:41 df -h
66  27/05/25 09:05:52 growpart /dev/nvme0n1 4
67  27/05/25 09:06:18 lvextend -r -L +5G /dev/mapper/RootVG-homeVol
68  27/05/25 09:06:21 df -h
69  27/05/25 09:06:29 mv /opt/sonarqube-25.5.0.107428 /home/sonar
70  27/05/25 09:06:36 sudo su - sonar
71  27/05/25 09:07:36 ls
72  27/05/25 09:07:49 unzip sonar.zip
73  27/05/25 09:08:08 ls
74  27/05/25 09:08:17 chown -R sonar:sonar sonarqube-25.5.0.107428
75  27/05/25 09:08:22 ls -l
76  27/05/25 09:08:39 sudo su - sonar
77  27/05/25 09:10:15 ls
78  27/05/25 09:10:31 mv /opt/sonarqube-25.5.0.107428 /home/sonar
79  27/05/25 09:10:49 ls
80  27/05/25 09:10:51 ls -l
81  27/05/25 09:10:59 mv /opt/sonarqube-25.5.0.107428 /home/sonar
82  27/05/25 08:30:59 cd /opt
83  27/05/25 08:31:08 df -h
84  27/05/25 08:31:54 curl -L -o sonar.zip curl -L -o sonarqube.zip https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-7.6.zip
85  27/05/25 08:32:03 ls
86  27/05/25 08:32:08 unzip sonarqube.zip
87  27/05/25 08:32:12 ls
88  27/05/25 08:32:25 ls -l
89  27/05/25 08:32:40 useradd sonar
90  27/05/25 08:32:42 ls
91  27/05/25 08:32:47 cd /home
92  27/05/25 08:32:48 ls
93  27/05/25 08:32:51 cd sonar
94  27/05/25 08:33:03 unzip /root/sonar.zip
95  27/05/25 08:33:25 mv /root/sonar /home/sonar
96  27/05/25 08:33:42 cd /opt
97  27/05/25 08:33:43 ls
98  27/05/25 08:34:04 mv /opt/sonarqube-7.6 /home/sonar
99  27/05/25 08:34:08 ls
100  27/05/25 08:34:13 cd /home/sonar
101  27/05/25 08:34:14 ls
102  27/05/25 08:34:18 ls -l
103  27/05/25 08:34:36 chown -R sonar:sonar /home/sonar
104  27/05/25 08:34:38 ls
105  27/05/25 08:34:40 ls -l
106  27/05/25 08:34:57 cd sonarqube-7.6
107  27/05/25 08:34:59 ls
108  27/05/25 08:35:05 cd conf
109  27/05/25 08:35:05 ls
110  27/05/25 08:35:10 cat sonar.properties
111  27/05/25 08:35:22 cd ..
112  27/05/25 08:35:23 ls
113  27/05/25 08:35:25 cd bin
114  27/05/25 08:35:26 ls
115  27/05/25 08:35:32 cd linux-x86-64
116  27/05/25 08:35:33 ls
117  27/05/25 08:35:41 ./sonar.sh start
118  27/05/25 08:35:52 ./sonar.sh
119  27/05/25 08:36:09 ls -l
120  27/05/25 08:36:15 sudo su - sonar
121  27/05/25 08:42:09 cd ../..
122  27/05/25 08:42:12 cd
123  27/05/25 08:42:21 dnf list | grep java
124  27/05/25 08:43:44 dnf install java-17-openjdk.x86_64 -y
125  27/05/25 08:44:25 sudo su - sonar
126  27/05/25 08:52:23 cd /opt
127  27/05/25 08:52:24 ls
128  27/05/25 08:52:29 history
129  27/05/25 08:52:46 ls
130  27/05/25 08:52:52 unzip sonar.zip
131  27/05/25 08:53:02 unzip sonarqube.zip
132  27/05/25 08:53:06 ls
133  27/05/25 08:53:15 sudo su - sonar
134  27/05/25 08:54:14 java -version
135  27/05/25 08:54:45 sudo su - sonar
136  27/05/25 09:02:35 ls -l
137  27/05/25 09:02:38 rm -rf *
138  27/05/25 09:02:39 ls
139  27/05/25 09:03:15 curl -L -o sonar.zip https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-25.5.0.107428.zip
140  27/05/25 09:03:19 ls
141  27/05/25 09:03:21 ls -l
142  27/05/25 09:03:44 mv /opt/sonar.zip /home/sonar
143  27/05/25 09:04:16 unzip sonar.zip
144  27/05/25 09:04:25 ls
145  27/05/25 09:04:44 mv /opt/sonarqube-25.5.0.107428 /home/sonar
146  27/05/25 09:05:41 df -h
147  27/05/25 09:05:52 growpart /dev/nvme0n1 4
148  27/05/25 09:06:18 lvextend -r -L +5G /dev/mapper/RootVG-homeVol
149  27/05/25 09:06:21 df -h
150  27/05/25 09:06:29 mv /opt/sonarqube-25.5.0.107428 /home/sonar
151  27/05/25 09:06:36 sudo su - sonar
152  27/05/25 09:07:36 ls
153  27/05/25 09:07:49 unzip sonar.zip
154  27/05/25 09:08:08 ls
155  27/05/25 09:08:17 chown -R sonar:sonar sonarqube-25.5.0.107428
156  27/05/25 09:08:22 ls -l
157  27/05/25 09:08:39 sudo su - sonar
158  27/05/25 09:10:15 ls
159  27/05/25 09:10:31 mv /opt/sonarqube-25.5.0.107428 /home/sonar
160  27/05/25 09:10:49 ls
161  27/05/25 09:10:51 ls -l
162  27/05/25 09:10:59 mv /opt/sonarqube-25.5.0.107428 /home/sonar
163  27/05/25 09:13:37 cd /opt
164  27/05/25 09:13:38 ls
165  27/05/25 09:13:53 mv /opt/sonarqube-25.5.0.107428 /home/sonar
166  27/05/25 09:14:06 sudo su - sonar
167  27/05/25 09:16:58 cd /home
168  27/05/25 09:17:00 ls
169  27/05/25 09:17:07 rm -rf sonar
170  27/05/25 09:17:09 ls -;
171  27/05/25 09:17:11 ls -l
172  27/05/25 09:17:17 useradd sonar
173  27/05/25 09:17:25 useradd sonar1
174  27/05/25 09:17:35 cd /opt
175  27/05/25 09:17:37 ls
176  27/05/25 09:17:45 ls -l
177  27/05/25 09:18:01 mv /opt/sonarqube-25.5.0.107428 /home/sonar1
178  27/05/25 09:18:16 sudo su - sonar
179  27/05/25 09:18:32 sudo su - sonar1
180  27/05/25 09:23:33 sudo chmod 777 /path/to/SonarQube.pid /path/to/nohup.log
181  27/05/25 09:24:17 ls -l
182  27/05/25 09:24:21 sudo su - sonar
183  27/05/25 09:25:09 sudo su - sonar1
184  27/05/25 09:27:41 rm -rf *
185  27/05/25 09:27:54 curl -L -o sonar.zip  https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-10.5.1.90531.zip
186  27/05/25 09:27:58 ls -l
187  27/05/25 09:28:09 unzip sonar.zip
188  27/05/25 09:28:17 ls -l
189  27/05/25 09:28:38 chown -R sonar1:sonar1 /opt/sonarqube-10.5.1.90531
190  27/05/25 09:28:40 ls -l
191  27/05/25 09:28:55 mv  /opt/sonarqube-10.5.1.90531 /home/sonar1
192  27/05/25 09:28:59 ls -l
193  27/05/25 09:29:04 sudo su - sonar1
194  27/05/25 09:33:17 curl -L -o sonar-scanner.zip https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-7.1.0.4889-linux-x64.zip?_gl=1*w374vd*_gcl_au*MTQ0NzA4ODc2MS4xNzQ4MzMyNDU3*_ga*MTAyOTA5MTgwLjE3MTc1OTUzMzA.*_ga_9JZ0GZ5TC6*czE3NDgzMzI0NTYkbzgkZzEkdDE3NDgzMzM3MzckajUzJGwwJGgwJGQzc1Z5UjRsN2tuNjEtNkRVdlEyYS1ZR0xVQ000aW9VUEZR
195  27/05/25 09:33:19 ls -l
196  27/05/25 09:33:27 unzip sonar-scanner.zip
197  27/05/25 09:33:30 ls -l
198  27/05/25 09:33:39 cd sonar-scanner-7.1.0.4889-linux-x64
199  27/05/25 09:33:41 ls -l
200  27/05/25 09:33:44 cd conf
201  27/05/25 09:33:46 ls -l
202  27/05/25 09:33:52 cat sonar-scanner.properties
203  27/05/25 09:33:55 cd ..
204  27/05/25 09:33:57 ls -l
205  27/05/25 09:33:59 cd bin
206  27/05/25 09:34:00 ls -l
207  27/05/25 09:34:10 ./sonar-scanner start
208  27/05/25 09:35:27 cd
209  27/05/25 09:35:48 git clone https://github.com/pdevops78/expense-backend
210  27/05/25 09:35:50 ls
211  27/05/25 09:35:56 cd expense-backend
212  27/05/25 09:35:58 ls
213  27/05/25 09:36:50 curl -L -o sonar-scanner.zip https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-7.1.0.4889-linux-x64.zip?_gl=1*w374vd*_gcl_au*MTQ0NzA4ODc2MS4xNzQ4MzMyNDU3*_ga*MTAyOTA5MTgwLjE3MTc1OTUzMzA.*_ga_9JZ0GZ5TC6*czE3NDgzMzI0NTYkbzgkZzEkdDE3NDgzMzM3MzckajUzJGwwJGgwJGQzc1Z5UjRsN2tuNjEtNkRVdlEyYS1ZR0xVQ000aW9VUEZR
214  27/05/25 09:36:52 ls -l
215  27/05/25 09:39:19 rm -rf *.zip
216  27/05/25 09:39:20 ls -l
217  27/05/25 09:39:27 cd /opt
218  27/05/25 09:39:29 ls -l
219  27/05/25 09:39:39 cd expense-backend
220  27/05/25 09:39:41 cd
221  27/05/25 09:39:45 cd expense-backend
222  27/05/25 09:40:08 /opt /sonar-scanner-7.1.0.4889-linux-x64/bin/cd /opt
223  27/05/25 09:40:11 cd /opt
224  27/05/25 09:40:12 ls -l
225  27/05/25 09:40:16 cd sonar-scanner-7.1.0.4889-linux-x64
226  27/05/25 09:40:17 ls -l
227  27/05/25 09:40:20 cd bin
228  27/05/25 09:40:21 ls -l
229  27/05/25 09:40:25 cd
230  27/05/25 09:40:30 cd expense-backend
231  27/05/25 09:42:04 /opt/sonar-scanner-7.1.0.4889-linux-x64/bin/sonar-scanner -Dsonar.host.url=http://172.31.89.19:9000
232  27/05/25 09:42:28 /opt/sonar-scanner-7.1.0.4889-linux-x64/bin/sonar-scanner -Dsonar.host.url=http://172.31.89.19:9000 -Dsonar.login=admin123 -Dsonar.password=admin123
233  27/05/25 09:43:28 /opt/sonar-scanner-7.1.0.4889-linux-x64/bin/sonar-scanner -Dsonar.host.url=http://172.31.89.19:9000 -Dsonar.login=admin -Dsonar.password=admin123
234  27/05/25 09:44:08 /opt/sonar-scanner-7.1.0.4889-linux-x64/bin/sonar-scanner -Dsonar.host.url=http://172.31.89.19:9000 -Dsonar.login=admin -Dsonar.password=admin123 -Dsonar.projectKey=expense-backend
235  27/05/25 09:45:28 history



open ssl issue:
==============
Check where is ssh

\#which ssh

/usr/local/bin/ssh
Remove the current ssh package.

sudo dnf remove openssh-server openssh-client
Remove ssh file under /usr/local/bin/ssh

Reinstall ssh package as follows.
sudo yum update
sudo dnf install openssh-server openssh-client
Log out the current session and re-login again. SSH command is back to work and is under /usr/bin/ssh.

\#which ssh

/usr/bin/ssh


how do we get secrets from github actions?
- run: echo OK
  name: Release Software
  if: ${{ startswith (github.ref == 'refs/tags/*') }}

test.yml:
---------
jobs:
 job1:
- run: env
  name: 

------------
* first zip all the files 
* redirect github ref into version
* then upload zip file to artifactory
* steps:
  - uses: vimtor/action-zip@v1.2
  with:
  files: ${{ inputs.release_files }}
  dest: result.zip



update hashicorp vault secrets through github actions:
========================================================
1. first to read vaiult credentials
   curl -s -k --request GET --header "X-Vault-Token:hvs.T8WnPWmYmGZkPYlGAHXVmebk" \
   https://vault-internal.pdevops78.online:8200/v1/common/data/expense-frontend | jq .data.data | sed -i '/app_version/ c\  "app_version": 1.0.1' filename.json


curl --request GET --header "X-Vault-Token: hvs.T8WnPWmYmGZkPYlGAHXVmebk" \
https://vault-internal.pdevops78.online:8200/v1/secret/data/expense-frontend | jq

here -k is used to bypass ssl certificate


2. add environment variables in gocd pipeline
environment_variables:
App_VERSION: ""

3. trigger a pipeline through gocd:
===================================
curl 'https://ci.example.com/go/api/pipelines/pipeline1/schedule' \
-u 'username:password' \
-H 'Accept: application/vnd.go.cd.v1+json' \
-H 'Content-Type: application/json' \
-X POST \
-d '{
"environment_variables": [
{
"name": "APP_VERSION",
"secure": false,
"value": "1.0.0"
}
],
"update_materials_before_scheduling": true
}' | sed -e "s/app_version/${GITHUB_REF_NAME}/" | jq > /tmp/1 (or data.json same line)


4. how do we know which version we are triggering the pipeline
===============================================================
label_template: "${env:APP_VERSION}"



Trigger a pipeline:
===================
Trigger a pipeline remotely (from a script) and pass custom environment variables like APP_VERSION, DEPLOY_ENV
1. Create JSON Payload with Environment Variables
   {
   "environment_variables": {
   "APP_VERSION": "1.0.1",
   "DEPLOY_ENV": "staging"
   }
   }
2. Trigger the Pipeline Using curl
      curl -X POST "https://your-gocd-server.com/go/api/pipelines/<pipeline-name>/schedule"  -H "Accept: application/vnd.go.cd.v1+json" -H "Content-Type: application/json" -d @data.json

http://52.201.245.87:8153/go/pipeline/activity/artifactory

Load Test:
----------

to monitor Load test data:
--------------------------
1. install prometheus
2. install grafana
3. cd /etc/grafana/provisioning/datasources
4. cat sample.yaml