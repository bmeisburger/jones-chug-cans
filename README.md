# Jones Beer Bike Chug Cans

This repo contains the 3D files for the chug cans created by Ben Meisburger for the 2024 Jones Chug Team. The following is a step-by-step guide to construct additional cans and tips for inspection.

## Printing:

I printed 8 complete cans on two Bambu Labs X1C with little hassle. I was able to tile 7 caps/mouthpieces per print with some creativity. Each print took < 6 hours. The mouthpiece.stl and cap.stl files should be ready to print. If changes need to be made to the file, use the chug-can.f3d and modify parameters as needed (e.g., tube wall thickness, mouthpiece hole size, etc.).

I used the following print settings:

1. Material: Matte white PLA
2. Orientation: Both cap *and* mouthpiece should be printed in their native orientation. The mouthpiece should not require any supports (you may have to manually disable them). The cap will require supports. The native orientation means the top (visible) part of the cap will have a pretty surface. The inside is serviceable and does not appear to impact performance in any way
3. Supports: Only the cap should require supports. Use normal supports (they seem to remove more readily than tree supports)
4. Strength: Increase the number of wall loops from 2 to 6
5. Layers: 0.2mm layer height. All other parameters were left to default
6. Brim: The mouthpiece has minimal bed contact area, so increase the brim to 5-10mm. This fixed a recurring delamination problem during the print

I also tested prototypes using PETG for increased impact resistance, but the supports for the cap were too difficult and messy to remove.

## Assembling:

1. Cut acrylic tubing to length. We used [this](https://www.usplastic.com/catalog/item.aspx?itemid=39379) schedule 40 2" acrylic tubing. The exact length to be cut is an iterative process. There are negative bodies in the chug-can.f3d file that can give you a rough estimate of the volume contained by the mouthpiece and cap (if the model is changed). For the existing mouthpiece.stl and cap.stl, I used 11.45" of tubing per men's can, and 7.55" of tubing per women's can. This should *only* be used as a starting point. To determine your correct length, cut the tubing ~0.25" in excess, assemble the complete can *without* sealant, fill with water, and weigh the water contained. You can easily determine the correction by calculating the volume per unit length of the tube and trimming to fit. It should be noted that even slight changes in the shape, diameter, wall thickness, and length of the tube has sizeable impacts on the total volume. I recommend using extra long calipers to create repeatable cut lines to +/-0.01". I was able to fit each chug can to +0.1/-0 oz without much difficulty. This seems like a reasonable target for precision.
2. Deburr inside and outside edges of the cut tubing ends.
3. Center punch cap holes: assemble cap on tube (it should be a tight fit without slop), find a transfer punch that is a snug fit with the finger holes and use the finger holes as a guide to mark where a hole must be drilled through one side of the acrylic tube.
4. Drill the cap holes. It is helpful to use V-blocks to ensure precise placement of the holes. Using a transfer punch as described above should make aligning the holes in the tube with the holes in the cap a simple task.
5. Deburr the drilled holes.
6. Glue the cap by first applying a film of silicone sealant to the *inside* of the 3d print flange. Ensure glue completely surrounds both finger holes, or there will be leaks. Push the tube into the cap. Wipe away excess glue using q-tips inserted into the finger holes. While cleaning the sealant this way is slightly tedious, the alternative of applying glue to the tube and pressing the cap onto the tube will cause glue to build up on the tube and lead to a messy final product.
7. Glue the mouthpiece in a similar fashion. The squeeze out can be cleaned by wiping a gloved finger around the inside joint between the mouthpiece and the tube.

## Inspection

As of 2024, the official Beer Bike rules state that a chug can must hold 24 oz of water (or 12 oz for women's cans). It does not state 24 *fluid* oz. This is a notable distinction because 24 fl oz of water weighs 25.04 oz. The chug inspectors may bring a measuring cup (or some other volume-measuring device) for the inspection. Since these chug cans are designed to contain 24 oz of water (which is less volume than 24 fl oz), you must bring a scale of some type to prove that the water in the cans meets the weight requirement. It might be easier to simply provide the scale for the inspectors to use than explain the difference between fluid oz and oz measurements.
