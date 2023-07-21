# Priyanshu-Gupta
My House
import random

def get_house_routine():
  """Returns a list of tasks to be completed for the house routine."""
  tasks = [
      "Make the bed",
      "Clean the kitchen",
      "Do the laundry",
      "Take out the trash",
      "Sweep the floor",
      "Mop the floor",
  ]
  return random.sample(tasks, len(tasks))

def print_house_routine():
  """Prints the list of tasks to be completed for the house routine."""
  tasks = get_house_routine()
  print("Here is your house routine:")
  for task in tasks:
    print(task)

if __name__ == "__main__":
  print_house_routine()
![2c7ed60a-f566-4a5b-a84e-b34dd47fc72e](https://github.com/mrpriyanshu5/Priyanshu-Gupta/assets/140094235/1a920282-98ef-42c9-8b63-3f94f4b68ac9)
