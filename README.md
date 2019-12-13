# WorkShop-UseLess

pragma solidity ^0.5.0;

contract newtry  {
 string private name; uint private age;

function setName (string memory newName)  public { name = newName; }   


function getName () public  view  returns(string memory )  {
    return name;
}


}
