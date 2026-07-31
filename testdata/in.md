# Hello, world!

import {External} from './some/place.js'
import {Chart} from './chart.js'
import population from './population.js'

export const pi = 3.14
export const Local = properties => <span style={{color: 'red'}} {...properties} />

<Chart data={population} label={'Something with ' + pi} />

An <External>external</External> component and a <Local>local one</Local>.

<div className="note">
  > Some notable things in a block quote!
</div>

<Welcome name="Venus" />
<Welcome name="Mars" />

<MyComponent id="123" />

You can also use objects with components, such as the `thisOne` component on
the `myComponents` object: <myComponents.thisOne />

<Component
  open
  x={1}
  label={'this is a string, *not* markdown!'}
  icon={<Icon />}
/>

Two 🍰 is: {Math.PI * 2}

{(function () {
  const guess = Math.random()

  if (guess > 0.66) {
    return <span style={{color: 'tomato'}}>Look at us.</span>
  }

  if (guess > 0.33) {
    return <span style={{color: 'violet'}}>Who would have guessed?!</span>
  }

  return <span style={{color: 'goldenrod'}}>Not me.</span>
})()}

## Anchored heading `{#anchored-heading}`

Mintlify and Docusaurus attach an explicit id to a heading this way. MDX hands
whatever sits in braces to Acorn, and `#anchored-heading` is not an expression.

Handlebars sections are not the same thing, and must be left alone -- the tail
of `{{#client}}` looks like an anchor but splicing a backtick into it breaks
the surrounding expression:

var clients = "Clients:<ul>{{#client}}<li>{{fn}}</li>{{/client}}</ul>";

