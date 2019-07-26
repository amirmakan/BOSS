# BOSS
Building Operation Smart System
BIM 7D software fro Facility Management 
1. Facility Management
2. Monitoring building behavior
3. Maintenace 
4. Bulding easy control
5. Energy Saving 

![](https://user-images.githubusercontent.com/6995838/61962611-254ecd80-afdf-11e9-8c0e-19eabd0cb388.png)

## Δ.By


| `Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|All	 	  	| `Δ.By.All()`      		| Gets all building elements 	|
|Category	  	| `Δ.By.Category(param)`   	| Gets specific element categories   	| `Windows,Doors`			|
|Type	  		| `Δ.By.Type(param)`   		| Gets specific element types   		| `Basic Walls`,`Curtain Walls`|
|Family	  		| `Δ.By.Family(param)`   	| Gets specific element families   		| `30cm Concrete`|
|Id	  			| `Δ.By.Id(param)`   		| Gets elements with specific Ids    	| `677763`|
|TypeId	  		| `Δ.By.TypeId(param)`   	| Gets elements with specific type Ids   	|`687764`|
|GUID	  		| `Δ.By.GUID(param)`   		| Gets elements with specific GUIDs     	|`1Fi$QD3af91OzrSrmvLvXA`|
|Mark	  		| `Δ.By.Mark(param)`   		| Gets elements with specific Type GUIDs   	|`1Fi$QD3af91OzrSrmvLuqy`|

#### Δ.By.Type

|`Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|Type 	  	| `Δ.By.Type(param)`    		| Gets all building elements by given type name 	|`Basic Walls`,`Curtain Walls`|
|Name	  		| `Δ.By.Type.Name(param)`   	| Gets all building elements by given type name   	| `2 m`		|
|TypeMark	  		| `Δ.By.Type.TypeMark(param)`   		| Gets specific element by given type marks   		| `AW101`	|
|TypeGUID	  		| `Δ.By.Type.TypeGUID(param)`   	| Gets all element with specific  type GUIDs   		| `1Fi$QD3af91OzrSrmvLvXA`|
|TypeId	  		| `Δ.By.Type.TypeId(param)`   		| Gets elements with specific type Ids    	| `3453553`|
|OmniClass	  	| `Δ.By.Type.OmniClass(param)` 		| Gets elements with specific omni classes    	| `20.32.45.11`|
|Category	  	| `Δ.By.Type.Category(param)`   	| Gets specific element categories   	| `Windows,Doors`	|
|Family	  		| `Δ.By.Type.Family(param)`   	| Gets specific element families   		| `30cm Concrete`|


#### Δ.By.Quantity

|`Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|Quantity 	  	| `Δ.By.Quantity(param)`    		| Gets all building elements with given quantities 	|`{Area:[20,30],Volume:[5,6]}`
|Length	  		| `Δ.By.Quantity.Length(param)`   	| Gets specific element length   	| `2 m`			|
|Area	  		| `Δ.By.Quantity.Area(param)`   		| Gets specific element area   		| `20 m2`	|
|Volume	  		| `Δ.By.Quantity.Volume(param)`   	| Gets specific element volume   		| `4 m3`|
|Width	  		| `Δ.By.Quantity.Width(param)`   		| Gets specific element width     	| `300 cm`|
|Perimeter	  	| `Δ.By.Quantity.Perimeter(param)` 		| Gets specific element perimeter     	| `4200 mm`|

#### Δ.By.Space
| `Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|Space 	  	| `Δ.By.Space(param)`    				| Gets all building elements in given space names	|`{Area:[20,30],Volume:[5,6]}`
|Id	  		| `Δ.By.Space.Id(param)`   				| Gets all building elements in given space Ids    	| `348984`			|
|No	  		| `Δ.By.Space.No(param)`   				|Gets all building elements in given spaces numbers 		| `205`	|
|Name	  		| `Δ.By.Space.Name(param)`   		| Gets all building elements in given space names    		| `Corridor`|
|Zone	  		| `Δ.By.Space.Zone(param)`   		| Gets all building elements in given zone names    	| `Official`|
|Occupancy	  	| `Δ.By.Space.Occupancy(param)`   	|Gets all building elements with given occupancy   	| `Circulation`	|		
|Occupant	  	| `Δ.By.Space.Occupant(param)`  | Gets all building elements with given number of occupants   			| `40`			|
|Department	  	| `Δ.By.Space.Department(param)`   		| Gets all building elements in given department names    	| `Educational`|
|Room	  		| `Δ.By.Space.Room(param)`   		| Gets all building elements in given room names     	| `Bedroom`	|
|RoomNo  		| `Δ.By.Space.RoomNo(param)`   		|Gets all building elements in given room numbers    	| `205`		|
|RoomId	  		| `Δ.By.Space.RoomId(param)`   		| Gets all building elements in given Room Ids    	| `538389`	|
|Height	  		| `Δ.By.Space.Height(param)`   		| Gets all building elements in spaces with given hight   		| `3 m`		|
|Area	  		| `Δ.By.Space.Area(param)`   		| Gets all building elements in spaces with given area    	| `24 m2`	|
|Perimeter  	| `Δ.By.Space.Perimeter(param)`   		| Gets all building elements in spaces with given perimeter   | `45 m`|
|Volume	  		| `Δ.By.Space.Volume(param)`   		| Gets all building elements in spaces with given volume   	| `5 m3`|


#### Δ.By.System

|`Name`	| `Command` 					| `Description`                  	|`sample input`    	|
|---------------| --------------------------| -----------------------------	|----------------------------	|
|System 	  	| `Δ.System(param)`    		| Gets all building elements in given system names 	|`{Area:[20,30],Volume:[5,6]}`
|Name	  		| `Δ.By.System.Name(param)`   	|  Gets all building elements in given system names  	| `2 m`			|
|Type	  		| `Δ.By.System.Type(param)`   		|  Gets all building elements in given system types  		| `20 m2`	|
|Classification	| `Δ.By.System.Classification(param)` | Gets all building elements in given system classifications   		| `20 m2`	|
