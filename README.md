Aim: This programs main aim is to create a Token
Description: There are a few steps which we would be following in this program to create a token and even burn it:
1.We will have public vriables to store details about our coin.
2.We will have maaping addresses to balances.
3.We will have a mint function which will furthur have two paramaters:an address and a value.The function then increases the total supply by that number and increases the balance of the address by that amount
4.Our contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
5.Lastly, Our burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.
Compiler: We can run this code on remix etherium,org
