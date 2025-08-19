recommendations = """
PARAMETER CONTROL GUIDE

🎛️ DAMPING COEFFICIENT (α):
• Slow motion: α = 0.005 - 0.02
• Medium speed: α = 0.05 - 0.1  
• Fast damping: α = 0.2 - 0.5

🧲 FIELD STRENGTH (H):
• Weak field: H = 0.1 - 0.5
• Normal field: H = 0.8 - 1.5
• Strong field: H = 2.0 - 10.0
(Higher H = faster precession)

📐 INITIAL ANGLE:
• Small perturbation: 10° - 30°
• Medium displacement: 45° - 90°
• Large displacement: 120° - 170°
(Larger angle = longer damping)

⏱️ TIME PARAMETERS:
• Time step: dt = 1e-5 to 1e-4
• Duration: 2-10 seconds for slow
• Duration: 0.5-2 seconds for fast

🎯 FOR SLOW VISUALIZATION:
α = 0.01, H = 0.8, angle = 90°
dt = 1e-4, duration = 5 seconds
"""
