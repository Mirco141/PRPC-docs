---
icon: forward
---

# Procedures

Below we will explain some procedures that repeat during the RP. Apply them whenever necessary.

<p align="center"><mark style="color:red;"><strong>Remember!</strong></mark></p>

{% hint style="info" %}
You can click on the appropriate button on commands boxes to instantly copy them and paste them in-game!
{% endhint %}

{% hint style="warning" %}
Don't forget to replace square brackets \[] with the content regarding what's specified inside of them!



You should **NOT** type, for example: .....is now at \[High Rock Park's Bunker].<i class="fa-xmark" style="color:red;">:xmark:</i>

You **should** type, for example: ....is now at High Rock Park's Bunker. <i class="fa-check" style="color:green;">:check:</i>
{% endhint %}

***

## Locations

The President can go everywhere he decides to, but keep in mind that there are some banned locations where he can't go:

* Any safe zone
* Police Department
* Fire Department
* Sheriff's Office
* Gun Store
* Prison
* Any Garage
* High Rock Park watchtower
* Farm silo
* Civilian spawn points

{% hint style="warning" %}
The President **must** stay in a location for at least 5 minutes, and should change every 15 minutes.
{% endhint %}

The first location **must** always be the White House (Hospital).

{% hint style="info" %}
Make sure all players know where the President is at all times, by making frequent "h" type announcements.
{% endhint %}

### Changing location

When a President asks you to change location, make sure that he has passed at least 5 minutes in the current location, and that the location is not banned.

Then, set up a peace timer of 500 seconds which must remain active (repeat the command when it expires) until the President has reached the new location.

{% code overflow="wrap" %}
```
:pt 500
```
{% endcode %}

Then, announce the President changing location via this message:

{% code overflow="wrap" %}
```
:h The President is now going to [location]. Please form a convoy outside [your current location].
```
{% endcode %}

{% hint style="info" %}
You can replace _<mark style="color:$info;">\[location]</mark>_ either with the location's name, or the location's postal code, or both.

Example: _<mark style="color:$info;">High Rock Park Bunker</mark>_ || _<mark style="color:$info;">Postal Code 709</mark>_ || _<mark style="color:$info;">Housing Suburbs (Postal Code 709)</mark>_
{% endhint %}

Make sure that players are now forming a convoy, and later lead that convoy to its new location. For convoy's formation instructions see the [Convoy's guide](convoy.md) <i class="fa-up-right-from-square">:up-right-from-square:</i>.

***

## When a President dies

Each President has 3 lives. When he dies he loses 1 until he reaches 0 remaining lives.

Each time the President dies, make sure that the kill was valid (all rules were respected, no RDM or such) and if it was valid, announce it to the players via the following message:

```
:h The President [username] has died. He has now [remaining lives]/3 lives remaning!
```

After that, revive the President:

{% code overflow="wrap" %}
```
:heal [username]
```
{% endcode %}

Then announce the following message:

{% code overflow="wrap" %}
```
:h Civilians should now leave this building and start attacking the President again once the peace timer is over.
```
{% endcode %}

Then, set up a 60 seconds (or similar) peace timer to allow everyone to re-organize.

{% code overflow="wrap" %}
```
:pt 60
```
{% endcode %}

Make sure that all civilians leave the building where the President is at, and give time to everyone to organize again. Then the RP will start again.



When the President loses all of his lives there are 2 possibilities:

<details>

<summary>There is a Vice-President</summary>

The President is replaced by the Vice-President, which automatically becomes President. Announce it to the players via the following message:

{% code overflow="wrap" %}
```
:h The President [username] has died. He has lost all of his lives.
```
{% endcode %}

If the Vice-President is online, and accepts to cover the role of President, announce it to the players via the following message:

{% code overflow="wrap" %}
```
:h The new President is now [username].
```
{% endcode %}

The new President will have, again, 3 lives and the procedure will repeat.

{% hint style="danger" %}
Once the Vice-President is elected, there will be no more Vice-President. Even if a player asks you, or the President wants to elect one for himself, **do not allow them to**.
{% endhint %}

If the Vice-President is not online or does not accept to be President, continue to the "There is no Vice-President" option.

</details>

<details>

<summary>There is no Vice-President</summary>

In this case, new elections must be hosted and the roleplay restarts from zero.

Announce it to the players via the following message:

{% code overflow="wrap" %}
```
:h New elections will be hosted at the Police Department's meeting room.
```
{% endcode %}

</details>

***

## Emergency escapes

The President can decide to emergency-escape a location.

He must tell the RP host before doing so (or tell a staff member which will tell the RP host about his decision), and the decision must be approved by the Host.

If approved, the President is authorized to drive away in a vehicle without a fully organized convoy, but he cannot drive for himself, he must have a driver.

{% hint style="info" %}
Players can both not form a convoy at all, or form a un-organized convoy.

This emergency escaping procedure does not have to follow any rules, the President can go anywhere he wants to and can also drive off at whatever speed his driver prefers to drive at. He can take all roads he want to reach his destination, and those roads do not have to be blocked.
{% endhint %}

If you're the host, after approving the escape, announce the following message:

{% code overflow="wrap" %}
```
:h The President is making an emergency escape!
```
{% endcode %}

Spectate the President while driving, see where he stops, and then announce the following message:

```
:h The President has made an emergency escape and is now at [Location].
```
