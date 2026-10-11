<project>
Build a highly polished interactive 3D web experience called "Tiny Island".

This is NOT supposed to be a conventional game, SaaS product, simulation, dashboard, or productivity tool.

It should feel like a beautiful little digital toy that someone discovers on the internet and immediately starts playing with.

The experience should create the reaction:

"wait... this is so cute"

followed by:

"what happens if I click this?"

The entire point is discovery, physicality, atmosphere, and delight.

Think of it as a miniature living world that the user can poke, drag, throw things into, disturb, grow, manipulate, and explore.

</project>

<creative_direction>

Create a tiny floating island surrounded by a large beautiful ocean.

The island should feel miniature, handcrafted, slightly whimsical, and alive.

The visual direction should be distinctive rather than generic low-poly 3D.

Do not make it look like an AI-generated Three.js template.

Do not make everything perfectly smooth, symmetrical, or procedurally generic.

Give the island personality.

Use a strong visual art direction with:

- beautiful lighting
- atmospheric perspective
- subtle fog
- carefully chosen materials
- convincing water
- soft shadows
- ambient animation
- tiny environmental details
- excellent scale relationships
- tasteful particles
- cinematic composition

The island should look good even when the user does nothing.

IMPORTANT:

You have full creative authority.

The features below are the starting point, not a prison.

If you think of a mechanic, animation, visual effect, secret, environmental detail, sound interaction, creature behavior, or UX improvement that makes the experience substantially better, implement it.

Do not ask me for permission for every creative decision.

Make good decisions yourself.

If a listed feature is technically expensive but there is a significantly better-looking simpler implementation, choose the better implementation.

Optimize for perceived quality rather than feature count.

</creative_direction>

<core_experience>

The user should be able to freely interact with the island.

There should be no complicated onboarding.

Ideally the user opens the page and immediately understands that the world is interactive simply by moving their cursor around and touching things.

Interactions should feel physical.

When something is clicked, dragged, thrown, touched, or disturbed, there should be an appropriate reaction.

Avoid generic UI wherever possible.

Let the world itself communicate what is interactive.

The user should discover mechanics rather than being presented with a huge instruction panel.

</core_experience>

<world>

Build the island with a rich but manageable set of landmarks:

- central grassy island
- small cliffs
- sandy shoreline
- ocean
- several trees
- grass
- flowers
- rocks
- mushrooms
- tiny cabin
- wooden dock
- small boat
- lighthouse or another distinctive landmark
- small pond or stream if appropriate
- scattered environmental objects
- birds
- fish
- butterflies/fireflies
- clouds
- sun
- moon

Do not distribute objects randomly.

Compose the island intentionally.

Create foreground, middle ground, and background layers.

There should be a clear visual focal point while still giving the user things to discover around the island.

Use variation in scale.

Tiny details should reward zooming in.

</world>

<camera>

Create a beautiful cinematic camera.

The default camera should make the island immediately readable and attractive.

Allow natural interaction such as:

- orbiting around the island
- zooming
- slightly inspecting different areas

Camera movement should have smooth damping.

Avoid making the experience feel like a 3D editor.

Consider subtle camera parallax, inertia, and cinematic framing.

The camera should never fight the user.

On mobile, adapt the interaction model appropriately.

</camera>

<water>

Water should be one of the strongest visual elements.

Create convincing stylized water with:

- gentle waves
- reflections
- subtle depth
- shoreline interaction
- foam
- ripples
- splash particles
- underwater color variation
- subtle caustic/light effects if practical

The water should respond to the user.

Clicking/tapping water should create a ripple.

Dropping or throwing objects into water should create a larger splash.

Objects near the water should feel connected to it.

Fish should react to disturbances.

The goal is not physically perfect water.

The goal is water that FEELS alive.

</water>

<physics_and_objects>

Create lightweight physics where it meaningfully improves the experience.

Small objects should be draggable or throwable.

Possible interactive objects:

- rocks
- sticks
- shells
- leaves
- fruit
- coconuts
- small toys
- bottles
- fishing objects

Throwing an object into the ocean should produce:

object trajectory
→ splash
→ ripple
→ particles
→ environmental reaction

Objects hitting the island should behave naturally.

Do not build a complicated physics engine purely for the sake of realism.

Use physics where the player can feel it.

</physics_and_objects>

<wind>

Implement an interactive wind system.

The cursor should influence the direction and strength of wind.

Moving the cursor should cause subtle environmental reactions:

- grass bends
- flowers sway
- tree branches move
- leaves fly
- particles drift
- clouds slowly move
- boat gently rocks
- water surface responds

Fast cursor movement can produce stronger wind.

The effect should be beautiful rather than exaggerated.

Consider allowing the user to "push" lightweight objects with the cursor.

This should be one of the signature interactions.

</wind>

<weather>

Create an environmental weather system.

At minimum support:

- sunny
- cloudy
- rain
- storm
- night

If technically practical, also support:

- fog
- snow

Weather should change the entire atmosphere rather than merely spawning particles.

For example:

RAIN:

- clouds gather
- rain begins
- lighting becomes softer/darker
- water becomes more active
- puddles appear
- plants react
- fish become more active
- tiny droplets appear on appropriate surfaces

STORM:

- stronger wind
- larger waves
- darker clouds
- lightning
- trees react
- birds disappear

NIGHT:

- moon appears
- stars appear
- fireflies appear
- cabin lights turn on
- lighthouse activates
- ocean becomes darker
- reflections change

Make transitions gradual and beautiful.

</weather>

<day_night_cycle>

Allow the user to influence time.

The sun/moon should move naturally.

Possible interaction:

drag the sun across the sky.

As time changes:

- lighting changes
- shadows move
- sky changes
- colors change
- stars appear
- moon appears
- fireflies emerge
- cabin lights activate
- lighthouse activates
- animals change behavior

The transition from sunset to night should be especially beautiful.

Do not make it feel like a settings slider.

It should feel like manipulating the world itself.

</day_night_cycle>

<plants>

Allow the user to interact with vegetation.

Possible interactions:

- plant seeds
- water plants
- touch flowers
- disturb grass
- collect fruit
- shake trees

Plants should have small reactions.

For example:

water seed
→ soil darkens
→ sprout appears
→ plant grows
→ flower opens

Do not make this a farming simulator.

Keep it playful and visual.

</plants>

<animals>

Populate the island with small creatures.

Possible creatures:

- birds
- fish
- butterflies
- crabs
- rabbits
- frogs
- fireflies

They should have simple autonomous behavior.

They should not just loop through the same animation.

Examples:

Bird:

- lands on tree
- watches the player
- flies away if disturbed
- returns later

Fish:

- swim around
- approach food
- scatter when rock hits water
- follow currents

Rabbit:

- wanders
- becomes startled
- runs away
- eventually returns

Butterfly:

- follows flowers
- occasionally follows the cursor

Frog:

- sits near water
- jumps when disturbed

The exact animals are your creative choice.

Focus on believable micro-behaviors rather than complexity.

</animals>

<boat>

Add a small boat.

The boat should:

- float naturally
- bob with waves
- respond to wind
- optionally be draggable or launchable

If appropriate, let the user click it and send it sailing around the island.

A tiny boat leaving a wake would be a great visual detail.

</boat>

<tiny_house>

Create a small cabin/house.

It should have subtle interactions:

- door opens
- window lights turn on at night
- chimney produces smoke
- light changes depending on weather
- perhaps a tiny character or silhouette appears inside

Do not turn it into a full interior-building system.

It exists primarily to give the island personality.

</tiny_house>

<lighthouse>

If a lighthouse is included:

During daytime it should be dormant.

At night:

- light activates
- beam rotates
- light interacts with fog
- tiny glow is visible across the ocean

Consider hiding a small interaction here.

</lighthouse>

<secrets>

This is extremely important.

Hide small discoveries throughout the island.

Do not explain all of them.

Examples:

- clicking a particular tree makes something fall
- throwing a rock at a certain location reveals something
- feeding fish repeatedly causes a special fish to appear
- staying still for a while attracts an animal
- interacting with the lighthouse at night triggers something
- watering a strange flower causes it to bloom
- a bottle washes onto shore
- a hidden object exists behind the island
- something changes during a storm
- something unusual happens at midnight

Create several secrets yourself.

The user should be able to discover things organically.

The experience should reward curiosity.

</secrets>

<mysterious_seed>

Consider making one special glowing seed/object discoverable on the island.

It should not be explained immediately.

If the user plants it and interacts with the environment around it, it should slowly react.

For example:

rain → growth
sun → growth
night → glow
water → growth
interaction → growth

Eventually it could become a strange tree, flower, portal, structure, or another unexpected object.

You have full creative freedom here.

The purpose is to create a small mystery that makes the user keep exploring.

</mysterious_seed>

<environmental_reactivity>

Make the world respond to the user's presence.

Examples:

- footsteps affect grass
- cursor movement influences wind
- touching water creates ripples
- throwing objects disturbs animals
- clicking trees shakes leaves
- touching flowers moves petals
- walking near birds makes them fly
- objects cast appropriate shadows
- rain changes surfaces
- nighttime changes creature behavior

Whenever possible, prefer cause-and-effect interactions.

The user should feel:

"I did that, and the world reacted."

</environmental_reactivity>

<sound>

If audio can be implemented elegantly, create a subtle ambient soundscape.

Possible layers:

- ocean
- wind
- birds
- rain
- fire
- subtle environmental ambience

Interactions can have tiny sounds:

- splash
- pebble impact
- leaves
- bell
- wood
- footsteps

Do NOT autoplay intrusive music.

If audio is included, make it tasteful and allow mute/unmute.

If sound implementation would compromise the project, prioritize visual quality.

</sound>

<visual_quality>

This project should NOT look like a default Three.js demo.

Pay extreme attention to:

- lighting
- shadows
- material quality
- color harmony
- scale
- composition
- atmospheric depth
- animation timing
- particle density
- water
- reflections
- environmental motion
- object placement
- camera framing

Use a coherent art direction.

Avoid:

- excessive bloom
- random gradients
- generic glassmorphism UI
- giant UI panels
- excessive rounded cards
- generic SaaS styling
- unnecessary text
- excessive particle effects
- visual clutter
- everything glowing
- "AI generated" aesthetic

The world itself is the interface.

</visual_quality>

<interaction_design>

Every interaction should have a clear response.

Follow this mental model:

INPUT
→ physical response
→ secondary environmental response
→ subtle visual/audio feedback

Example:

throw rock

rock flies
→ hits water
→ splash
→ ripple
→ fish scatter
→ nearby bird reacts
→ waves continue propagating

This is much better than:

click
→ particle effect

Build chains of reactions whenever practical.

</interaction_design>

<ui>

Keep UI extremely minimal.

The first screen should mostly be the world.

Avoid a giant HUD.

If controls are needed, use tiny unobtrusive controls.

Possible controls:

sound
weather
reset
camera
time

But prefer world interactions over buttons.

A user should be able to discover most functionality without reading instructions.

If you need an onboarding hint, make it extremely subtle and temporary.

</ui>

<performance>

This must run smoothly in a browser.

Prioritize:

- stable frame rate
- efficient rendering
- instancing where useful
- reasonable geometry
- efficient particles
- sensible texture sizes
- shader efficiency
- lazy loading where useful
- avoiding unnecessary React re-renders
- disposing resources correctly

Do not sacrifice the visual experience unnecessarily for premature optimization.

But also do not create a scene that destroys the GPU.

Use profiling when useful.

Target a smooth experience on a modern laptop and a reasonable fallback on mobile.

</performance>

<mobile>

Make the experience usable on touch devices.

Support:

- tap
- drag
- pinch/zoom where appropriate
- touch-based object interaction

Do not require hover.

If a desktop-only interaction is beautiful but impossible on mobile, create an equivalent touch interaction.

</mobile>

<architecture>

Use the existing project stack if one exists.

If starting from scratch, choose a modern, sensible Three.js/R3F architecture.

Keep systems modular enough that:

- water
- weather
- time
- wind
- animals
- particles
- interactions
- camera

can evolve independently.

Do not over-engineer.

This is a 1–2 day creative project, not a game engine.

Prefer simple systems that produce excellent perceived results.

</architecture>

<development_process>

Do not attempt to implement every feature blindly in one pass.

Work in stages.

First establish:

1. project setup
2. island composition
3. camera
4. lighting
5. water
6. basic environment animation

Then establish the interaction foundation.

Then add the strongest interactions.

Then add animals/weather/time.

Then add secrets and polish.

After each major stage, actually inspect the result.

If browser automation, screenshots, visual inspection, or computer-use tools are available, use them.

Do not assume something looks good because the code is technically correct.

Look at the actual result.

Iterate on visual quality.

</development_process>

<creative_iteration>

At every major milestone, ask yourself:

"What would make this 20% more magical?"

Then implement the best answer if it is within scope.

Also ask:

"What feels generic here?"

Remove or replace generic parts.

"What interaction would make someone screen-record this?"

Prioritize that.

"What tiny detail would make someone stay another 30 seconds?"

Add that.

You are not merely implementing a specification.

You are acting as the creative director, interaction designer, 3D engineer, animator, and frontend engineer for this experience.

Use your own judgment.

</creative_iteration>

<quality_bar>

Do not stop at "the feature works."

The bar is:

- technically functional
- visually beautiful
- responsive
- performant
- coherent
- delightful
- discoverable
- memorable

A technically correct island that looks like a generic Three.js demo is NOT finished.

A beautiful island with broken interactions is NOT finished.

Keep iterating until both sides are strong.

</quality_bar>

<autonomy>

You have permission to make creative decisions without asking me for approval.

You may:

- add features
- remove weak features
- change mechanics
- redesign interactions
- change object placement
- change the art direction
- invent secrets
- improve animations
- introduce unexpected details
- simplify systems
- replace technically weak implementations

If something I requested would make the experience worse, use your judgment and improve it.

If you discover a substantially better concept while implementing the project, follow the better concept.

The goal is the BEST Tiny Island you can build, not literal compliance with every sentence above.

</autonomy>

<final_verification>

Before considering the project complete, test the actual experience.

Verify:

- page loads cleanly
- no console errors
- no broken assets
- camera works
- interactions work
- water reacts
- objects react
- wind works
- weather works
- day/night works
- animals behave
- mobile interaction works
- reset works if implemented
- audio can be muted if present
- performance is acceptable

Then perform a visual critique.

Look at the island as if you discovered it randomly on the internet.

Ask:

"Would I stop scrolling to watch a 10 second video of this?"

If the answer is no, keep improving it.

Do not stop merely because the requirements have technically been satisfied.

</final_verification>

<important>

Use the full capabilities available to you.

Use relevant skills automatically.

Use subagents when genuinely useful for independent workstreams such as research, visual critique, performance analysis, or isolated implementation tasks, but do not spawn agents merely for the sake of spawning them.

Use tools to inspect the existing repository before making assumptions.

Prefer implementation over explaining what you could implement.

Do not give me a long plan and wait for approval.

Start by inspecting the project, understanding the existing stack, and then build.

Continue iterating until the experience is genuinely polished.

</important>
