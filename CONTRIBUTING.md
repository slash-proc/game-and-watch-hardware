Project Roadmap & Priorities

This project is a fork of the original reverse-engineering effort for the Game & Watch: Super Mario Bros. mainboard by Jake Little/Upcycle-Electronics. Development is prioritized according to the following three-stage roadmap.

1. Phase 1: Functional Parity (Primary Goal)

The immediate priority is completing the reverse engineering of the original hardware.

    Goal: Achieve a schematic and board layout that is functionally equivalent to the original retail unit.

    Focus: Accurate trace routing, component matching, and netlist verification against the original hardware.

2. Phase 2: Repair & Accessibility (Secondary Goal)

Once parity is achieved, the project will branch into a "Repair-Friendly" variant.

    Goal: Enable users to fix broken units using off-the-shelf components.

    Focus:

        Modifying the design to accept generic, readily available LCD screens.

        Swapping proprietary or EOL components for modern equivalents.

        Optimizing the layout for home-printing (PCB fabrication) and manual soldering.

3. Phase 3: Hardware Expansion (Tertiary Goal)

The final objective is a complete modernization of the platform’s core capabilities while maintaining the original form factor.

    MCU Upgrade: Transitioning to a more capable microcontroller to move beyond the original hardware constraints.

    Storage Expansion: Integrating additional storage methods (e.g., microSD) by default into the board design.

    USB Data Integration: Redesigning the USB interface. While the original hardware uses the USB-C port strictly for charging, Phase 3 will aim to connect the data lines to enable firmware management, debugging, and data transfer directly via USB.

How to Contribute

The commits are the primary record of progress. If you wish to contribute:

    Schematic Changes: Ensure any MCU or storage changes are documented with clear netlist labels.

    USB Routing: Special care should be taken with differential pair routing if the design moves toward high-speed USB data.

    Documentation: Updates to the BOM (Bill of Materials) for off-the-shelf alternatives are highly encouraged.

    Issues: Use the issue tracker for documenting specific hardware quirks or netlist discrepancies discovered during testing.

License & Attribution

By contributing, you agree that your changes will be released under the existing MIT License. This project remains a community-driven effort.
