# Task-Fragmentation
AN assignment to test the fragmentation ability of Developers

## My Reasons for Fragmentating it like that

### For Hooks:
- The custom hook `useFetchTransactions` was utilized to encapsulate the logic related to fetching and managing transactions within the application. 

- This approach was chosen for several reasons. Firstly, it promotes code reusability by abstracting away complex transaction-fetching logic into a single, reusable function. 

- Secondly, it enhances code organization and separation of concerns, making the codebase more modular and easier to maintain. 

- Thirdly, it provides a clean and standardized interface for transaction management, reducing duplication of code and ensuring consistency across different components that require similar functionality. 

- Lastly, using a custom hook adheres to best practices in React development, allowing for the encapsulation of stateful logic while ensuring components remain focused on presentation and user interaction.


### For components :

- Component separation enhances code readability and modularity, improving maintenance.
- `BurnBar` manages display and adjustment of burn amount with interactive features.
- `SupplyBar` presents supply statistics visually, like progress bars, for easy comprehension.
- `SupplyLabelList` renders a summary of available supplies with quantity and status details.
- `SupplyTopBar` displays contract information such as expiration dates and renewal status.
