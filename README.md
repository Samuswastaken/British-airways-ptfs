import os

# Create project folder
project_name = "ptfs_british_airways_site"
os.makedirs(project_name, exist_ok=True)

# HTML content with detailed text
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PTFS British Airways</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background-color: #f0f2f5; margin: 0; padding: 0; }
        header { background-color: #1a2a6c; color: white; padding: 40px 20px; text-align: center; }
        section { padding: 30px 20px; max-width: 800px; margin: auto; }
        h2 { color: #1a2a6c; }
        .discord-button {
            display: inline-block;
            background-color: #5865F2;
            color: white;
            padding: 12px 20px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }
        footer { background-color: #ddd; text-align: center; padding: 15px; margin-top: 40px; }
    </style>
</head>
<body>
    <header>
        <h1>PTFS British Airways</h1>
        <p>Official Discord Community for British Airways in PTFS Roblox</p>
    </header>

    <section>
        <h2>About Us</h2>
        <p>Welcome aboard! We are a passionate group of aviation fans who roleplay as British Airways pilots, crew, and staff in the popular Roblox game <strong>Pilot Training Flight Simulator (PTFS)</strong>.</p>
        <p>Our server offers realistic flight operations, rank progression, training sessions, and exciting events that simulate real-world airline procedures.</p>
    </section>

    <section>
        <h2>How to Join</h2>
        <p>Joining is easy! Just click the Discord invite below and follow the onboarding instructions. You'll be assigned a role and can start flying with us right away.</p>
        <p><a class="discord-button" href="https://discord.gg/YOUR_INVITE_CODE">Join Our Discord</a></p>
    </section>

    <section>
        <h2>Ranks & Roles</h2>
        <ul>
            <li><strong>Cadet Pilot</strong> – Entry-level role for new members</li>
            <li><strong>First Officer</strong> – Earned after completing basic training</li>
            <li><strong>Captain</strong> – For experienced pilots with leadership skills</li>
            <li><strong>Flight Instructor</strong> – Helps train new recruits</li>
            <li><strong>Staff</strong> – Moderators and event organizers</li>
        </ul>
    </section>

    <section>
        <h2>Events</h2>
        <p>We host weekly events including:</p>
        <ul>
            <li>✈️ Group Flights across PTFS maps</li>
            <li>🎓 Training & Certification Sessions</li>
            <li>🏆 Competitions and Challenges</li>
            <li>🎉 Seasonal Celebrations</li>
        </ul>
        <p>Check Discord for the latest schedule!</p>
    </section>

    <footer>
        <p>&copy; 2025 PTFS British Airways Community | Made with ❤️ by aviation fans</p>
    </footer>
</body>
</html>
"""

# Write HTML file
with open(os.path.join(project_name, "index.html"), "w") as file:
    file.write(html_content)

print(f"✅ Website generated in ./{project_name}/ — ready for Vercel deployment!")
