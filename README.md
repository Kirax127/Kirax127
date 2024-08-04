import pygame
import random

# Initialize Pygame
pygame.init()

# Set up the display
width, height = 800, 600
screen = pygame.display.set_mode((width, height))
pygame.display.set_caption("Musical Rhythm Cooking Game")

# Game loop
running = True
while running:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False
    
    # Game logic here
    
    # Drawing code here
    screen.fill((255, 255, 255))  # Fill screen with white
    
    # Update the display
    pygame.display.flip()

# Quit the game
pygame.quit()
