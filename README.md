# Mobirise Sample Project

Download this Zip file and use Mobirise desktop to open the Project. You need have the code editor plugin installed / have access to modify the code inside the blocks. 

To integrate HexaEight Sessions in Mobirise, you first need to configure [HexaEight Token Server](https://github.com/HexaEightTeam/HexaEight-Token-Server) and create a new Client and obtain the Client ID. 

The following changes were incorporated in order to enable authentication

1. The script tags are added to the HOME page settings under Inside <head> code
2. There is a empty content6-f tag below the introduction block titled "Authentication demo". If you look at the code using code editor, there are two <divs> added for displaying appname and username
3.  Towards the end of the page you have a custom-script block which contains all the Javascript code for encryption/decryption, protection/dechipher and callback functions.

**Remember to modify the Client ID and tokenserverurl in th custom script code to point to your application.**

Finally Publish the site !!

**This demo sample is part of a [this](https://github.com/HexaEightTeam/session-js-spa-https) repository**
