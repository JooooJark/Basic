Console.WriteLine("Inventory:");
                foreach (var item in inventory)
                {
                    Console.WriteLine($"- {item}");
                }
            }
            else if (choice == "3")
            {
                break;
            }
            else
            {
                Console.WriteLine("Invalid choice.");
            }
        }
    }
}
