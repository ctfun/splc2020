# splc2020
SPLC2020 conference modeling contents - Submission 45

This repository contains the published domain case studies found in our submitted work to SPLC2020 (https://http://splc2020.net)
Using [Clafer](http://clafer.org), v0.4.3 (https://gsd.uwaterloo.ca/clafer-tools-binary-distributions.html), 
Developed within the [ISC2 Project] (https://www.irt-systemx.fr/en/projets/isc/).

The repository is structured as follows:
* root - final model (and branchings)
* xp1 - body related to modeling strategies to encoding the deployment problem in an heterogeneous context
* xp2 - body related to improving the resolution thanks to customized resolution strategy
* xp3 - body related to improving the resolution thanks to customized resolution strategy (domain constraints added)
* xp4 - body related to improving the constraints for resolution (redundancy constraints)

Some commands: 
.\clafer deplCasebA.cfr -m choco -m graph --validate --sr
java -jar .\chocosolver.jar --file deplCasebA.js --time --maxint 10000000

## Contributors

* [Stephen Creff] IRT SystemX
* [Jerome Le Noir] Thales Research and Technology
