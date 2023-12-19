JTAG (Joint Test Action Group) IEEE 1149.1

#-----------
# Components
#-----------
- TAP ACCESS PORT (TAP)
- TAP Controller
- Registers
- Instruction Decoder

#----------
# Registers
#----------
Registers are two types
- Instruction Register
- Data Register (Bypass Register, Boundary Scan Register, Device ID Register(optional), User Data Register(optional))

#----------------------
# TAP ACCESS PORT (TAP)
#----------------------
The JTAG interface called a TAP or Test Access Port uses different signals for supporting the boundary scan operation like TCK, TMS, TDI, TDO, and TRST.
TCK - Test clock
TMS - Test Mode Select
TDI - Test Data Input
TDO - Test Data Output
TRST - Test Reset

 

