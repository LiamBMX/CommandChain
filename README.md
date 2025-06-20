# Command Chain

**Command Chain** is a browser‑based coding game for people looking to learn to code or just have some fun and test there skills! CommandChain spits out a box on a convayor belt and it is your task to use JavaScript styled code to decide how to complete your assigned mission with the code, missions include sorting boxes by weight, color, etc. Boxes are fully random so you must use advanced functions and if statements to determine how to orgamize your Factory!

```js
player.move("right");
player.grabBox();
if (player.box.color === "red") {
  player.sendBox("right");
  player.setStopper(40);
}
```

# Roadmap / Task List
- [ ] Add more levels
- [ ] Add sandbox mode where users can freely build conveyors, sorters, dropoffs, and more.
- [ ] Integrate ollama local AI to help users when they get stuck
- [ ] Add levels and ways to add more than one dropoff where boxes spawn at
- [ ] ReName project (CommandChain sucks)

# Downloading and running locally
Pull the code, install node packages, run dev, if you dont know how to do that use the website, its free :)
