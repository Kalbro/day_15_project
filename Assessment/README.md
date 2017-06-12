## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.

Scope refers to how visible and accessible a variable is.

Hoisting is when the variable declaration is pushed to the top of the scope.

Compartmentalization making a container that is restricted to containing vertain things.

### Provide examples for all three, below:

#### Scope:
function Scope(){
  stuff = "stuff"
  another thing = "another thing"
};

#### Hoisting:
function hoisting() {
    var y;
    bar();
    y = 7;
}

#### Compartmentalization:
function compartment() {
    var z;
    bar();
    z = 7;
}
