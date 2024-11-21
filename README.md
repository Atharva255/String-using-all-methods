# String-using-all-methods
###Team 1 Creating String Data Structure Using all Methods
#Objective: The project aims to develop a detailed and versatile implementation of a string data structure in Python, featuring all common and essential string manipulation methods. It will help users understand the internal workings of string operations and provide a foundation for more complex text-based applications.

```mermaid
graph TD
    Start([Start Program]) --> Input[String Input]
    Input --> Menu{Select Operation}
    Menu --> |1. Convert to Uppercase| Uppercase[Uppercase]
    Menu --> |2. Convert to Lowercase| Lowercase[Lowercase]
    Menu --> |3. Reverse String| Reverse[Reverse String]
    Menu --> |4. Check Palindrome| Palindrome[Check Palindrome]
    Menu --> |5. Find Substring| Find[Find Substring]
    Menu --> |6. Replace Substring| Replace[Replace Substring]
    Menu --> |7. Split String| Split[Split String]
    Menu --> |8. Join Strings| Join[Join Strings]
    Menu --> |9. Remove Whitespaces| Remove[Remove Whitespaces]
    Menu --> |10. Check Start/End| Check[Check Start/End]
    Menu --> |11. Exit| Exit[Exit Program]
    Exit --> End([End Program])

