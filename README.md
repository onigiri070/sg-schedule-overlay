# Speed Gaming Schedule Overlay

A Twitch video overlay which displays:  
- What’s on the other channels right now
- What’s coming up next on all of the channels

## Want to Contribute?

Right now development of this project is limited to SG Staff and SG Volunteers who possess the **Volunteer - Software** role in the SG Staff/Volunteer Discord server. If you meet the above criteria and are interested helping, please drop by the dev channel and let us know! We're always happy to have more help!

Once you've made contact, please be sure you have read and understand the [Contribution Guidelines](https://github.com/onigiri070/sg-schedule-overlay/wiki/contributionGuidelines) wiki page for this project. Any submitted work not adhering to the guidelines, will politely be asked to update to these standards.

The heart behind having these standards is not to be difficult or create an "exclusive" ring of devs; it's to have a codebase that is consistent, clear, readable and of such quality that *anybody* can help maintain it while preserving style and design continuity as much as possible. If you're unsure if something doesn't meet a standard or are simply unclear about something, just ask! We're a friendly group and are more than happy to help people learn!






---

# Twitch Extensions Boilerplate

The Twitch Extensions Boilerplate acts as a simple starting point to create your Extension, as well as a simple method using Docker to locally serve your Extension for testing and development.

## Dependencies

You will need:
 * [docker](https://docs.docker.com/engine/installation/)
 * [docker-compose](https://docs.docker.com/compose/install/)

## Generate self-signed certs
```bash
cd certs
./generate_local_ssl.sh
    # Requires a sudo password so that the cert can be installed on the root keychain
    # If this install fails, see the README in ./certs for manual override.
```

## To start the Extensions Boilerplate service
```bash
docker-compose up --build
```

## Further documentation

Please consult the [Twitch Extensions documentation on the Twitch developer site](https://dev.twitch.tv/docs/extensions)
