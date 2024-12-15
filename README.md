# Plastic-Bottle
   IMG-20241215-WA0009.jpg
 Plastic Bottle Design in CATIA V5

This repository contains a plastic bottle design created in CATIA V5. The project includes both the 3D model (`.CATPart` file) and a 2D drawing (`.PDF`/`.PNG` files).

VID-20241215-WA0004

## Design Process

### Step 1: Creating the Base Shape
- **Goal**: Start by creating the basic shape of the bottle using a 3D sketch.
- **Action**: 
  - Open a new `.CATPart` document.
  - Create a **profile** sketch in the **XY plane** representing the cross-section of the bottle.
  - Use the **Revolve** feature to create the bottle’s cylindrical shape.

### Step 2: Adding the Neck and Thread
- **Goal**: Create the bottle’s neck with threads.
- **Action**: 
  - Create a **sketch** for the neck’s cross-section (small cylinder).
  - Use **Pad** to extrude the neck.
  - Add a **Thread** feature for the screw cap.

### Step 3: Creating the Bottom
- **Goal**: Design the bottle’s bottom to provide support.
- **Action**: 
  - Create a **sketch** for the bottom.
  - Use **Pocket** to cut the bottom profile into the bottle’s base.

### Step 4: Adding Details
- **Goal**: Add other details like ribs or embossed logos.
- **Action**:
  - Create additional **sketches** and **pockets** to add ribs for strength.
  - For logo, use **Embossing**.

### Step 5: Final Assembly
- **Goal**: If the bottle has multiple parts (e.g., cap), create an assembly.
- **Action**: 
  - Create a new **.CATProduct** file.
  - Insert the bottle part and the cap as components.
  - Apply **Assembly Constraints** to position the parts correctly.
