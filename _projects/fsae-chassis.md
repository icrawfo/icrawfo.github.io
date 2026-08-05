---
layout: entry
type: project
order: 1
title: FSAE Chassis
role: Chassis Lead
org: Anteater Formula Racing (FSAE)
dates: Sep 2024 &ndash; Present
location: Irvine, CA &middot; 45-Member Team &middot; 6-Person Chassis Subteam
tagline: >-
  Leading design, FEA validation, and manufacturing of a sub-55&nbsp;lb chassis
  for UC Irvine's Formula SAE team &mdash; and TIG-welding most of it myself.
card_placeholder: >-
  Close-up 3/4 shot of the bare welded chassis on the fixture table, good side
  lighting to show weld beads and tube geometry.
hero_placeholder: >-
  Wide, well-lit shot of the full chassis (welded or on the fixture table),
  or the complete car in the paddock/on track. 21:9 crop works best here.
stats:
  - value: "59 lb"
    label: Current Chassis Weight (Unwelded, No Tabs)
  - value: "3,000"
    label: N&middot;m/deg Torsional Rigidity (vs. 2,100 Target)
  - value: "&plusmn;0.003&Prime;"
    label: Pedal Box Press-Fit Tolerance
  - value: "51st"
    label: Overall Finish, FSAE Michigan
gallery:
  - caption: >-
      Chassis mid-weld on the tube-notching fixture, showing jigging and
      tack welds before final passes.
  - caption: >-
      Close-up of a finished TIG weld bead on a chromoly joint &mdash; a shot
      that shows bead consistency and heat-affected zone control.
  - caption: >-
      Screenshot of the ANSYS Mechanical torsional rigidity simulation,
      deformation contour plot with the load/constraint setup visible.
  - caption: >-
      The 6061-aluminum pedal box fresh off the HAAS, showing the machined
      press-fit bosses.
  - caption: >-
      Ian welding at the table (PPE on, arc visible) &mdash; a good action
      shot for the "who is this person" read.
  - caption: >-
      Full car in the paddock or on track at FSAE Michigan, ideally with
      the team in frame.
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
powertrain parts.

## Design & Analysis

The design target for this season is a sub-55&nbsp;lb chassis (untabbed,
unwelded), down from 63&nbsp;lb the prior season. I run the structural
validation in ANSYS Mechanical, using torsional rigidity as the primary
stiffness metric &mdash; this season's design hit 3,000&nbsp;N&middot;m/deg
against a 2,100&nbsp;N&middot;m/deg target, well past what we needed without
giving back the weight savings.

The biggest design decision this cycle was switching the tube material from
1020 DOM steel to 4130 chromoly. Chromoly's higher yield strength let us drop
wall thickness while holding the same structural targets, which is where most
of the weight came out of the design. It's a harder material to weld
correctly &mdash; chromoly is more sensitive to heat input and post-weld
treatment than mild steel &mdash; which fed directly into how I planned the
welding sequence for manufacturing.

## Manufacturing

I manufactured and TIG-welded the prior season's chassis start to finish:
98&nbsp;lb with tabs, down from 122&nbsp;lb two seasons earlier, and the
program's first one-year chassis build in 20 years. Everything downstream of
the frame runs through me too &mdash; I CNC-machined the 6061-aluminum pedal
box on the HAAS to &plusmn;0.003&Prime; press-fit tolerances with zero
failed fits, and fabricated the suspension and powertrain components that
don't get outsourced.

The one place I want to get better: welded suspension pickup-point accuracy.
Last season's chassis came in at 1.25&nbsp;mm average deviation from nominal
(6&nbsp;mm at the worst point), mostly from weld draw and fixturing error.
It didn't cause any failures, but it's the clearest target for improvement
in how I sequence welds and hold tube position through the process.

## Results & What's Next

The prior season's chassis helped move the team from 79th overall (no
acceleration run) to 51st overall and 10th in acceleration at FSAE Michigan
&mdash; on top of being 24&nbsp;lb lighter than the chassis two seasons before
it. This season's design is sitting at 59&nbsp;lb unwelded against a 55&nbsp;lb
target, with welding starting this fall and a sub-70&nbsp;lb target once
tabbed and welded.
