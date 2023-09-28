Directives are Instructions in the DOM

<p appTurnGreen>Receives a green background</p>

@Directive({
selector:'[appTurnGreen]'
})
export class TurnGreenDirective{
...
}

\*ngIf=""

This works by turning on or off a component depending on if the value in ngIf is true or false.
