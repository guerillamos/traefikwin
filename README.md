# traefik on DockerforWindows
A dockerfile with a simple tweak for bringing up Traefik with automatic cert on DockerforWindows... Complete with a preloaded chmod 600 acme.json.

1. 1. Build the image yourself or pull it down from the dockerhub. (If you pull this image keep in mind that you may need to change the path to your cert file in your traefik.toml)

2. Attach a shell and double check the permissions. (I did the multiple times mainly because I couldn't believe it worked!)

3. Attach logs and watch as your server pulls certs down like unicorn wonder magic.

4. Profit

