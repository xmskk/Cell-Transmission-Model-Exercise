# Cell-Transmission-Model-Exercise
Exercise problem for the cell transmission model of traffic control

# Setup

The figure below describes the model of a highway stretch that is 4 km long. It is divided into 8 cells (0 ~ 7) with each cell being 500 m long. As depicted, there is one on-ramp at cell 1 and one off-ramp at cell 5.

<img src='https://user-images.githubusercontent.com/28818052/148681385-60ed6a2c-ea33-4ed8-9294-d5227ff33b87.png' width='600'>

The highway follows the following properties:
	Jam Density: 120 veh/km/lane 
	Critical Density: 20% of jam density 
	Maximum flow: 2000 veh/h/lane 
The demand profiles for the mainline and the on-ramp is depicted below. The highway does not have any vehicles in the initial state. And the split ratio at the off-ramp of cell 5 is 40%.

<img src='https://user-images.githubusercontent.com/28818052/148681429-ffe47ddb-89b8-45d2-900f-853a840d3978.png' width='600'>

# Simulation

To investigate the behavior of the CTM model, Δt is set to 20 seconds and the simulation was ran for 100 minutes. After the 60-minute mark, both inflow demands were set to 0. The detailed procedure of the code is described as follows:

<img src='https://user-images.githubusercontent.com/28818052/148681456-624476fe-6837-4543-b622-45b65f375377.PNG' width='600'>

# Results

The following figures depict the results of the simulation and the resulting VHT and VKT are 692.8 veh*h and 13822.5 veh*km, respectively.

<img src='https://user-images.githubusercontent.com/28818052/148681687-46639024-9989-4a54-b428-569571799383.png' width='600'>
<img src='https://user-images.githubusercontent.com/28818052/148681688-d8426779-1edd-48b5-a6e6-6626823f74a6.png' width='600'>
<img src='https://user-images.githubusercontent.com/28818052/148681689-37de7457-f595-46ed-aa0f-39c713c276fe.png' width='600'>
<img src='https://user-images.githubusercontent.com/28818052/148681690-0bee520b-6633-461a-b1b8-be4fd3f876bf.png' width='700'>


