> BLoC => Business Logic Compoment

# Basic Knowledge

## State

State is the data your application is currently showing

## Event

Event is any action that is detected by application. Typically, it's a user action like clicking on botton

## Stream

Stream can be considered as a medium through which data travels. Stream is like **pipe**, and the data traveling through is like water.

- To control the **Stream**, we usually use a **StreamController**.
- To insert something into the **Stream**, the **StreamController** expose the "entrance", called a **StreamSink**, accessible via the **sink** property.
- the way out of the **Stream**, is exposed by the **StreamController** via the **stream** property

## Sink

Sink can be considered as the point where you receive or consume data from stream.

# BLoC

