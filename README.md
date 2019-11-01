# postgresql-replication

## PostgreSQL Streaming Replication With Docker and docker-compose

### Requirements :
Following dependencies needs to be installed on the machine
<ul style="list-style-type:circle">
  <li>1. Docker</li>
  <li>2. docker-compose</li>
  <li>3. PgAdmin</li>
</ul>

<b>Optional :</b><br><br>
You can create your own docker image. Use following command to create one. <br><br>
`docker image build -t postgresql-replication` <br><br>
After this, you need to modify the image name in docker-compose.yml file.

<b>Plan of execution</b><br><br>
<b>1. Run the docker images using docker-compose</b><br><br>
```docker-compose up```
<br><br>
<b>2. Use PgAdmin to log into the databases</b><br>
We need to add two servers into the PgAdmin one is for master server and another is for slave server.<br><br>
<b>2.1 Adding master server</b></br>
