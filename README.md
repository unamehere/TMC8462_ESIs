# TMC8462_ESIs
Here live some ESI /XML  Config Files for the TMC8462 Ethercat Slave. 
I had start problems with this chip and found no information on the internet.
So I'll put some of my Knowledge about this Chip here. 

Status 17.06.21: Currently the Ethercat TM8462 Config Wizard in the Trinamic IDE dosen't work properly. 
There are no padding bytes needed at the end of the Rx/TxPDOs (write_registers /read_registers).
