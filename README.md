# Cheapest hours HA card
This Home Assistant card shows the day and time of the cheapest hours in a dynamic energy contract with a Nordpool integration. You can choose a block of 1 to 10 hours for which you get the cheapest hours start time (maximum 1 day in advance).

![alt Cheapest hours HA card](https://github.com/Swerfer/cheapest_hours_HA_card/blob/main/images/Cheapest%20hours.png?raw=true)

## Prerequisites

•	[Nordpool integration](https://github.com/custom-components/nordpool/)
•	[Cheapest energy hours jinja macro](https://github.com/TheFes/cheapest-energy-hours)

## How to install

•	Copy the YAML from input_number_helpers.yaml and past it in your input_number_helpers.yaml file.

•	Do a quick reload of the YAML configurations (Settings --> Restart Home Assistant --> Quick reload)

•	Go to the dashboard of your choice, add a new manual card and past the YAML from card.yaml in the YAML editor.

•	Save the card and you’re done.

## Buy me a coffee
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/Swerfer)
