### Flight Simulation Game
---

# DATABASE SETUP
---
This repo contains the files needed for inital MySQL database setup.  

Included in this repo are scripts which:  
- create the `flightsim` database
- create the `admin` user, with both localhost and remote access


# USE
---
Here is an example for running a script on the database ...

```bash
> cd ~/<deployment_directory>
> mysql -u root -p < create_db.sql

Enter the root password when prompted
```

