# Stop using MVVM for SwiftUI

Don’t over-engineering! No suggested architecture for SwiftUI, just MVC without the C. On SwiftUI you get extra (or wrong) work and complexity for no benefits. Don’t fight the system.

## Software engineering

Simple software design can only be achieved by really fully understanding the problem First you have to really understand what’s going on, in all its complexities, and then come up with a solution so simple that – in hindsight – it is the obvious way to do it.

- Don't over-engineer your code
- Don't fall into the tutorial trap
- Don't just copy and paste code without understanding it
- Don't blindly follow someone else's strategy
- Avoid sacrificing software design for testability
- Consider mocking only as a last resort

Be careful, in an effort to make code more testable, we can very often find ourselves introducing a ton of new protocols and other kinds of abstractions, and end up making our code significantly more complicated. Don't go Clean / SOLID anti-patterns, be an OOP / POP engineer.

In the agile world use Feature Driven Development (FDD) and avoid as you can Test Driven Development (TDD) / Extreme Programming (XP). 

**There's an object for that!**

1. Identify Objects
2. Identify Tasks
3. Identify Dependencies

- Don’t fight the system
- Don’t literally start with a protocol
- Avoid unnecessary internal & external dependencies
- Avoid too many layers of abstraction or complexity
- Use nested type for supporting or to hide complexity

## Slides

![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.002.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.003.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.004.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.005.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.006.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.007.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.008.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.009.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.010.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.011.png)
