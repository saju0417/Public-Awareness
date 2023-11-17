import csv

# Function to display public awareness information
def display_public_awareness(survey.csv):
    try:
        with open(servey.csv, mode='r') as file:
            reader = csv.DictReader(file)
            for row in reader:
                print(f"Topic: {row['Topic']}")
                print(f"Description: {row['Description']}\n")
    except FileNotFoundError:
        print(f"The file {servey.csv} does not exist.")
    except Exception as e:
        print(f"An error occurred: {e}")

# Main program
if __name__ == "__main__":
    file_name = "public_awareness.csv"
    display_public_awareness(servey.csv)
