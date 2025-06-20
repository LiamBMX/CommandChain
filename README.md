# Command Chain

**Command Chain** is a browser‑based coding game where you write JavaScript‑style scripts to control a factory bot on a grid. Your bot can move, pick up boxes, inspect their properties (color, weight), and route them to the correct conveyor or bin using commands like:

```js
player.move("right");
player.grabBox();
if (player.box.color === "red") {
  player.sendBox("right");
  player.setStopper(40);
}
