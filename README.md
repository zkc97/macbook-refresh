# MacBook Pro 2019: Thermal Refresh & OS Pivot

This project was about saving a 2019 Intel MacBook Pro from its own heat issues. The goal was to clean it out, repaste it, and find an OS that didn't make the fans sound like a jet engine during basic tasks.

## What I Did
- **Deep Clean:** Opened the bottom case and cleared dust from the dual fans and heat sinks.
- **Repaste:** Cleaned off the crusty factory thermal paste and replaced it with fresh high-performance compound.
- **Stability Testing:** Ran load tests to make sure the temps stayed within a reasonable range and didn't thermal throttle.

## The "T2 Chip" Pivot
My original plan was to wipe macOS and install a lightweight Linux distro. I ran into a wall with the **Apple T2 Security Chip**. 

Because the T2 chip handles SSD encryption and hardware drivers, getting Linux to work reliably on this specific model is a massive headache involving kernel patches and driver issues. I decided that forcing Linux wasn't worth the stability trade-off for a machine I actually want to use.

**The Solution:** I pivoted to **macOS Catalina**. It’s much less bloated than modern versions, which keeps the Intel chip from high idle temps and pinned CPU usage.

## What I Learned
- **Hardware Gates:** Hardware security chips like the T2 can completely dictate your software options. You have to check the silicon before you plan the deployment.
- **Thermal Impact:** I saw firsthand how much "factory" thermal paste can degrade over 5-6 years. The repaste alone dropped idle temps significantly.
- **OS Choice:** Sometimes the "best" OS isn't the newest one, but the one the hardware was actually designed to handle efficiently.

## Current Status
The laptop is stable, runs cool, and serves as a secondary machine in my lab.
