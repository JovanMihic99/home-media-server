# Home Media Streaming Server Docker configuration
Personal docker configuration for automating downloading and seeding of movie and tv torrents, as well as streaming of said media. 
## Containers Used
- Jellyfin (A media server that allows you to stream your movies and TV shows across devices)
- Sonarr (A PVR (Personal Video Recorder) for TV shows, automating downloading, organizing, and renaming episodes)
- Radarr (A similar tool to Sonarr but focused on automating movie downloads and management)
- Prowlarr (An indexer manager that integrates with Sonarr and Radarr to fetch torrents from multiple sources)
- QBitTorrent (A lightweight and feature-rich torrent client for handling downloads and seeding)
- Nginx (A web server used as a reverse proxy to manage access and improve performance & security)
