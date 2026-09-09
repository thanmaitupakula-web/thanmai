# Thanmai - Industrial Pick and Pack Robot
## B.Tech 2nd Year Robotics Project

A modified commercial robot platform adapted for autonomous pick-and-pack operations. This is a team capstone project focusing on robotics, control systems, and automation.

**Team Members:** 5  
**Academic Year:** B.Tech 2nd Year  
**Department:** Robotics/Mechanical Engineering  

---

## 📋 Project Overview

Thanmai is an industrial pick-and-pack robotic system designed to:
- Pick objects from source locations using computer vision
- Place objects at target destinations with precision
- Operate autonomously in warehouse/manufacturing environments
- Integrate commercial robot hardware with custom control software

### Key Objectives
- [ ] Modify commercial robot for pick-and-pack operations
- [ ] Implement vision-based object detection
- [ ] Develop motion planning and control algorithms
- [ ] Create user interface for task programming
- [ ] Validate system performance and safety

---

## 📁 Project Structure

```
thanmai/
├── docs/                      # Project documentation
│   ├── PROJECT_REPORT.md      # Main project report
│   ├── ARCHITECTURE.md        # System design document
│   ├── HARDWARE_SPECS.md      # Hardware and specifications
│   ├── API.md                 # Software API documentation
│   ├── SETUP.md               # Installation and setup guide
│   └── team/                  # Team documentation
│       ├── ROLES.md           # Team member roles
│       └── TIMELINE.md        # Project milestones
├── hardware/                  # Hardware-related files
│   ├── CAD/                   # 3D models and drawings
│   ├── schematics/            # Electrical schematics
│   ├── BOM.xlsx               # Bill of Materials
│   └── MODIFICATIONS.md       # Commercial robot modifications
├── firmware/                  # Embedded controller code
│   ├── src/                   # Source code
│   ├── include/               # Header files
│   └── Makefile               # Build configuration
├── software/                  # High-level software (ROS/Python)
│   ├── src/                   # Main algorithms
│   ├── launch/                # Launch configurations
│   ├── config/                # Parameter files
│   └── README.md              # Software setup
├── vision/                    # Computer vision module
│   ├── detection/             # Object detection
│   ├── calibration/           # Camera calibration
│   └── datasets/              # Training data
├── tests/                     # Testing and validation
│   ├── unit_tests/            # Code testing
│   ├── integration_tests/      # System testing
│   └── TESTING_REPORT.md      # Test results
├── examples/                  # Example programs
│   ├── simple_pick_place.py   # Basic operation
│   └── batch_operations.py    # Advanced scenarios
├── results/                   # Experimental results
│   ├── performance_data/      # Metrics and measurements
│   └── videos/                # Demo videos
├── CONTRIBUTING.md            # Contribution guidelines
├── README.md                  # This file
└── .gitignore                 # Git ignore file
```

---

## 🔧 Quick Start

### Prerequisites
- Commercial robot (model: [TBD])
- [List of required software/tools]
- [Hardware requirements]

### Hardware Setup
1. Follow `hardware/MODIFICATIONS.md` for robot modifications
2. Install gripper and end-effectors
3. Set up camera and sensor systems
4. Verify all electrical connections

### Software Installation
```bash
# Clone repository
git clone https://github.com/thanmaitupakula-web/thanmai.git
cd thanmai

# Install dependencies
pip install -r requirements.txt

# Build firmware (if applicable)
cd firmware
make build
make flash

# Run software
cd ../software
python main.py
```

### Running a Simple Demo
```bash
python examples/simple_pick_place.py
```

---

## 📊 Project Milestones

| Milestone | Target Date | Status |
|-----------|------------|--------|
| Hardware Setup & Modifications | [TBD] | ⏳ |
| Basic Arm Control | [TBD] | ⏳ |
| Vision System Integration | [TBD] | ⏳ |
| Motion Planning Implementation | [TBD] | ⏳ |
| Full System Integration | [TBD] | ⏳ |
| Testing & Validation | [TBD] | ⏳ |
| Final Report & Demo | [TBD] | ⏳ |

---

## 👥 Team Members & Roles

See [docs/team/ROLES.md](docs/team/ROLES.md) for detailed team member responsibilities.

---

## 📚 Documentation

- **[PROJECT_REPORT.md](docs/PROJECT_REPORT.md)** — Comprehensive project report
- **[ARCHITECTURE.md](docs/ARCHITECTURE.md)** — System design and architecture
- **[HARDWARE_SPECS.md](docs/HARDWARE_SPECS.md)** — Hardware specifications
- **[SETUP.md](docs/SETUP.md)** — Installation and setup guide
- **[API.md](docs/API.md)** — Software API documentation
- **[TESTING_REPORT.md](tests/TESTING_REPORT.md)** — Test results and validation

---

## 🧪 Testing

Run test suite:
```bash
cd tests/
python -m pytest unit_tests/
python -m pytest integration_tests/
```

---

## 📈 Performance Metrics

See [results/performance_data/](results/performance_data/) for detailed metrics including:
- Pick success rate
- Cycle time per pick-place
- Accuracy measurements
- Power consumption

---

## ⚠️ Safety Notice

- Always keep emergency stop accessible
- Verify gripper force limits before operation
- Ensure work area is clear of obstacles
- Follow all safety protocols in [docs/SAFETY.md](docs/SAFETY.md)

---

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how team members can contribute.

---

## 📞 Contact & Support

For questions or issues:
- Create a GitHub Issue
- Contact project lead: [TBD]
- Check documentation first: see [docs/](docs/)

---

**Last Updated:** September 9, 2026  
**Project Status:** In Progress
