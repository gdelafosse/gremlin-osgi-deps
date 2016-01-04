# Gremlin OSGI dependencies

This project's goal is to aggregate in one single bundle, the non OSGI dependencies required by the TinkerPop projects.
As a result, installing TinkerPop jar in an OSGI container just requires installing gremlin-osgi-deps first.

> It works only if the pull request https://github.com/apache/incubator-tinkerpop/pull/186 is accepted
> Waiting for it, you can checkout and compile https://github.com/gdelafosse/incubator-tinkerpop/tree/osgify.

As soon as the projects embedded in this bundle are valide OSGI bundles, this project is no more usefull.
