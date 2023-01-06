# docker-pylint-airflow
Docker to run static code analysis on Airflow DAGs source code.

## How to use it?
```
docker run python-pylint pylint --load-plugins=pylint_airflow <python_file_to_be_analyzed>

# Example (using as example file embedded python lib file: smtplib.py ) : 
docker run python-pylint pylint --load-plugins=pylint_airflow /usr/local/lib/python3.12/smtplib.py
```

## DockerHub repository
https://hub.docker.com/r/vmasilva/pylint-airflow

## Versions published ready to be pulled

| Versions Included                   | Docker tag                         |
|                                   - |                                  - |
| Python 3.12 + Pylint v2.15.9        | python-v3.12_pylint-v2.15          |
