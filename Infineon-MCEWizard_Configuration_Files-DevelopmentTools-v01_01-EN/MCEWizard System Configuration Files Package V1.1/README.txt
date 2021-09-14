This .zip file contains the MCEWIzard System Configuration Files for all the iMOTION evaluation boards supported. These files include:

-All supported combinations of the iMOTION MADK control board and the match MADK inverter board
-iMOTION Starter kits
-iMOTION Reference designs
-iMOTION Training kits

For MADK Boards, all the System Configuration Files are consolidated under single MADK inverter board folder. In case that there are
more controller boards which can be combined with this inverter board, each combination of controller + inverter board will have 
its own System Configuration File and the name of the file will indicate the corresponding controller and inverter board used in this combination.

When starting the new system setup in MCEWizard which is based on one of the iMOTION boards, the first step would be 
to open System Configuration File for that particular board.

## [v 1.1] - 2020-20-07
### Changed
- UART connectivity update. V1.0 had System question 18 set up to UART0. For proper iMOTION MCEDEsigner connectivity UART in question 18 has ben set up 
  to UART1

### Added
- EVAL-M1-05F310R
- EVAL-M1-05F804R
- EVAL-M3-IM564