# Instructions

## Setup

- Setup: `sh setup.sh`
- Execute container: `sh run_service.sh`

## Using container

- Acessing container: `docker exec -ti test-postgres bash`
- Running pgadminp: `sh run_pgadmin.sh`
- Logging pgadmin:  `http://localhost:15432`
- Acessing remotely: `psql -h 127.0.0.1 -U postgres -W`
