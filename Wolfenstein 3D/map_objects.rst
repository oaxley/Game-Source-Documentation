.. default-role:: code

================
Map object codes
================

The following is a list of words (two bytes) and their corresponding map
objects.  Some objects are walls and only used on the *Architecture* map, others
are decoration objects and used on the *Objects* map. No two objects have the
same byte even though they always appear on different maps. The list was adapted
from the *MAPDATA.DEF* file of the *Nmap* editor by Nathan Lineback. See below
for acknowledgements.

The codes are similar, but not exactly the same for Wolfenstein 3D and Spear of
Destiny, so there are extra columns for the two of them. The SoD mission packs
on the other hand are just using re-drawn graphics while the hard-coded data is
the same as for SoD, so there are no colums for them.

========  ============================  =====================  ===================  ===================
Word      Wolf3D Architecture           Wofl3D Objects         SoD Architecture     SoD Objects        
========  ============================  =====================  ===================  ===================
`0x0000`  Nothing/Undefined             Nothing/Undefined      Nothing/Undefined    Nothing/Undefined  
`0x0001`  Grey Stone 1                                         Grey stone 1                            
`0x0002`  Grey Stone 2                                         Grey stone 2                            
`0x0003`  Grey with banner                                     Grey w/banner                           
`0x0004`  Grey with Hitler                                     Grey w/hitler                           
`0x0005`  Cell                                                 Cell                                    
`0x0006`  Grey with eagle                                      Grey w/eagle                            
`0x0007`  Grey with skeleton                                   Cell w/skeleton                         
`0x0008`  Blue Stone 1                                         Blue stone 1                            
`0x0009`  Blue Stone 2                                         Blue stone 2                            
`0x000A`  Wood w/eagle                                         Wood w/eagle                            
`0x000B`  Wood w/hitler                                        Wood w/hitler                           
`0x000C`  Wood panelling                                       Wood panelling                          
`0x000D`  Entrance to level                                    Entrance to level                       
`0x000E`  Steel w/signs                                        Steel w/signs                           
`0x000F`  Steel plate                                          Steel plate                             
`0x0010`  Landscape                                            Landscape                               
`0x0011`  Red brick                                            Red brick                               
`0x0012`  Red w/wreath                                         Red w/wreath                            
`0x0013`  Purple wall                   Start, face N          Purple wall          Start, face N      
`0x0014`  Red w/shield                  Start, face E          Red w/shield         Start, face E      
`0x0015`  Elevator <>                   Start, face S          Elevator <>          Start, face S      
`0x0016`  Elevator 2 ^v                 Start, face W          Elevator 2 ^v        Start, face W      
`0x0017`  Wood w/symbol                 Water                  Wood w/symbol        Water              
`0x0018`  stone w/yellow stf            Oil drum               stone w/yellow stf   Oil drum           
`0x0019`  Purple w/blood                Table & Chairs         Purple w/blood       Table & Chairs     
`0x001A`  stone w/yellow2               Floor lamp             stone w/yellow2      Floor lamp         
`0x001B`  Grey stone 3                  Chandelier             Grey stone 3         Chandelier         
`0x001C`  Grey stone w/signs            Hanging skeleton       Grey stone w/signs   Hanging skeleton   
`0x001D`  Tan design                    Dog food               Tan design           Dog food           
`0x001E`  Tan W blood                   Column                 Tan W blood          Column             
`0x001F`  Tan W blood 2                 Potted tree            Tan W blood 2        Potted tree        
`0x0020`  Tan W blood 3                 Skeleton               Tan W blood 3        Skeleton           
`0x0021`  Wblock/Hitler                 Washbasin              Wblock/Hitler        Skulls on stick    
`0x0022`  Blueblock/Face                Potted bush            Blueblock/Face       Potted bush        
`0x0023`  White block                   Vase                   White block          Vase               
`0x0024`  Bblock W symbol               Table                  Bblock W symbol      Table              
`0x0025`  Wblock W Bit                  Overhead lamp          Wblock W Bit         Overhead lamp      
`0x0026`  R/W/Y/bricks                  Pot & Pan rack         R/W/Y/bricks         Cage W guts        
`0x0027`  Wbrick W crack                Armor                  Wbrick W crack       Armor              
`0x0028`  Blue Block                    Cage, empty            Blue Block           Cage, empty        
`0x0029`  Blue stone/sign               Cage, with skeleton    Blue stone/sign      Cage, with skeleton
`0x002A`  Tan pannel                    Bones                  Tan pannel           Bones              
`0x002B`  Wblock w map                  Key 1 (yellow)         Wblock w map         Key 1 (yellow)     
`0x002C`  Tan stone                     Key 2 (grey)           Tan stone            Key 2 (grey)       
`0x002D`  Tan stone2                    Bed                    Tan stone2           Cage w skulls      
`0x002E`  Tan pannel 2                  Pot                    Tan pannel 2         Pot                
`0x002F`  Tan Pannel/flag               Food                   Tan Pannel/flag      Food               
`0x0030`  Plasterboard                  First aid kit          Plasterboard         First aid kit      
`0x0031`  Wblock w Pic                  Ammunition             Wblock w Pic         Ammunition         
`0x0032`                                Machine gun            Rock wall 1          Machine gun        
`0x0033`                                Huge gun               Rock wall 2          Huge gun           
`0x0034`                                Cross                  Rock /w banner       Cross              
`0x0035`                                Cup                    Rock /w reath        Cup                
`0x0036`                                Jewels                 Grey marble 1        Jewels             
`0x0037`                                Crown                  Grey marble 2        Crown              
`0x0038`                                Sphere / life          Hot wall             Sphere / life      
`0x0039`                                Bloody bones           Grey flat marble     Bloody bones       
`0x003A`                                Brown barrel           Stone fence 1        Brown barrel       
`0x003B`                                Well with water        Stone fence 2        Well with water    
`0x003C`                                Well empty             Elevator decoration  Well empty         
`0x003D`                                Blood                  White wall           Blood              
`0x003E`                                Flag                   Brown Marble         Flag               
`0x003F`                                Call Apogee            Purple Brick         Overhead lamp2     
`0x0040`                                Trash 1                                     Trash 1            
`0x0041`                                Trash 2                                     Trash 2            
`0x0042`                                Trash 3                                     Trash 3            
`0x0043`                                Pot/Pan Rack2                               Animal skull stick 
`0x0044`                                Oven                                        Pool of guts       
`0x0045`                                Spear Rack                                  Demon statue       
`0x0046`                                Vines                                       Vines              
`0x0047`                                                                            Tan pillar         
`0x0048`                                                                            Ammo Box           
`0x0049`                                                                            Truck              
`0x004A`                                                                            Spear              
`0x004B`                                                                                               
`0x004C`                                                                                               
`0x004D`                                                                                               
`0x004E`                                                                                               
`0x004F`                                                                                               
`0x0050`                                                                                               
`0x0051`                                                                                               
`0x0052`                                                                                               
`0x0053`                                                                                               
`0x0054`                                                                                               
`0x0055`                                                                                               
`0x0056`                                                                                               
`0x0057`                                                                                               
`0x0058`                                                                                               
`0x0059`                                                                                               
`0x005A`  Door                          Move East              Door                 Move >             
`0x005B`  Door                          Move North-East        Door                 Move />            
`0x005C`  Locked door                   Move ^                 Locked door          Move ^             
`0x005D`  Locked door                   Move <\                Locked door          Move <\            
`0x005E`  Locked door 2 Vertical        Move <                 Locked door 2        Move <             
`0x005F`  Locked door 2 Horizontal      Move </                Locked door 2 -      Move </            
`0x0060`  Fixed door Vertical           Move v                 Fixed door           Move v             
`0x0061`  Fixed door Horizontal         Move \>                Fixed door -         Move \>            
`0x0062`  Fixed door Vertical           Secret door            Fixed door           Secret door        
`0x0063`  Fixed door Horizontal         End of game trigger    Fixed door -         End of game trigger
`0x0064`  Elevator entrance Vertical                           Elevator entrance                       
`0x0065`  Elevator entrance Horizontal                         Elevator entrance -                     
`0x0066`                                                                                               
`0x0067`                                                                                               
`0x0068`                                                                                               
`0x0069`                                                                                               
`0x006A`  Stasis Area 6A                                       Stasis Area 6A       WEIRD THING        
`0x006B`                                                                            LAST SOD GUY       
`0x006C`  Area 6C                       Guard 1 East           Area 6C              Guard 1 >          
`0x006D`  Area 6D                       Guard 1 ^              Area 6D              Guard 1 ^          
`0x006E`  Area 6E                       Guard 1 <              Area 6E              Guard 1 <          
`0x006F`  Area 6F                       Guard 1 v              Area 6F              Guard 1 v          
`0x0070`  Area 70                       Guard 1 > moving       Area 70              Guard 1 > moving   
`0x0071`  Area 71                       Guard 1 ^ moving       Area 71              Guard 1 ^ moving   
`0x0072`  Area 72                       Guard 1 < moving       Area 72              Guard 1 < moving   
`0x0073`  Area 73                       Guard 1 v moving       Area 73              Guard 1 v moving   
`0x0074`  Area 74                       W Guard 1 East         Area 74              W Guard 1 >        
`0x0075`  Area 75                       W Guard 1 ^            Area 75              W Guard 1 ^        
`0x0076`  Area 76                       W Guard 1 <            Area 76              W Guard 1 <        
`0x0077`  Area 77                       W Guard 1 v            Area 77              W Guard 1 v        
`0x0078`  Area 78                       W Guard 1 > moving     Area 78              W Guard 1 > moving 
`0x0079`  Area 79                       W Guard 1 ^ moving     Area 79              W Guard 1 ^ moving 
`0x007A`  Area 7A                       W Guard 1 < moving     Area 7A              W Guard 1 < moving 
`0x007B`  Area 7B                       W Guard 1 v moving     Area 7B              W Guard 1 v moving 
`0x007C`  Area 7C                       Dead guard             Area 7C              Dead guard         
`0x007D`  Area 7D                                              Area 7D              SOD GUY1           
`0x007E`  Area 7E                       Officer 1  East        Area 7E              Officer 1  >       
`0x007F`  Area 7F                       Officer 1  ^           Area 7F              Officer 1  ^       
`0x0080`  Area 80                       Officer 1  <           Area 80              Officer 1  <       
`0x0081`  Area 81                       Officer 1  v           Area 81              Officer 1  v       
`0x0082`  Area 82                       Officer 1  > moving    Area 82              Officer 1  > moving
`0x0083`  Area 83                       Officer 1  ^ moving    Area 83              Officer 1  ^ moving
`0x0084`  Area 84                       Officer 1  < moving    Area 84              Officer 1  < moving
`0x0085`  Area 85                       Officer 1  v moving    Area 85              Officer 1  v moving
`0x0086`  Area 86                                              Area 86                                 
`0x0087`  Area 87                                              Area 87                                 
`0x0088`  Area 88                                              Area 88                                 
`0x0089`  Area 89                                              Area 89                                 
`0x008A`  Area 8A                       Dog 1 East             Area 8A              Dog 1 >            
`0x008B`  Area 8B                       Dog 1 ^                Area 8B              Dog 1 ^            
`0x008C`  Area 8C                       Dog 1 <                Area 8C              Dog 1 <            
`0x008D`  Area 8D                       Dog 1 v                Area 8D              Dog 1 v            
`0x008E`  Area 8E                                              Area 8E              SOD GUY4           
`0x008F`  Area 8F                                              Area 8F              SOD GUY2           
`0x0090`                                Guard 2 East                                Guard 2 >          
`0x0091`                                Guard 2 ^                                   Guard 2 ^          
`0x0092`                                Guard 2 <                                   Guard 2 <          
`0x0093`                                Guard 2 v                                   Guard 2 v          
`0x0094`                                Guard 2 East moving                         Guard 2 > moving   
`0x0095`                                Guard 2 ^ moving                            Guard 2 ^ moving   
`0x0096`                                Guard 2 < moving                            Guard 2 < moving   
`0x0097`                                Guard 2 v moving                            Guard 2 v moving   
`0x0098`                                W Guard 2 East                              W Guard 2 >        
`0x0099`                                W Guard 2 ^                                 W Guard 2 ^        
`0x009A`                                W Guard 2 <                                 W Guard 2 <        
`0x009B`                                W Guard 2 v                                 W Guard 2 v        
`0x009C`                                W Guard 2 East moving                       W Guard 2 > moving 
`0x009D`                                W Guard 2 ^ moving                          W Guard 2 ^ moving 
`0x009E`                                W Guard 2 < moving                          W Guard 2 < moving 
`0x009F`                                W Guard 2 v moving                          W Guard 2 v moving 
`0x00A0`                                Floating guy                                Floating guy       
`0x00A1`                                                                            SOD GUY3           
`0x00A2`                                Officer 2 East                              Officer 2 >        
`0x00A3`                                Officer 2 ^                                 Officer 2 ^        
`0x00A4`                                Officer 2 <                                 Officer 2 <        
`0x00A5`                                Officer 2 v                                 Officer 2 v        
`0x00A6`                                Officer 2 > moving                          Officer 2 > moving 
`0x00A7`                                Officer 2 ^ moving                          Officer 2 ^ moving 
`0x00A8`                                Officer 2 < moving                          Officer 2 < moving 
`0x00A9`                                Officer 2 v moving                          Officer 2 v moving 
`0x00AA`                                                                                               
`0x00AB`                                                                                               
`0x00AC`                                                                                               
`0x00AD`                                                                                               
`0x00AE`                                Dog 2 E                                     Dog 2 E            
`0x00AF`                                Dog 2 N                                     Dog 2 N            
`0x00B0`                                Dog 2 W                                     Dog 2 W            
`0x00B1`                                Dog 2 S                                     Dog 2 S            
`0x00B2`                                Robo Hitler                                 Robo Hitler        
`0x00B3`                                General                                     General            
`0x00B4`                                Guard 3 E                                   Guard 3 E          
`0x00B5`                                Guard 3 N                                   Guard 3 N          
`0x00B6`                                Guard 3 W                                   Guard 3 W          
`0x00B7`                                Guard 3 S                                   Guard 3 S          
`0x00B8`                                Guard 3 E moving                            Guard 3 E moving   
`0x00B9`                                Guard 3 N moving                            Guard 3 N moving   
`0x00BA`                                Guard 3 W moving                            Guard 3 W moving   
`0x00BB`                                Guard 3 S moving                            Guard 3 S moving   
`0x00BC`                                W Guard 3 E                                 W Guard 3 E        
`0x00BD`                                W Guard 3 N                                 W Guard 3 N        
`0x00BE`                                W Guard 3 W                                 W Guard 3 W        
`0x00BF`                                W Guard 3 S                                 W Guard 3 S        
`0x00C0`                                W Guard 3 E moving                          W Guard 3 E moving 
`0x00C1`                                W Guard 3 N moving                          W Guard 3 N moving 
`0x00C2`                                W Guard 3 W moving                          W Guard 3 W moving 
`0x00C3`                                W Guard 3 v moving                          W Guard 3 S moving 
`0x00C4`                                Dr Schabbs                                  Dr Schabbs         
`0x00C5`                                BIG Guardet!                                BIG Guardet!       
`0x00C6`                                Officer 3 East                              Officer 3 >        
`0x00C7`                                Officer 3 ^                                 Officer 3 ^        
`0x00C8`                                Officer 3 <                                 Officer 3 <        
`0x00C9`                                Officer 3 v                                 Officer 3 v        
`0x00CA`                                Officer 3 East moving                       Officer 3 > moving 
`0x00CB`                                Officer 3 ^ moving                          Officer 3 ^ moving 
`0x00CC`                                Officer 3 < moving                          Officer 3 < moving 
`0x00CD`                                Officer 3 v moving                          Officer 3 v moving 
`0x00CE`                                                                                               
`0x00CF`                                                                                               
`0x00D0`                                                                                               
`0x00D1`                                                                                               
`0x00D2`                                Dog 3 >                                     Dog 3 >            
`0x00D3`                                Dog 3 ^                                     Dog 3 ^            
`0x00D4`                                Dog 3 <                                     Dog 3 <            
`0x00D5`                                Dog 3 v                                     Dog 3 v            
`0x00D6`                                Hans Grösse (boss)                          BIG Guard!         
`0x00D7`                                Big officer                                 Big officer        
`0x00D8`                                Zombie 1 East                               Zombie 1 >         
`0x00D9`                                Zombie 1 ^                                  Zombie 1 ^         
`0x00DA`                                Zombie 1 <                                  Zombie 1 <         
`0x00DB`                                Zombie 1 v                                  Zombie 1 v         
`0x00DC`                                Zombie 1 East                               Zombie 1 > moving  
`0x00DD`                                Zombie 1 ^                                  Zombie 1 ^ moving  
`0x00DE`                                Zombie 1 <                                  Zombie 1 < moving  
`0x00DF`                                Zombie 1 v                                  Zombie 1 v moving  
`0x00E0`                                Blinky (red ghost)                          Red Ghost          
`0x00E1`                                Clyde (orange ghost                         Orange Ghost       
`0x00E2`                                Pinky (pink ghost)                          Light red Ghost    
`0x00E3`                                Inky (blue ghost)                           Blue Ghost         
`0x00E4`                                                                                               
`0x00E5`                                                                                               
`0x00E6`                                                                                               
`0x00E7`                                                                                               
`0x00E8`                                                                                               
`0x00E9`                                                                                               
`0x00EA`                                Zombie 2 East                               Zombie 2 >         
`0x00EB`                                Zombie 2 ^                                  Zombie 2 ^         
`0x00EC`                                Zombie 2 <                                  Zombie 2 <         
`0x00ED`                                Zombie 2 v                                  Zombie 2 v         
`0x00EE`                                Zombie 2 East                               Zombie 2 > moving  
`0x00EF`                                Zombie 2 ^                                  Zombie 2 ^ moving  
`0x00F0`                                Zombie 2 <                                  Zombie 2 < moving  
`0x00F1`                                Zombie 2 v                                  Zombie 2 v moving  
`0x00F2`                                                                                               
`0x00F3`                                                                                               
`0x00F4`                                                                                               
`0x00F5`                                                                                               
`0x00F6`                                                                                               
`0x00F7`                                                                                               
`0x00F8`                                                                                               
`0x00F9`                                                                                               
`0x00FA`                                                                                               
`0x00FB`                                                                                               
`0x00FC`                                Zombie 3 E                                  Zombie 3 E         
`0x00FD`                                Zombie 3 N                                  Zombie 3 N         
`0x00FE`                                Zombie 3 W                                  Zombie 3 W         
`0x00FF`                                Zombie 3 S                                  Zombie 3 S         
`0x0100`                                Zombie 3 East                               Zombie 3 > moving  
`0x0101`                                Zombie 3 North                              Zombie 3 ^ moving  
`0x0102`                                Zombie 3 <                                  Zombie 3 < moving  
`0x0103`                                Zombie 3 v                                  Zombie 3 v moving  
========  ============================  =====================  ===================  ===================

Ackgnowledgements
=================
NMAP Wolf3d map editor by Nathan Lineback [http://toastytech.com/files/nmap.html]
