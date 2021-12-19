# About OMDB
[![Database](https://img.shields.io/badge/Database%20Sample-🐘%20postgres-316192.svg)](https://www.postgresql.org/)

_omdb_ ([open media database](https://www.omdb.org/)) is a free database for film media. There is no set editorial staff, but rather a large number of movie addicts and lovers who volunteer their time to provide material and develop the site. Anybody can add or change existing information on _omdb_ once they have done the quick and simple task of signing up for their user login name. Films will thus be represented with equal opportunities hence Blockbusters, Soap Operas, and a college thesis film will each have their own place on _omdb_.

_omdb_ is a non-commercial project. All the contents of the site are published under the Creative Commons License. The databank is therefore represents a contribution to free knowledge on the Internet. The information does not belong to a company or person but rather to the general public (more about the CC-License). _omdb_ consciously stays away from commercial related information with an objective to provide a self-contained film database.

👉 This repository contain a dump database file created on 19-Dic-2021, using script [credativ/omdb-postgresql](https://github.com/credativ/omdb-postgresql).

## Init
In this directory, run container:
```bash
docker-compose up -d
```

Connect to database using credentials:
<table>
    <tbody>
        <tr>
            <td>Host</td>
            <td>localhost</td>
        </tr>
        <tr>
            <td>Port</td>
            <td>5432</td>
        </tr>
        <tr>
            <td>User</td>
            <td>postgres</td>
        </tr>
        <tr>
            <td>Password</td>
            <td>postgres</td>
        </tr>
        <tr>
            <td>Database</td>
            <td>omdb</td>
        </tr>
    </tbody>
</table>

For stop container:
```bash
docker-compose down
```

## Licence
</a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/2.0/de/">Creative Commons Attribution 2.0 Germany License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by/2.0/de/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/2.0/de/88x31.png" />

[Copyright© omdb](https://www.omdb.org/content/Copyright)