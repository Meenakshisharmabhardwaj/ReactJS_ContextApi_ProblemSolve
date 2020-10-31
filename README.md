# ReactJS_ContextApi_ProblemSolve

Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.
Before it we use redux that centralized state global state management at single place 

but Context provide a way pass data through component tree without having to pass props down manually at every level

Sometimes it is known as props drilling 

In Our Example

If we are accessing child component in grandchild component we have to pass the props unneccessarily although it is not being used by tha grandchild 
so in order to avoid it we can use conntext api 
