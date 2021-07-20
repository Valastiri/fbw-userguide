---
hide:
    - navigation
    - toc
---

# Flight Deck Overview

- Clickable overview of the A320neo flight deck.
- Move the mouse over the panels to get the name of the panel.
- Click on the panels to get a more detailed description of that panel.

<style>
.imagemap {
    position: relative;
    display: inline-block;
    /*background-color: rgba(255, 0, 0, .4);*/
    /*border: 1px solid yellow;*/
}
.imagemap .imagemapname {
  visibility: hidden;

  background-color: rgba(29, 30, 38,.8);
  color: rgba(212, 212, 213, 1);
  text-align: center;
  padding: 5px 0;
  border-radius: 6px;

  /* Position the tooltip text - see examples below! */
  position: absolute;
  z-index: 1;
  width: 120px;
  top: 0%;
  left: 50%;
  margin-left: -60px; /* Use half of the width (120/2 = 60), to center the tooltip */
}
.imagemap:hover .imagemapname {
    visibility: visible;
}
.imagemap:hover {
    background-color: rgba(10, 144, 153, 0.30);
    border: 1px solid black;
}
</style>

<div style="position: relative;">
    <img src="/assets/a32nx-briefing/Cockpit-Overview-Map.png" style="width: 100%; height: auto;">
    <!-- OVHD AFT -->
    <a href="/a32nx-briefing/ovhd-aft/elt/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 2.55%; width: 12.5%; height: 1.7%;"><span class="imagemapname">ELT Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd-aft/cockpit-door/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 4.25%; width: 12.5%; height: 2.1%;"><span class="imagemapname">Cockpit Door Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd-aft/reading-light/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 9.9%; width: 12.5%; height: 3.3%;"><span class="imagemapname">Jump Seat Right Light</span></div></a>
    <a href="/a32nx-briefing/ovhd-aft/circuit/"><div class="imagemap" style="position: absolute; left: 35%; top: 0%; width: 30.3%; height: 18%;"><span class="imagemapname">Circuit Breaker Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd-aft/pedestal-light/"><div class="imagemap" style="position: absolute; left: 35%; top: 18%; width: 30.3%; height: 4.7%;"><span class="imagemapname">Pedestal Light</span></div></a>
    <a href="/a32nx-briefing/ovhd-aft/maintenance/"><div class="imagemap" style="position: absolute; left: 65.3%; top: 0%; width: 12.5%; height: 8%;"><span class="imagemapname">Maintenance Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd-aft/reading-light/"><div class="imagemap" style="position: absolute; left: 65.3%; top: 15.3%; width: 12.5%; height: 3.4%;"><span class="imagemapname">Jump Seat Left Light</span></div></a>
    <a href="/a32nx-briefing/ovhd-aft/fms-load/"><div class="imagemap" style="position: absolute; left: 65.3%; top: 18.6%; width: 12.5%; height: 2.2%;"><span class="imagemapname">FMS Load Panel</span></div></a>
    <!-- OVHD FWD Left-->
    <a href="/a32nx-briefing/ovhd/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 23.8%; width: 12.5%; height: 1.7%;"><span class="imagemapname">PA and Cockpit Door Video</span></div></a>
    <a href="/a32nx-briefing/ovhd/adirs/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 25.5%; width: 12.6%; height: 4.5%;"><span class="imagemapname">ADIRS Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/flight-control-computer/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 31.2%; width: 12.6%; height: 1.7%;"><span class="imagemapname">Flight Control Panel Left</span></div></a>
    <a href="/a32nx-briefing/ovhd/evacuation/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 32.9%; width: 12.6%; height: 1.6%;"><span class="imagemapname">Evacuation Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/emergency-electric/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 34.5%; width: 12.6%; height: 1.7%;"><span class="imagemapname">Emergency Electric Power Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/egpws/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 36.2%; width: 12.6%; height: 1.5%;"><span class="imagemapname">Ground Proximity Warning Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/voice-recorder/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 37.7%; width: 12.6%; height: 1.3%;"><span class="imagemapname">Voice Recoder Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/oxygen/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 39%; width: 12.6%; height: 1.5%;"><span class="imagemapname">Oxygen Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/calls/"><div class="imagemap" style="position: absolute; left: 22.5%; top: 40.5%; width: 12.6%; height: 1.45%;"><span class="imagemapname">Calls Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/wipers"><div class="imagemap" style="position: absolute; left: 22.5%; top: 41.95%; width: 12.6%; height: 2.2%;"><span class="imagemapname">Wiper Panel Capt.</span></div></a>
    <!-- OVHD FWD Middle-->
    <a href="/a32nx-briefing/ovhd/fire/"><div class="imagemap" style="position: absolute; left: 35.1%; top: 25.7%; width: 30%; height: 2.7%;"><span class="imagemapname">Fire Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/hyd/"><div class="imagemap" style="position: absolute; left: 35.1%; top: 28.4%; width: 30%; height: 2.3%;"><span class="imagemapname">Hydraulic Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/fuel/"><div class="imagemap" style="position: absolute; left: 35.1%; top: 30.7%; width: 30%; height: 2.2%;"><span class="imagemapname">Fuel Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/elec/"><div class="imagemap" style="position: absolute; left: 35.1%; top: 32.9%; width: 30%; height: 3.6%;"><span class="imagemapname">Electricity Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/ac/"><div class="imagemap" style="position: absolute; left: 35.1%; top: 36.5%; width: 30%; height: 3.9%;"><span class="imagemapname">Air Condition Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/anti-ice/"><div class="imagemap" style="position: absolute; left: 35.1%; top: 40.4%; width: 17.2%; height: 1.7%;"><span class="imagemapname">Anti Ice Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/cab-press/"><div class="imagemap" style="position: absolute; left: 52.3%; top: 40.4%; width: 12.8%; height: 1.7%;"><span class="imagemapname">Cabin Pressure Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/ext-lt/"><div class="imagemap" style="position: absolute; left: 35.1%; top: 42.1%; width: 13.3%; height: 3.2%;"><span class="imagemapname">External Lights Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/apu/"><div class="imagemap" style="position: absolute; left: 48.4%; top: 42.1%; width: 3.2%; height: 3.2%;"><span class="imagemapname">APU Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/int-lt/"><div class="imagemap" style="position: absolute; left: 51.6%; top: 42.1%; width: 13.5%; height: 1.4%;"><span class="imagemapname">Internal Lighting Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/signs/"><div class="imagemap" style="position: absolute; left: 51.6%; top: 43.5%; width: 13.5%; height: 1.6%;"><span class="imagemapname">Sign Panel</span></div></a>
    <!-- OVHD FWD Right-->
    <a href="/a32nx-briefing/ovhd/3rd-acp/"><div class="imagemap" style="position: absolute; left: 65.1%; top: 23.3%; width: 12.6%; height: 3.2%;"><span class="imagemapname">3rd Audio Control Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/flight-control-computer/"><div class="imagemap" style="position: absolute; left: 65.1%; top: 33%; width: 12.6%; height: 1.7%;"><span class="imagemapname">Flight Control Panel Right</span></div></a>
    <a href="/a32nx-briefing/ovhd/cargo-vent/"><div class="imagemap" style="position: absolute; left: 65.1%; top: 34.7%; width: 12.6%; height: 2.4%;"><span class="imagemapname">Cargo Ventilation Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/cargo-smoke/"><div class="imagemap" style="position: absolute; left: 65.1%; top: 37.1%; width: 12.6%; height: 1.65%;"><span class="imagemapname">Cargo Smoke Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/vent/"><div class="imagemap" style="position: absolute; left: 65.1%; top: 38.75%; width: 12.6%; height: 1.6%;"><span class="imagemapname">Ventilation Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/eng-man/"><div class="imagemap" style="position: absolute; left: 65.1%; top: 40.3%; width: 12.6%; height: 1.75%;"><span class="imagemapname">Engine Manual Start and N1 Mode Panel</span></div></a>
    <a href="/a32nx-briefing/ovhd/wipers/"><div class="imagemap" style="position: absolute; left: 65.1%; top: 42%; width: 12.6%; height: 2.2%;"><span class="imagemapname">Wiper Panel F.O.</span></div></a>
    <!-- Glareshield -->
    <a href="/a32nx-briefing/glareshield/fcu/"> <div class="imagemap" style="position: absolute; left: 41.5%; top: 46.5%; width: 17%; height: 3.7%;"><span class="imagemapname">Flight Control Unit</span></div></a>
    <a href="/a32nx-briefing/glareshield/efis_control/">   <div class="imagemap" style="position: absolute; left: 31%; top: 47%; width: 10.5%; height: 3.2%;"><span class="imagemapname">EFIS Control Unit Capt.</span></div></a>
    <a href="/a32nx-briefing/glareshield/efis_control/">   <div class="imagemap" style="position: absolute; left: 58.5%; top: 47%; width: 10.5%; height: 3.2%;"><span class="imagemapname">EFIS Control Unit F.O.</span></div></a>
    <a href="/a32nx-briefing/glareshield/warning/"> <div class="imagemap" style="position: absolute; left: 0%; top: 47.5%; width: 31%; height: 3.2%;"><span class="imagemapname">Alarms and Warnings Capt.</span></div></a>
    <a href="/a32nx-briefing/glareshield/warning/"> <div class="imagemap" style="position: absolute; left: 69%; top: 47.5%; width: 31%; height: 3.2%;"><span class="imagemapname">Alarms and Warnings F.O.</span></div></a>
    <a href="/a32nx-briefing/glareshield/light-knobs/">    <div class="imagemap" style="position: absolute; left: 0%; top: 50.7%; width: 100%; height: 0.8%;"><span class="imagemapname">Light Knobs</span></div></a>
    <a href="/a32nx-briefing/glareshield/light-knobs/">    <div class="imagemap" style="position: absolute; left:31%; top: 50.2%; width: 38%; height: 1.3%;"><span class="imagemapname">Light Knobs</span></div></a>
    <!-- Flight Instruments -->
    <a href="/a32nx-briefing/front/ilcp/"> <div class="imagemap" style="position: absolute; left: 8.5%; top: 51.5%; width: 7%; height: 3.5%;"><span class="imagemapname">Instrument Lighting Control Panel Capt.</span></div></a>
    <a href="/a32nx-briefing/front/pfd/"> <div class="imagemap" style="position: absolute; left: 15.5%; top: 51.5%; width: 10.5%; height: 5.5%;"><span class="imagemapname">PFD Capt.</span></div></a>
    <a href="/a32nx-briefing/front/nd/"> <div class="imagemap" style="position: absolute; left: 26%; top: 51.5%; width: 10.5%; height: 5.5%;"><span class="imagemapname">ND Capt.</span></div></a>
    <a href="/a32nx-briefing/front/nd/"> <div class="imagemap" style="position: absolute; left: 36.5%; top: 55.4%; width: 3.2%; height: 2.1%;"><span class="imagemapname">Terrain Switch for ND</span></div></a>
    <a href="/a32nx-briefing/front/nd/"> <div class="imagemap" style="position: absolute; left: 64%; top: 51.5%; width: 10%; height: 5.5%;"><span class="imagemapname">ND F.O.</span></div></a>
    <a href="/a32nx-briefing/front/pfd/"> <div class="imagemap" style="position: absolute; left: 74%; top: 51.5%; width: 10.5%; height: 5.5%;"><span class="imagemapname">PFD F.O.</span></div></a>
    <a href="/a32nx-briefing/front/ilcp/"> <div class="imagemap" style="position: absolute; left: 84.5%; top: 51.5%; width: 7%; height: 3.5%;"><span class="imagemapname">Instrument Lighting Control Panel F.O.</span></div></a>
    <a href="/a32nx-briefing/front/isis/"> <div class="imagemap" style="position: absolute; left: 39.7%; top: 53.5%; width: 5.2%; height: 2.8%;"><span class="imagemapname">Integrated Standby Instrument System</span></div></a>
    <a href="/a32nx-briefing/front/dcdu/"> <div class="imagemap" style="position: absolute; left: 36.5%; top: 59.2%; width: 8%; height: 2.5%;"><span class="imagemapname">Datalink Ctl and Display Unit</span></div></a>
    <a href="/a32nx-briefing/front/upper-ecam/"> <div class="imagemap" style="position: absolute; left: 45%; top: 51.5%; width: 11%; height: 5.1%;"><span class="imagemapname">Upper ECAM</span></div></a>
    <a href="/a32nx-briefing/front/lower-ecam/"> <div class="imagemap" style="position: absolute; left: 45%; top: 56.6%; width: 11%; height: 5.2%;"><span class="imagemapname">Lower ECAM</span></div></a>
    <a href="/a32nx-briefing/front/autobrake-gear/"><div class="imagemap" style="position: absolute; left: 56%; top: 51.5%; width: 8%; height: 2.3%;"><span class="imagemapname">Autobrake and Gear</span></div></a>
    <a href="/a32nx-briefing/front/clock/"> <div class="imagemap" style="position: absolute; left: 56%; top: 53.8%; width: 5.2%; height: 2.5%;"><span class="imagemapname">Clock</span></div></a>
    <a href="/a32nx-briefing/front/nd/"> <div class="imagemap" style="position: absolute; left: 61.2%; top: 53.8%; width: 2.8%; height: 2.5%;"><span class="imagemapname">Terrain Switch for ND</span></div></a>
    <a href="/a32nx-briefing/front/autobrake-gear/"><div class="imagemap" style="position: absolute; left: 56%; top: 56.3%; width: 4%; height: 2.9%;"><span class="imagemapname">Gear</span></div></a>
    <a href="/a32nx-briefing/front/accu/"> <div class="imagemap" style="position: absolute; left: 60%; top: 57.2%; width: 4%; height: 2.0%;"><span class="imagemapname">Accumulator Pressure Indication</span></div></a>
    <a href="/a32nx-briefing/front/dcdu/"> <div class="imagemap" style="position: absolute; left: 56%; top: 59.2%; width: 8%; height: 2.5%;"><span class="imagemapname">Datalink Ctl and Display Unit</span></div></a>
    <!-- Pedestal -->
    <a href="/a32nx-briefing/pedestal/switching/"><div class="imagemap" style="position: absolute; left: 41.2%; top: 62.5%; width: 17.6%; height: 3.2%;"><span class="imagemapname">Switching Panel</span></div></a>
    <a href="/a32nx-briefing/pedestal/ecam-control/"><div class="imagemap" style="position: absolute; left: 41.2%; top: 65.7%; width: 17.6%; height: 3.2%;"><span class="imagemapname">ECAM Control Panel</span></div></a>
    <a href="/a32nx-briefing/pedestal/mcdu/"><div class="imagemap" style="position: absolute; left: 28.9%; top: 62.5%; width: 12.3%; height: 9.9%;"><span class="imagemapname">MCDU Capt.</span></div></a>
    <a href="/a32nx-briefing/pedestal/mcdu/"><div class="imagemap" style="position: absolute; left: 58.8%; top: 62.5%; width: 12.3%; height: 9.9%;"><span class="imagemapname">MCDU F.O.</span></div></a>
    <a href="/a32nx-briefing/pedestal/rmp/"><div class="imagemap" style="position: absolute; left: 28.9%; top: 72.4%; width: 12.3%; height: 7.7%;"><span class="imagemapname">RMP and Audio Control Capt.</span></div></a>
    <a href="/a32nx-briefing/pedestal/rmp/"><div class="imagemap" style="position: absolute; left: 58.8%; top: 72.4%; width: 12.3%; height: 7.7%;"><span class="imagemapname">RMP and Audio Control F.O.</span></div></a>
    <a href="/a32nx-briefing/pedestal/thrust-elev-trim/"><div class="imagemap" style="position: absolute; left: 41.2%; top: 70%; width: 17.6%; height: 11.7%;"><span class="imagemapname">Thrust Lever and Elevation Trim</span></div></a>
    <a href="/a32nx-briefing/pedestal/engine/"><div class="imagemap" style="position: absolute; left: 45.5%; top: 81.7%; width: 8.9%; height: 3.3%;"><span class="imagemapname">Engine Panel</span></div></a>
    <a href="/a32nx-briefing/pedestal/lighting-capt/"><div class="imagemap" style="position: absolute; left: 28.9%; top: 80.1%; width: 12.3%; height: 2.2%;"><span class="imagemapname">Lighting Capt.</span></div></a>
    <a href="/a32nx-briefing/pedestal/radar/"><div class="imagemap" style="position: absolute; left: 28.9%; top: 82.3%; width: 12.3%; height: 2.8%;"><span class="imagemapname">Radar Panel</span></div></a>
    <a href="/a32nx-briefing/pedestal/lighting-aids-dfdr/"><div class="imagemap" style="position: absolute; left: 58.8%; top: 80.1%; width: 12.3%; height: 2.2%;"><span class="imagemapname">Lighting, AIDS, DFDR F.O.</span></div></a>
    <a href="/a32nx-briefing/pedestal/atc-tcas/"><div class="imagemap" style="position: absolute; left: 58.8%; top: 82.3%; width: 12.3%; height: 2.8%;"><span class="imagemapname">ATC and TCAS Panel</span></div></a>
    <a href="/a32nx-briefing/pedestal/speedbrake/"><div class="imagemap" style="position: absolute; left: 41.2%; top: 84%; width: 4.3%; height: 4.9%;"><span class="imagemapname">Speed Brake</span></div></a>
    <a href="/a32nx-briefing/pedestal/flaps/"><div class="imagemap" style="position: absolute; left: 54.4%; top: 84%; width: 4.3%; height: 4.9%;"><span class="imagemapname">Flaps</span></div></a>
    <a href="/a32nx-briefing/pedestal/cockpit-door/"><div class="imagemap" style="position: absolute; left: 34%; top: 88.9%; width: 12.3%; height: 2.6%;"><span class="imagemapname">Cockpit Door Panel</span></div></a>
    <a href="/a32nx-briefing/pedestal/printer/"><div class="imagemap" style="position: absolute; left: 54%; top: 88.9%; width: 12.3%; height: 7.5%;"><span class="imagemapname">Printer</span></div></a>
    <a href="/a32nx-briefing/pedestal/rudder-trim/"><div class="imagemap" style="position: absolute; left: 46.3%; top: 86.6%; width: 8%; height: 3.1%;"><span class="imagemapname">Rudder Trim</span></div></a>
    <a href="/a32nx-briefing/pedestal/parking-brake/"><div class="imagemap" style="position: absolute; left: 46.3%; top: 90.8%; width: 8%; height: 3.2%;"><span class="imagemapname">Parking Brake</span></div></a>
    <a href="/a32nx-briefing/pedestal/gravity-gear-ext/"><div class="imagemap" style="position: absolute; left: 46.3%; top: 94%; width: 8%; height: 3.2%;"><span class="imagemapname">Gravity Gear Extension</span></div></a>

</div>


