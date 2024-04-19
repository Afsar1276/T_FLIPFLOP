# AIM:
To simulate and synthesis t flipflop using vivado
# APPARATUS REQUIRED:
vivado
#
PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the Fille Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# T_FLIPFLOP
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/74140ea2-0b93-4ffc-b38b-527fb2ece133)
# Truth Table
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/1d4afa40-166a-4690-ab1a-179948b9b550)
# VERILOG CODE:
```
module tff(clk,rst,j,q);
input clk,rst,j;
output reg q;
always@(posedge clk)
begin
case(t)
1'b0:q=q;
1'b1:q=~q;
default=q=1'b0;
endcase
end
endmodule
```
# OUTPUT:
![WhatsApp Image 2024-04-19 at 19 29 45_2834f763](https://github.com/Afsar1276/T_FLIPFLOP/assets/161407741/4d6ee4f7-72d0-4fa2-af39-dd54333d1878)
# RESULT:
RESULT:
Thus, the verilog program for t flipflop has been simulated and verified successfully.
