# Welcome to the SNAP Kernel

The SNAP Kernel is a modified version of Apache Karaf.

In order to deploy the SNAP Core bundles, the Kernel requires Internet access to access the SNAP repositories.

## To deploy the SNAP Core bundles:

1. Start the Kernel: 'snap-0.0.2$ bin/snap'
2. Install the snap-core feature: 'karaf@root> features:install snap-core'
3. Create the broker instance: 'karaf@root> activemq:create-broker --type blueprint'
4. Verify that all of the bundles are "Active": 'karaf@root> list'

Apache Karaf is licensed with the Apache 2.0 license:

/*
 * Licensed to the Apache Software Foundation (ASF) under one or more
 * contributor license agreements.  See the NOTICE file distributed with
 * this work for additional information regarding copyright ownership.
 * The ASF licenses this file to You under the Apache License, Version 2.0
 * (the "License"); you may not use this file except in compliance with
 * the License.  You may obtain a copy of the License at
 *
 *      http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */