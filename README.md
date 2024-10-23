# In-Class-Example-Inheritance-and-Access-Modifiers

A toy example of inheritance using Dogs

Animal - Base Abstract class that Dog will be inheriting from

Dog - Has a Dog Class and a Husky Class. Dog inherits Animal, and Husky inherits Dog.

AnimalTester - Basically the same Main method found in Dog, but shows errors thrown due to Access Modifiers

# Running commands

Make sure your current directory in terminal is InheritanceExample. You can check this with the following command:
```bash
# windows
cd

# Mac or Linux
pwd
```

After running the command, you should see a path similar to the following:
```
[Full path]/In-Class-Example-Inheritance-and-Access-Modifiers/InheritanceExample
```

To look at the files, open Program.cs in the Animal, Dog, and AnimalTester folders

To run the files, use one the following commands to see the output:

```bash
# running AnimalTester
dotnet run --project ./AnimalTester
```

```bash
# running Dog
dotnet run --project ./Dog
```