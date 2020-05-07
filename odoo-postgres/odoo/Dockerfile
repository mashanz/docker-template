# docker build . -t odoo_and_lib:13
FROM odoo:13

# run as root
USER root

# If you have to install from pip and using Odoo >= 11.0
RUN python3 -m pip install wheel
RUN python3 -m pip install pipedrive-python-lib

# If you need to install something with apt, if not working try to add apt-get update
RUN apt-get update
RUN apt-get install wkhtmltopdf -y
