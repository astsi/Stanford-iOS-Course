# Stanford-iOS-Course
The code created by following the Stanford SwiftUI Course

## Video 1 - Comments and notes:

### Language related terms:
- @main stands before the main program, and after the include section in the code (StanfordSwiftUIApp.swift).

### The lego metaphor:
- ZStack/VStack - a bag of legos 
- ContentView - parts made out of legos
- The returning value of var body: some View - a lego brick (different shapes and sizes)

### Manipulating a shape:
- outlining a shape using .stroke() - use only on shapes
- using a .fill() to fill the shape
- text cant be stroked - it’s not a shape

### Modifiers:
- Adding new modifiers in the inspector section
  -  use the add modifier search field - click to find the one you want to use
- You can add modifiers to the ZStack/VStack
- ZStack/VStack can have two arguments 
  - a default argument named content: (contains all the lego bricks)
  - alignment (.top, .bottom …) - defines how the lego bricks inside the stack are aligned 

