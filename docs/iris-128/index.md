# Iris-128

Open-source 128-channel headstages for neural stimulation and recording.

> *The publication of this work can be found at DOI 10.1088/1741-2552/ae1876. The raw data files corresponding to the publication can be found at https://doi.org/10.17605/OSF.IO/XS2PU.*

![Iris-128](images/iris-128-system.jpg)

| Type | Description |
| :--: | :---------- |
| [Iris-128B](iris-128b/index.md)  | Fully bidirectional headstage with recording or stimulation across all 128 electrode channels. |
| [Iris-128S](iris-128s/index.md) | Selective stimulation headstage with recording from 128 channels and stimulation on 16 simultaneous channels out of 32 available stimulation channels. |
| [Thin-film electrode](./thin-film/index.md) | 128 channel surface array used as a test platform for the headstages. |

## EDA Tools used in the Development

| EDA Tool     | Version | Usage           |
| :----------: | :-----: | :-------------- |
| KiCad        | 8.0.5   | Design of PCBs. |
| KiCad        | 9.0.3   | Design of PCBs. |
| STM32CubeIDE | 1.16.0  | Design of firmware for MCU. |

## Developers

<div class="grid cards" markdown>

- :fontawesome-solid-university: Deku Lab, University of Oregon, Eugene, OR
- :material-office-building: OpenIC, Eagan, MN

</div>



## License

Copyright 2025 Manuel Monge, Emma Jacobs

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
