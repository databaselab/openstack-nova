..
      Licensed under the Apache License, Version 2.0 (the "License"); you may
      not use this file except in compliance with the License. You may obtain
      a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
      WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
      License for the specific language governing permissions and limitations
      under the License.

Development policies

Out Of Tree Support
===================

While nova has many entrypoints and other places in the code that allow for
wiring in out of tree code. Upstream doesn't actively make any guarantees
about these extensibility points; we don't support them, make any guarantees
about compatibility, stability, etc.