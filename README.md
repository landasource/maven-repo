maven-repo
==========

maven repository for landasource projects

To deploy

mvn7 -DperformRelease=true -DaltDeploymentRepository=snapshot-repo::default::file:../maven-repo/snapshots clean deploy
