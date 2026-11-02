# Steel & Iron

This is my favourite feature of the game — and the one that started the project. Steel and Iron are 2 of the 8 basic metals obtainable in the game. Iron allows you to
pull towards metalic object, while steel allows you to push from them. This effectively creates magnetic flying. Additionaly, Steel Users(Coinshots) can shoot out coins
that can be used either in combat or as weaker anchors for pushing. Iron Users(Lurchers) can pull out these coins from the ground disabling them from being used as anchors.
Additionaly, both Steel and Iron can be flared, consuming large amount of metal fuel in one burst of power. This can be dangerous, however, since there is velocity and fall damage
in the game.

## How does it work?

The general idea is simple. Find a target, "hook" to it, and let go to stop flying. There are 2 targetting modes: Normal and Metalsense.

Normal mode is quite simple: point at a metal object, press Steel or Iron keybind, and you're flying.

Metalsense is more interesting, and generally more useful mode. Metalsense is effectively an xray. It draws lines to all metal targets in range and allows a better selection. This is what it looks like:

<img width="1290" height="783" alt="image" src="https://github.com/user-attachments/assets/9d89b85a-8dc1-4cfe-b0d0-9c5ba9c7076a" />

The big blue circles indicate the selection area. Hover your mouse over them and you can hook to them — even through walls! This makes Steel and Iron much easier to use.

Once you hook the target, you will start accelerating until you hit terminal velocity. At this point colliding can deal damage and leave you ragdolling, so if you want to go fast, get good at dodging.
Steel and Iron movement has a rather high skill ceiling. 

There are modifiers to help with target selection: Rehook and Hook Nearest. While Hook Nearest key is held, holding your Steel or Iron key will automatically hook you to the nearest
metallic object. Rehook works similarly, except it will hook you to the last object you were hooked to. Depending on user settings, rehook can also track the last metallic object you
were standing on, or the last coin you shot.

One of the features that can be exploited is the unique way velocity is calculated in the game. First of all, there is no gravity. This makes movement nicer
and more controllable. Second of all, there is a mechanic called velKill(velocity kill). Let's say you are swinging towards a metal pole, but halfway you decide to let go and hook to a different pole. Some of your
momentum will be killed. This adds extra sense of control to the flight. 0% velKill makes the flying feel loose and uncontrolable. 100% velKill makes it feel overly rigid and stiff. The game uses something in the
middle, although how much velocity is kept depends on your target. The closer the target you're aiming for aligns with the direction you were already moving in, the more of your velocity will be conserved. This also
means that if you overshoot your target and go back, it will kill a lot more of your velocity, letting you make sharper turns. This can be exploited in a technique I call "swing." By approaching your target from the side,
letting go, and rehooking you can swing around your target and make a U-turn.

To watch a video demonstration of Steel and Iron, you can click [here](https://www.youtube.com/watch?v=kgctyPAFINk).
