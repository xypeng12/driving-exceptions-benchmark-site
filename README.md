# Driving Exceptions Benchmark — website

Project website: https://xypeng12.github.io/driving-exceptions-benchmark-site/

This repository contains only the static website, displayed scene recordings, and downloadable benchmark configuration definitions. The benchmark implementation is maintained separately in the private `xypeng12/driving-exceptions-benchmark` repository. Research agents, planners, model services and the full research implementation are not included.

GitHub Pages publishes the root of the `main` branch. All asset paths are relative so the site works under its project URL.

To preview locally: `python3 -m http.server 8765`.

To update the website, edit the HTML/CSS/JavaScript or replace its referenced assets, commit, and push to `main`. Website publication does not grant access to the private benchmark repository.
