cmake_minimum_required(VERSION 3.0.0)

include(cmake/zz.cmake)

project(ZZ)

add_subdirectory(Prelude)
add_subdirectory(CmdLine)
add_subdirectory(Generics)
add_subdirectory(Unix)
add_subdirectory(EXTERN)
add_subdirectory(Lua)

add_subdirectory(Npn4)
add_subdirectory(Netlist)
add_subdirectory(MiniSat)
add_subdirectory(MetaSat)
add_subdirectory(BFunc)
add_subdirectory(CnfMap)
add_subdirectory(Bip/Common)
add_subdirectory(Abc)
add_subdirectory(AbcInterface)
add_subdirectory(Bip)

add_subdirectory(Md5)
add_subdirectory(Cluster)
add_subdirectory(CutSim)
add_subdirectory(LinReg)
add_subdirectory(Liberty)
add_subdirectory(Verilog)
add_subdirectory(DelayOpt)
add_subdirectory(Dsd)
add_subdirectory(EqCheck)
add_subdirectory(Exploratory/Xml)
add_subdirectory(Gig)
add_subdirectory(LutMap)
add_subdirectory(TechMap)
add_subdirectory(Gip)
add_subdirectory(MaxSat)
add_subdirectory(Fta)
add_subdirectory(PunySat)

add_subdirectory(Graphics)
add_subdirectory(Sdl)