#!/bin/bash

echo "Updating package list..."
sudo apt update

apps=(
    "neofetch"
    "nmap"
    # Add more applications here
)

for app in "${apps[@]}"; do
    echo "Installing $app..."
    sudo apt install -y "$app"
done

echo "All applications have been installed."
