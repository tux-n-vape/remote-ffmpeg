# Remote FFmpeg

Script using SSH-SFTP to use FFmepg remotly.

## Dependencies
* python3
* paramiko

## Usage
This is used exactly like ffmpeg but you must edit the configuration file "remote-ffmpeg.json" before first usage.

## Configuration

**Refer to the "connect" function parameters of paramiko to complete the "connection" section :**

http://docs.paramiko.org/en/2.4/api/client.html#paramiko.client.SSHClient.connect