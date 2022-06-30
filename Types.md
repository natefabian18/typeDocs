# Setup 
~~I've already done all the hard parts~~\
add these two options to your settings\
![Pastedimage20220624121607.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624121607.png)
# Examples as to why this is useful
## Error checking 
~~(AKA don't be dumb)~~
Note: a lot of these are directly from S9's codebase not madeup examples
### customer-controller.js 
#### improper use of the new keyword
![Pastedimage20220624115709.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624115709.png)
#### Oops wrong caps
![Pastedimage20220624115751.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624115751.png)
#### duplicate properties on an object
![Pastedimage20220624121758.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624121758.png)
### customer.js
#### Passing too many or not needed params
```
let result = await bl.getOverridePassword(req); //unused param


async getOverridePassword(){
	//some code
}
```
![Pastedimage20220624115445.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624115445.png)


## Intellisense everywhere
### jQuery helpers
![Pastedimage20220624115859.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624115859.png)
### kendo helpers
![Pastedimage20220624115918.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624115918.png)
![Pastedimage20220624115946.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624115946.png)

### custom JSDoc hints
#### What did this function do again?
![Pastedimage20220624121017.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624121017.png)
#### ensure type operations are viable
![Pastedimage20220624121314.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624121314.png)

## Exceptions
This type is weird and I cant get it to not error\
//@ts-ignore tells the next line to ignore type checking\
![Pastedimage20220624121505.png](https://raw.githubusercontent.com/natefabian18/typeDocs/main/Types/Pastedimage20220624121505.png)
