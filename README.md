# rec-room-obfstuff

instantiate lives in RecRoom.Networking.Instantiation.Runtime.dll, RecRoom.Networking
params are (System.String, UnityEngine.Vector3, UnityEngine.Quaternion, UnityEngine.Vector3, RecRoom.Foundation.ViewId, RecRoom.DataLayer.CreationInstantiationParameters, System.Boolean)
parameters of method below are (RecRoom.Networking.InstantiateParameters&)
above: (System.String, UnityEngine.Vector3, UnityEngine.Quaternion, System.Object[])

get health's:
"Assembly-CSharp.dll", "", "DownButNotOutRespawnCondition", ".ctor", 2
System.Void .ctor(System.Object, System.IntPtr)

now under that you'll see a method with the param (System.Action<RecRoom.Networking.DataTypes.JNIVCIZIPSX>) might not be JNIVCIZIPSX depending on the build
find 5 System.Int32 OYZMUFUBIWD() undere that no params OYZMUFUBIWD is not gonna be the name since this is probably a different build

 getmasterclient - search (System.Func<System.String,System.String>) last result, count down 11

set master
     search term -> "RecRoom.Networking.Instantiation.Runtime.dll", "RecRoom.Networking"
     find out what NAME is. just search somethinng like get_NetworkedPlayer you'll see 	RecRoom.Networking.DataTypes.JNIVCIZIPSX JNIVCIZIPSX will be different.
     System.Boolean NAME1(RecRoom.Networking.DataTypes.NAME) 
     NAME is obfuscated, just try a few of these until they're right
     1 param
     RecRoom.Networking.DataTypes.JNIVCIZIPSX (last result)
     MNBQIABPYXS is the name (not for all builds)
     not last result, but go to last result then
     System.Boolean with 1 param(RecRoom.Networking.DataTypes.name)
     inside "RecRoom.Networking.Instantiation.Runtime.dll", "RecRoom.Networking",
     looks like: 	System.Boolean EKOJRVGZPFD(RecRoom.Networking.DataTypes.JNIVCIZIPSX) (different names though , VJZKYKLEVCC , JNIVCIZIPSX) 
     next 2 above it are both RecRoom.Networking.DataTypes.
     then 2 Booleans above that

     Playerlist
     search "RecRoom.Networking.Instantiation.Runtime.dll" then search System.Collections.Generic.IReadOnlyList<, there is 2
     // System.Collections.Generic.IReadOnlyList<RecRoom.Networking.DataTypes.JNIVCIZIPSX> YENVYXZQREK(System.Boolean)
     // 	System.Collections.Generic.IReadOnlyList<RecRoom.Networking.DataTypes.JNIVCIZIPSX> ZXOGAFLDDTP(System.Boolean)
     // above them are: 	RecRoom.Networking.DataTypes.JNIVCIZIPSX ENKLWSKEEBX(System.Int32)


     // getExecParams 
     // search for "Assembly-CSharp.dll", "RecRoom.Systems.PlayerRoles", "PlayerRoomRoleManager", ".ctor", 0 params
     // 	System.Void .ctor()
     // below that is Circuits.Dynamic.Api.AQJBJOMITDO KBFPZLHJWJV() (again the names might be different AQJBJOMITDO, KBFPZLHJWJV)

     
     
     
     
     
