NetSquid-SimulationTools (2.0.0)
================================

Description
-----------

This is a user contributed _snippet_ for the [NetSquid quantum network simulator](https://netsquid.org).

Tools for storing and processing quantum-repeater-chain simulation results.

Installation
------------

See the [INSTALL file](INSTALL.md) for instruction of how to install this snippet.

Documentation
-------------

So build and see the docs see the [docs README](docs/README.md).

Usage
-----

Quantum-repeater-chain results can be stored in a `RepchainDataFrameHolder`, see `repchain_dataframe_holder.py`.
To process results stored in a `RepchainDataFrameHolder` (e.g. calculate secret-key rate as a function of some varied parameter), use `repchain_data_process.py`.
Finally, the processed results can be visualized using `repchain_data_plot.py`.
While there is other functionality included in this snippet, these three python files provide the core functionality of netsquid-simulationtools.

Contact
-------

For questions, contact the maintainer of this snippet: Guus Avis (g.avis@tudelft.nl).

Contributors
------------

- Guus Avis (g.avis@tudelft.nl)
- David Maier
- Hana Jirovska
- Julian Rabbie
- Tim Coopmans
- Axel Dahlberg

License
-------

The NetSquid-SnippetTemplate has the following license:

> Copyright 2018 QuTech (TUDelft and TNO)
> 
>   Licensed under the Apache License, Version 2.0 (the "License");
>   you may not use this file except in compliance with the License.
>   You may obtain a copy of the License at
> 
>     http://www.apache.org/licenses/LICENSE-2.0
> 
>   Unless required by applicable law or agreed to in writing, software
>   distributed under the License is distributed on an "AS IS" BASIS,
>   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
>   See the License for the specific language governing permissions and
>   limitations under the License.
