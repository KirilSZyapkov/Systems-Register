# Systems-Register

You will be given a register of systems with components and subcomponents. You need to build an ordered database of all the elements that have been given to you. 

The elements are registered in a very simple way. When you have processed all of the input data, you must print them in a specific order. For every System you must print its components in a specified order, and for every Component, you must print its Subcomponents in a specified order. 

The Systems you’ve stored must be ordered by amount of components, in descending order, as first criteria, and by alphabetical order as second criteria. The Components must be ordered by amount of Subcomponents, in descending order. 

The input comes as array of strings. Each element holds data about a system, a component in that system, and a subcomponent in that component. If the given system already exists, you should just add the new component to it. If even the component exists, you should just add the new subcomponent to it. The subcomponents will always be unique.
