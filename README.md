<!---
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to You under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
--->


# Gremlin OSGI dependencies

This project's goal is to aggregate in one single bundle, the non OSGI dependencies required by the TinkerPop projects.
As a result, installing TinkerPop jar in an OSGI container just requires installing gremlin-osgi-deps first.

> It works only if the pull request https://github.com/apache/incubator-tinkerpop/pull/186 is accepted
> Waiting for it, you can checkout and compile https://github.com/gdelafosse/incubator-tinkerpop/tree/osgify.

As soon as the projects embedded in this bundle are valide OSGI bundles, this project is no more usefull.
