---
layout: entry
type: project
order: 1
title: FSAE
role: Chassis Lead
org: Anteater Formula Racing
dates: Sep 2024 &ndash; Present
location: Irvine, CA &middot; 45-Member Team &middot; 6-Person Chassis Subteam
tagline: >-
  Leading chassis design, FEA validation, and manufacturing for UC Irvine's
  Formula SAE team &mdash; plus the brakes and powertrain fabrication that
  comes with it.
card_placeholder: >-
  Close-up 3/4 shot of the bare welded chassis on the fixture table, good side
  lighting to show weld beads and tube geometry.
card_image: /assets/images/fsae-chassis-fixture.jpg
hero_placeholder: >-
  Wide, well-lit shot of the full chassis (welded or on the fixture table),
  or the complete car in the paddock/on track. 21:9 crop works best here.
hero_image: /assets/images/fsae-team-car-lift.jpg
stats:
  - value: "59 lb"
    label: Current Chassis Weight (Unwelded, No Tabs)
  - value: "1,371"
    label: lb&middot;ft/deg Torsional Rigidity (Up 33% YoY)
  - value: "1.25 mm"
    label: Avg. Hardpoint Deviation After Manufacturing
  - value: "51st"
    label: Overall Finish, FSAE Michigan
gallery:
  - caption: >-
      The torsional rigidity test rig &mdash; a pivoting see-saw beam bolted
      to the chassis through laser-cut, CNC-bent adaptors, mid-test with dial
      indicators in frame.
  - caption: >-
      The crossmemberless front bulkhead test coupon &mdash; a 100mm section
      cut to replicate the real connection point, loaded in the Instron.
  - caption: >-
      Side-by-side of a laser/CNC-notched tube joint vs. a hand-notched one
      &mdash; a shot that shows the accuracy difference that drove the
      process change.
  - image: /assets/images/fsae-cad-model.png
    caption: >-
      CAD model of the chassis, color-coded by tube group &mdash; main frame,
      roll hoops, bracing, and front bulkhead.
  - image: /assets/images/fsae-fixture-build.jpg
    caption: >-
      Building this year's chassis fixture &mdash; aluminum extrusion towers
      set up around the new hardpoint-focused jigging strategy.
  - image: /assets/images/fsae-welding-action.jpg
    caption: >-
      Welding on the fixture table, PPE on and arc visible.
  - image: /assets/images/fsae-ansys-axial-force.png
    caption: >-
      ANSYS Mechanical axial force results under the torsional rigidity
      load case, full chassis contour plot.
  - image: /assets/images/fsae-cad-pedal-box.png
    caption: >-
      CAD of the pedal box assembly, including the mid-season 3rd-pedal
      revision.
  - image: /assets/images/fsae-pedal-box-mill.jpg
    caption: >-
      The 6061-aluminum pedal box on the manual mill for secondary
      operations, after the HAAS cut the primary press-fit bores.
  - image: /assets/images/fsae-intake-manifold.jpg
    caption: >-
      The 3D-printed intake manifold mounted on the engine.
  - image: /assets/images/fsae-exhaust-system.jpg
    caption: >-
      The current exhaust system, manufactured and installed.
  - image: /assets/images/fsae-cad-header-design.png
    caption: >-
      CAD of the new header design in progress, showing the packaging
      constraints around the engine bay.
  - image: /assets/images/fsae-cad-full-assembly.png
    caption: >-
      Full car assembly in CAD &mdash; chassis, engine, carbon fiber seat,
      and suspension.
  - image: /assets/images/fsae-suspension-parts.jpg
    caption: >-
      Machined aluminum suspension uprights and brackets, fresh off the mill.
  - image: /assets/images/fsae-subassembly-weld.jpg
    caption: >-
      TIG-welding a chassis subassembly in the shop fixture.
  - image: /assets/images/fsae-paddock-crowd.jpg
    caption: >-
      The car being rolled out at FSAE Michigan, paddock crowd in frame.
  - image: /assets/images/ian-portrait-shop.jpg
    caption: >-
      Ian with the car on the fixture table in the Vehicle Performance
      Engineering Lab.
---

## The Program

Anteater Formula Racing is UC Irvine's 45-member Formula SAE team, designing and
building a formula-style race car from scratch every season to compete against
roughly 100 other university teams at FSAE Michigan. Two seasons ago, the team's
chassis weighed 122&nbsp;lb and the car placed 79th overall without completing
the acceleration event. Last season &mdash; my first on the team &mdash; we
rebuilt the chassis in a single year for the first time in the program's
20-year history, brought it down to 98&nbsp;lb, and finished 51st overall and
10th in acceleration.

## My Role

I'm the Chassis Lead, running a 6-person subteam responsible for the frame's
design, analysis, manufacturing, and fixturing. Last season I was the
manufacturing lead on the chassis: I TIG-welded almost the entire frame myself
and built the fixturing used to hold tube geometry through the welding
process. This season, as lead, my focus shifted upstream to design and FEA
validation of the next chassis, while still doing the bulk of the shop work
across the car &mdash; the pedal box, suspension components, and several
powertrain parts. Chassis isn't the only thing I work on for the team, either
&mdash; anywhere the car needed a part machined, mounted, or welded outside
the frame itself, it tends to come through me too.

## Design & Analysis

The design target for this season is a sub-58&nbsp;lb chassis (untabbed,
unwelded), down from 63&nbsp;lb the prior season. Sizing starts from the
minimum tube requirements in the rules (the SES &mdash; Structural
Equivalency Spreadsheet &mdash; that governs anything deviating from the
baseline steel-tube spec), and from there I only upsize a tube when ANSYS
shows it's actually needed, rather than oversizing preemptively the way a lot
of teams do to stay safe &mdash; that habit is where a lot of unnecessary
chassis weight usually comes from.

I run three main load cases &mdash; braking, cornering, and acceleration
&mdash; to pull load-transfer numbers and size the frame around what the car
actually sees, plus torsional rigidity as the primary stiffness metric. This
season's design hit 1,371&nbsp;lb&middot;ft/deg, up 33% from last season's
1,027&nbsp;lb&middot;ft/deg, well past what we needed without giving back the
weight savings.

The biggest design decision this cycle was switching the tube material from
1020 DOM steel to 4130 chromoly. Chromoly's higher yield strength let us drop
wall thickness while holding the same structural targets, which is where most
of the weight came out of the design. We're now looking into heat-treating
the chassis (something we've never done before) to get even more out of the
material, though it's not confirmed yet &mdash; it comes down to budget.

### Current Research: Bonding Carbon Fiber to Steel Tubing

Beyond this season's chassis, I'm leading research into bonding carbon fiber
to the steel chassis tubing, with the goal of pushing torsional rigidity
higher than an all-steel tube frame can achieve on its own &mdash; the carbon
fiber would reinforce the tube walls rather than replace them, adding
stiffness without the cost and manufacturing overhaul of a full composite
monocoque. This is early-stage research only: we're still working through
bonding method and surface prep (adhesive selection, steel surface treatment,
layup approach) and nothing has been implemented on an actual chassis yet.

### How We Actually Measure Torsional Rigidity

TR isn't just a simulation number &mdash; we validate it physically. We built
a rig that works like a see-saw: a pivoting beam mounted at the front of the
chassis lets us apply a controlled twist, with laser-cut, CNC-bent adaptors
bolting the rig to the frame and dial indicators reading deflection at fixed
points. That measured deflection is what we back-calculate the actual
lb&middot;ft/deg number from, rather than trusting the FEA output on its own.

## Rules-Driven Testing: The Crossmemberless Bulkhead

One of the bigger engineering swings this season is a crossmemberless front
bulkhead &mdash; removing a structural member the rules technically require
unless you can prove an equivalent design is just as safe. That proof has to
be physical, not just simulated, so we built a test article: a 100&nbsp;mm
section cut to replicate the actual bulkhead connection point, loaded on an
Instron to see exactly where and how it fails. That data is what lets us make
the case that the lighter, crossmemberless design meets the same safety bar
as the standard one.

## Manufacturing

I manufactured and TIG-welded the prior season's chassis start to finish:
98&nbsp;lb with tabs, down from 122&nbsp;lb two seasons earlier, and the
program's first one-year chassis build in 20 years.

Last year we hand-notched every tube, and it's a big part of why that
chassis ended up with suspension pickup points averaging 1.25&nbsp;mm off
nominal (6&nbsp;mm at the worst point) &mdash; hand notching just doesn't
hold the same accuracy as a machine does. This season we're working with
outside shops for CNC laser notching and CNC tube bending instead, and I
changed the fixturing strategy to match: last year's fixture held every tube
at mid-span, spreading clamping evenly across the frame; this year's fixture
concentrates precision specifically at the suspension hardpoints and the
engine mount, and lets the less critical areas take up whatever warping
happens instead. Better to control the tolerances that actually matter and
let the rest float than spread your accuracy thin trying to hold everything
equally.

## Beyond the Chassis: Brakes & Powertrain

I manufactured almost the entire pedal box myself, running all of the CNC CAM
programming for it and machining it on the HAAS to &plusmn;0.003&Prime;
press-fit tolerances with zero failed fits. Partway through last season the
team ran into a problem that required a third pedal, so I went back into the
design and modified the pedal box to add one &mdash; a real mid-season
iteration rather than a clean one-shot build.

On the powertrain side, I've built all of the mounting systems, 3D-printed
the intake manifold, and manufactured the current exhaust system. We're now
designing an all-new header set for this season, working through some real
packaging constraints in the engine bay while trying to optimize scavenging
for more low-RPM performance &mdash; that'll be built and welded once the
design is locked.

## How I Lead the Team

Leading chassis is different from leading most other FSAE subteams, because
the chassis is fundamentally one connected structure rather than a set of
separable parts &mdash; you can't just hand someone "a component" the way a
suspension or aero lead can. Instead I run it more as a collective: each
member takes ownership of a region &mdash; front-end geometry, mid-section
geometry, and so on &mdash; and runs their own analysis and design reviews on
it. What I actually care about isn't the fine detail of any one person's
design; it's whether they can tell me *why* one geometry outperforms another
and how that reasoning should shape the master chassis. We back that up with
weekly meetings and dedicated work sessions to keep design and manufacturing
moving together instead of design finishing months before anyone picks up a
grinder.

## Results & What's Next

The prior season's chassis helped move the team from 79th overall (no
acceleration run) to 51st overall and 10th in acceleration at FSAE Michigan
&mdash; on top of being 24&nbsp;lb lighter than the chassis two seasons before
it. This season's design is sitting at 59&nbsp;lb unwelded against a 58&nbsp;lb
target, with welding starting this fall and a sub-70&nbsp;lb target once
tabbed and welded.
