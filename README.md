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
     then 2 Booleans above that. 
     .
	 .
     Playerlist
     search "RecRoom.Networking.Instantiation.Runtime.dll" then search System.Collections.Generic.IReadOnlyList<, there is 2
     // System.Collections.Generic.IReadOnlyList<RecRoom.Networking.DataTypes.JNIVCIZIPSX> YENVYXZQREK(System.Boolean)
     // 	System.Collections.Generic.IReadOnlyList<RecRoom.Networking.DataTypes.JNIVCIZIPSX> ZXOGAFLDDTP(System.Boolean)
     // above them are: 	RecRoom.Networking.DataTypes.JNIVCIZIPSX ENKLWSKEEBX(System.Int32)
     .
	 .
     // getExecParams 
     // search for "Assembly-CSharp.dll", "RecRoom.Systems.PlayerRoles", "PlayerRoomRoleManager", ".ctor", 0 params
     // 	System.Void .ctor()
     // below that is Circuits.Dynamic.Api.AQJBJOMITDO KBFPZLHJWJV() (again the names might be different AQJBJOMITDO, KBFPZLHJWJV)
.
.
     trygenquestgift
     - at the end of QuestManager
     you'll see private static void .cctor() { } above that is public void .ctor() { } and above that is trygenquestgift, private void THISISOBFUSCATEDPROBABLY(int32_t THISISOBFUSCATEDPROBABLY) { }
     .
     getcv2manager
     - search for internal static CircuitsV2Manager
     - inside RecRoom.Debugging, UgcWatchdog 
     .
     Fire (for paintball burst gun)
     inside recroom.tools.weapons, BurstFireGun 
     first method with a float arg so like:
     private void THISISOBFUSCATEDPROBABLY(ref float THISISOBFUSCATEDPROBABLY) { }
     .
     set ammunition
     regex for set annunition: protected\s+void\s+[A-Za-z0-9_]+\s*\(\s*(?:ref\s+)?int\s+\w+\s*,\s*(?:ref\s+)?int\s+\w+\s*\)
     below ForceAmmunitionValuesOnSpawn,
     this is what it would look like:
         protected void THISISOBFUSCATEDPROBABLY(int32_t THISISOBFUSCATEDPROBABLY, int32_t THISISOBFUSCATEDPROBABLY) { }

.
get_HasBulletDrop - under set_BlockFireAnimation in rangedwepaon
will look like:
public bool THISISOBFUSCATEDPROBABLY() { }

.
getRangedWeaponScreenToolBehaviorConfig
(this is mostly for stuff like no recoil)
	private RangedWeaponScreenToolBehaviorConfig THISISOBFUSCATEDPROBABLY() { }

so just search RangedWeaponScreenToolBehaviorConfig
now once you find that, search it again or a few more times then you will find the fields, so like public bool applyRecoil;
.

this is probably not obfuscated but Photon Player To String 
public override string ToString() { }
no namespace 
below it is:
	public string THISISOBFUSCATEDPROBABLY() { }
	public override bool Equals(object THISISOBFUSCATEDPROBABLY) { }
 	public override int GetHashCode() { }
  	protected internal void THISISOBFUSCATEDPROBABLY(ref int THISISOBFUSCATEDPROBABLY) { }
   	public bool THISISOBFUSCATEDPROBABLY(Hashtable THISISOBFUSCATEDPROBABLY, Hashtable THISISOBFUSCATEDPROBABLY, THISISOBFUSCATEDPROBABLY THISISOBFUSCATEDPROBABLY) { }
private bool THISISOBFUSCATEDPROBABLY() { }
then it's the end.

.
I will probably add more to this but i think this is enough
 





