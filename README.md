# Valentine's Day Card Generator

def generate_valentines_card(sender, recipient):
    message = (
        f"Dear {recipient},\n\n"
        "I wanted to take this moment on Valentine's Day to express my feelings for you.\n"
        "You mean the world to me, and I am incredibly grateful to have you in my life.\n"
        "Your love and support have brought me immense joy and happiness.\n"
        "On this special day, I want to remind you of how much I care for you.\n"
        "Will you be my Valentine?\n\n"
        "With all my love,\n"
        f"{sender}"
    )
    return message

def main():
    sender_name = input("Enter your name: ")
    recipient_name = input("Enter your girlfriend's name: ")
    
    valentines_message = generate_valentines_card(sender_name, recipient_name)
    print("\n\nGenerated Valentine's Day Message:\n\n")
    print(valentines_message)

if __name__ == "__main__":
    main()
