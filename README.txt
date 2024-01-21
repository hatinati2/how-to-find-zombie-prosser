ps axo stat,ppid,pid,comm | grep -w defunct
sudo kill -9 process_id
