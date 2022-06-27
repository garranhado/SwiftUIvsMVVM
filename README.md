# Stop using MVVM for SwiftUI

Don’t over-engineering! No suggested architecture for SwiftUI, just MVC without the C.

*Declarative UI does not require MVVM. We are now in an era where declarative UI is commonplace in iOS development.*

*In the field of React/Vue/Flutter, which also uses declarative UI, the architecture of MVVM is not adopted, and it seems strange to adopt MVVM only in SwiftUI.*

## Software engineering

Simple software design can only be achieved by really fully understanding the problem First you have to really understand what’s going on, in all its complexities, and then come up with a solution so simple that – in hindsight – it is the obvious way to do it.

- Don't over-engineer your code
- Don't fall into the tutorial trap
- Don't just copy and paste code without understanding it
- Don't blindly follow someone else's strategy
- Avoid sacrificing software design for testability
- Consider mocking only as a last resort

Be careful, in an effort to make code more testable, we can very often find ourselves introducing a ton of new protocols and other kinds of abstractions, and end up making our code significantly more complicated. Follow KISS (Keep It Simple Stupid) principles.

**There's an object for that!**

1. Identify Objects (structs / classes)
2. Identify Tasks
3. Identify Dependencies

- Don’t fight the system
- Don’t literally start with a protocol
- Start with concrete types, generalize when needed
- Avoid unnecessary internal & external dependencies
- Avoid too many layers of abstraction or complexity
- Use nested type for supporting or to hide complexity
- Define constants only where they are necessary (e.g. PI, notification names)
- Prioritize code simplicity, readability and independence

## Slides

![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.001.png)
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
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.012.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.013.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.014.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.015.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.016.png)
![](https://raw.githubusercontent.com/garranhado/SwiftUIvsMVVM/main/SwiftUIvsMVVM.017.png)
