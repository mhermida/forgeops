FROM gcr.io/forgerock-io/ig/pit1:7.0.0-f838a92b816aeab942b028ebd44a4d465bd8b6a2

# Copy all config files into the docker image.
# The default ig directory is /var/ig, and it expects subfolders config/ and scripts/ (if required)
COPY --chown=forgerock . /var/ig
