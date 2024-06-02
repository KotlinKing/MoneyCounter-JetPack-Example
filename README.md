# Money Counter App : Jetpack Compose

This app doesn't do much but it showcases a very important concept of hoisting a state to a
calling composable. 

## Why do we want to hoist the state? 

The reason why do we want to hoist the state from our main composable to a calling composable
because composable functions needs to be relatively stateless i.e, they shouldn't hold any state
as we want the composable to be flexible so that we can call the composable from anywhere we want.
