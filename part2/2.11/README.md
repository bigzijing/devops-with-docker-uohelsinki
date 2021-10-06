At work we have an analytics team (coming from a company that provides data as one of our features)
We wanted to track and look at data metrics
So since our data is constantly changing, we use Docker on a remote machine to have more hands-free Postgres server to work on
As there might be several devs, we also make scripts such that we can spin up multiple containers for each person
Such that heavy querying or data mutation would not hinder with another's work
