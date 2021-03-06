# px-demo-data

## Overview

The `px-demo-data` repo contains the test data used by all the px data vis components.
This represents the data format expected by the data vis components.

## Usage

`Px-demo-data` is not a component, and is not used as such. The data contained in this repository is used by other components which bind the data using [iron-ajax](https://elements.polymer-project.org/elements/iron-ajax).

Example:

    <iron-ajax
        url="../demo-data/aviation/fan-vibration-cruise.json"
        handleas="json">
    </iron-ajax>

### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues](https://github.com/PredixDev/COMPONENT/issues) to submit any bugs you might find.
