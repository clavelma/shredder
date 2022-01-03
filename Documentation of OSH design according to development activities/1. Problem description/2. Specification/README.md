# **Specification**

*The specification consists in describing the product with a "black box" external view to capture the intermediate technical objects (stakeholders, external interfaces, services, and constraints) that serve to, *in fine*, elucidate the product requirements.*

## **How to document the specifications?** 
  
## **1. Stakeholders:**

### Template of stakeholders
  
   * Clients
   * Users
   * Partners
   * Media
   * European standards
   * Environment
  
  ![Image of stakeholder diagram for template](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Stakeholder%20diagram%20for%20template.jpg)
  
  *The link below can be used to define the stakeholders of your project/product.*
  
  <a href="https://app.diagrams.net/?libs=general#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FStakeholder%20diagram%20for%20template.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/?libs=general#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FStakeholder%20diagram%20for%20template.png">Edit in diagrams.net</a>
  
## **2. External interfaces**

*The image below shows the external interfaces of  ADD-ONS of XYZ cargo as a graph*

![Image of External interfaces of XYZ cargo-ADD ONS](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/External%20interfaces%20of%20XYZ%20Cargo%20ADD-ONS.jpg)

<a href="https://app.diagrams.net/?libs=general#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces.png">Edit in diagrams.net</a>
</details>

### Template of external interfaces
   
   * Clients
       * needs
   * Users
       * use
       * repaire
   * Partners
       * data
       * technical support
   * Media
       * reproduce
       * data
   * European standards
       * laws
       * norms
       * security
   * Environment
       * supply
       * adapt
       * reuse
       * technical support
  
 ![Image of stakeholder diagram for template](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/External%20interfaces%20for%20template.jpg)
  
   *The link below can be used to define the external interfaces of your project/product.*
  
  <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces%20for%20template.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FExternal%20interfaces%20for%20template.drawio">Edit in diagrams.net</a>

## 3. Service *(synonyms: external function, capability)* 
<details>
  <summary>Click to see the guideline!</summary>
  
- **Definition:** *A service is an effect intended by a stakeholder resulting from the interaction of the product with its environment (i.e. what the  product is for).*

- **Comments:**
  - *Services provide users with an exchange value that can be included in an economic system (e.g. airlines buy flight hours).*
  - *Services are intended effects that can be observed from outside the product ("black box" external view), but not from outside an internal component ("white box" internal view).*
  - *Services are defined in a solution neutral-way.*
  - *Services can be stated as follows: The [Product] shall enable [Stakeholder] [Action verb] (e.g. The product shall enable end-user to clean its teeth)*
  - *we often reason in terms of action verbs to communicate expected behaviors, so it would be nice to be able to search designs with action verbs*
</details>

<details>
  <summary>Click to see the example!</summary>
  
 ```
  What does contain the minimum documentation of the service to stakeholders?
  
  Example of services for ADD-ONS of XYZ Cargo
  
    - The ADD-ONS shall enable the food producer to store food
      - 1.1 solid (10 kilos)
      - 1.2 liquid (5 litrs)
    - The ADD-ONS shall enable the food producer to heat food
      -  2.1solid (150 deg Celcius)
      - 2.2 liquid (80 deg Celcius)
    - The ADD-ONS shall enable the food producer to cool down food for 4 hours
      - 3.1 solid (6 deg Celcius)
      - 3.2 liquid (6 deg Celcius)
      
    - ...
  ```
 </details>

### Template of services
  
   * Services to clients
       * The shredder shall enable the ABS&PLA plastic from 3D printing scraps to be reduce into big or medium chips
       * The shredder shall enable the thermoformable plastic from thermoformable plastic plate scraps to be reduce into big or medium chips
   * Services to users
       * The shredder shall enable the plastic from user's personal collect to be reduce into big or medium chips
   * Services to partners
       *  The shredder shall enable the plastic from partner's personal collect to be reduce into big or medium chips
   * Services to media
       * x
   * Services to european standards
       * x 
   * Services to environment
       * x 

## 4. Constraint *(Synonyms: non function requirement)*
<details>
  <summary>Click to see the guideline!</summary>
  
- **Definition:**  *A constraint is a choice that makes certain designs "not allowed" or inappropriate for their intended use.*

- **Comments:**

  - *The constraint is a restriction, limit, or regulation imposed on a product.*
  - *There are two kinds of constraints: input constraints and system constraints.* 
    - *Input constraints are imposed as part of the design specifications.*
    - *System constraints are constraints imposed by the system in which the design solution must function.*
 </details> 
 
 <details>
  <summary>Click to see the example!</summary>
  
   ```
  What does contain the minimum documentation of the constraints?
  
  Example XYZ Cargo ADD-ONS, constraints for maker of ADD-ONS
  
   - User should be able to dismantle ADD-ONS with a maximum one wrench and one screwdriver 
   - Users should be able to customize the modules of ADD-ONS to fit their use. 
   - The ADD-ONS should enable the users to do the assembly of components in a short time (10 minutes) and the maker shall select the resistance material for using ADD-ONS in different weather conditions. 
   - ADD-ONS should be dismantled for recycling purposes.
   - ...

  ```
</details>

### Template of constraints
  
   * Constraint 1
   * ...
     
  
## **5. Requirement**

<details>
  <summary>Click to see the guideline!</summary>
  
- **Definition:** *A requirement is a formal statement that specifies when condition C is true, property P of object O is actual and its value shall belong  to domain D.*

- **Comments:**
  -  *The minimum set of independent requirements can completely characterize the needs of the product in the functional domain.*
  -  *Functional requirements describe qualitatively the system functions or tasks to be performed in operation.* 
  -  *Requirement can state as follows: The [stakeholder] need [Property] [object] [Action verb]  at [Condition]* 
 </details>
 
 <details>
  <summary>Click to see the example!</summary>
  
  ```
  Example of the functional requirement that ADD-ONS of XYZ cargo provides for the food producers, as a stakeholder, to preserve the quality of food.
 
  In this example, we assumed a refrigerator on the ADD-ONS could help the food producers to cool down and preserve the temperature of food. 
  
  So, we defined some  functional requirements (FR) based on this assumption that consist:
 
    - FR1: To maintain the quality of food, the food producer needs to main the material at cold temperature (between 3 °C and 10 °C) for short-term preservation (3h) or long-term preservation (24h).
    - FR2: ADD-ONS shall fix the internal ADD-ONS temperature for 7 °C.
    - FR3: To create a cold ambient in the cooling down system, the ADD-ONS shall compress the low temperature and pressured gas to start the cooling cycle.
    - FR4: the cooling down system shall control the pressure of exit hot gas 
    - FR5: the hot and pressured exit gas needs to meet the cooler external ambient temperature to become a liquid.
    - ...
    
  ```
 </details>
 
 ### Template of requirements
    
   * Requirement 1
   * ...
