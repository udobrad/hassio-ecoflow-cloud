## DELTA_MAX

*Sensors*
- Main Battery Level (`pd.soc`)
- Battery Level (`ems.lcdShowSoc`)
- Total In Power (`pd.wattsInSum`)
- Total Out Power (`pd.wattsOutSum`)
- AC In Power (`inv.inputWatts`)
- Solar In Power (`mppt.inWatts`)
- AC Out Power (`inv.outputWatts`)
- DC Out Power (`mppt.outWatts`)
- Type-C (1) Out Power (`pd.typec1Watts`)
- Type-C (2) Out Power (`pd.typec2Watts`)
- USB (1) Out Power (`pd.usb1Watts`)
- USB (2) Out Power (`pd.usb2Watts`)
- USB QC (1) Out Power (`pd.qcUsb1Watts`)
- USB QC (2) Out Power (`pd.qcUsb2Watts`)
- Charge Remaining Time (`ems.chgRemainTime`)
- Discharge Remaining Time (`ems.dsgRemainTime`)
- Inv Out Temperature (`inv.outTemp`)
- Cycles (`bmsMaster.cycles`)
- Battery Temperature (`bmsMaster.temp`)
- Min Cell Temperature (`bmsMaster.minCellTemp`)   _disabled_
- Max Cell Temperature (`bmsMaster.maxCellTemp`)   _disabled_
- Battery Volts (`bmsMaster.vol`)   _disabled_
- Min Cell Volts (`bmsMaster.minCellVol`)   _disabled_
- Max Cell Volts (`bmsMaster.maxCellVol`)   _disabled_

*Switches*
- Beeper (`pd.beepState` -> `{"moduleType": 5, "operateType": "quietMode", "params": {"enabled": "VALUE"}}`)
- USB Enabled (`pd.dcOutState` -> `{"moduleType": 0, "operateType": "TCP", "params": {"enabled": "VALUE", "id": 34}}`)
- AC Always On (`pd.acAutoOnCfg` -> `{"moduleType": 1, "operateType": "acAutoOn", "params": {"cfg": "VALUE"}}`)
- Prio Solar Charging (`pd.pvChgPrioSet` -> `{"moduleType": 1, "operateType": "pvChangePrio", "params": {"pvChangeSet": "VALUE"}}`)
- AC Enabled (`inv.cfgAcEnabled` -> `{"moduleType": 0, "operateType": "TCP", "params": {"enabled": "VALUE", "id": 66}}`)
- X-Boost Enabled (`inv.cfgAcXboost` -> `{"moduleType": 5, "operateType": "TCP", "params": {"id": 66, "xboost": "VALUE"}}`)
- DC (12V) Enabled (`mppt.carState` -> `{"moduleType": 0, "operateType": "TCP", "params": {"enabled": "VALUE", "id": 81}}`)

*Sliders (numbers)*
- Max Charge Level (`ems.maxChargeSoc` -> `{"moduleType": 2, "operateType": "upsConfig", "params": {"maxChgSoc": "VALUE"}}` [50 - 100])
- Min Discharge Level (`ems.minDsgSoc` -> `{"moduleType": 2, "operateType": "dsgCfg", "params": {"minDsgSoc": "VALUE"}}` [0 - 30])
- Generator Auto Start Level (`ems.minOpenOilEbSoc` -> `{"moduleType": 2, "operateType": "closeOilSoc", "params": {"closeOilSoc": "VALUE"}}` [0 - 30])
- Generator Auto Stop Level (`ems.maxCloseOilEbSoc` -> `{"moduleType": 2, "operateType": "openOilSoc", "params": {"openOilSoc": "VALUE"}}` [50 - 100])
- AC Charging Power (`inv.cfgFastChgWatt` -> `{"moduleType": 5, "operateType": "acChgCfg", "params": {"chgWatts": "VALUE", "chgPauseFlag": 255}}` [400 - 2200])

*Selects*


