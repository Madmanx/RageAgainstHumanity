Inventaire 
	Hud 
		Stats UI -> Lvl / Stats / Pv / Exp
		Inventory UI -> Close Inventory ( key button down ) 
	Controller d'item dans item slot
	Sauvegarde des stats et remove des stats
	Tooltips ( fonction d'init chiant, j'ai laissé un bout de code qui aurait du marché et que j'ai du faire a la main ) 
	Buttons pour augmenter les stats apres le passage d'un niveau

Item
	Ajout potion, helmet ( multiples stats ) 
	Test sur enumation en bp avec la rareté qui change la couleur sur le tooltip
	Drop d'item a la mort des ennemy
	Test d'héritage sur le item
	
Rage Controller 
	Open Inventory
	Attack range
	Use potion

Rage Character
	Regen
	Take damage ( event ) linked to Anim Bp 
	Attack enemy  linked to Anim Bp
	Stats 
		-> endurance affecte max pv*
		-> dexterite affect play rate sur attack ( attack speed ) 
		-> force affect dégats

EnemyCharacter
	Init ( test sur des png ) / Unclickable dans intro / reveil apres discussion 101 -> ennemy controller 
		Des liens dans le levels blueprint ( notamment event dispatcher) 
	Take damage ( event ) linked to Anim Bp
	Attack player linked to Anim Bp
	Stats 
		-> endurance affecte max pv
		-> dexterite affecte play rate sur attack animation ( attack speed ) 
		-> force affect dégats
	Mort ( add experience pour le joueur ) 


Enemy Controller
	Attack player on sight ( lache apres une certaine distance , test sur l'ours a l'extérieur )

Animation
	Plusieurs retarget / un notify / un animation bp refait a la main pour l'ours
	
Tp between levels 
	Trigger dans castle map
	On click sur la porte

Destructible -> test dans map castle
	Custom on click et play animation ( pour tester ) 

Extra
	LD un peu sur castle.
	Sequence intro pour tester.





Retour d'apprentissage : 

	Un feedback -> faire découvrir les game instances pour transporter de l'info de scene en scene
	Bug dans la sequence ( différence entre le shot et l'actuel sequence ) 
	Pour les détections utilisé plus de trigger et moins de on click sur les modèles même
