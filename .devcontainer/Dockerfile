FROM node:lts

# Erstelle Arbeitsverzeichnis
WORKDIR /workspace

# Installiere zusätzliche Pakete (falls benötigt)
# RUN apt-get update && apt-get install -y <pakete>

# Setze Berechtigungen für den node-Benutzer
RUN chown -R node:node /workspace

# Wechsel zu Benutzer 'node'
USER node

# Exponiere Ports
EXPOSE 5173
