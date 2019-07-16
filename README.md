# Odd And Even Number Game

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## About this App

This was a solution for a coding challenge focusing on data binding in Angular
Here are the instructions for the said challenge:

1. Create three new components: GameControl, Odd and Even
2. The GameControl Component should have buttons to start and stop the game
3. When starting the game, an event (holding a incrementing number) should get emitted each second (ref = setInterval())
4. The event should be listenable from outside the component
5. When stopping the game, no more events should get emitted (clearInterval(ref))
6. A new Odd component should get created for every odd number emitted, the same should happen for the Even Component (on even numbers)
7. Simply output Odd - NUMBER or Even - NUMBER in the two components
8. Style the element (e.g. paragraph) holding your output text differently in both components
