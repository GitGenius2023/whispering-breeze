import random

# List of whispering sounds
whispers = [
    "ssshhh...",
    "hush...",
    "whisper...",
    "softly...",
    "quietly...",
    "rustle...",
    "sigh...",
    "breathe...",
]

def whispering_breeze():
    # Generate a random whispering sound
    sound = random.choice(whispers)
    return sound

# Example usage
if __name__ == "__main__":
    print("The breeze whispers: ", whispering_breeze())
