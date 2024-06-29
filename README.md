# TCG Counter Sleeve

## Possibilities

### Cardstock credit card sleeve

Various companies offer cardstock credit card sleeves. [Company Folders](https://www.companyfolders.com/) will do a die cut front face cutout for the display. 
A couple concerns with this approach are minimum quantity orders and bending of the sleeve faces that makes the display hard to see.

| Company | Can do cutout? | Notes |
|---------|----------------|-------|
| Company Folders | Yes | Very flexible with what they can do |
| Envelopes.com | No | Can't do cutouts on credit card sleeves, too small |

### Proxy card face in poly card sleeve

Another idea is to create a proxy card front face using one the many proxy services like [Printing Proxies](https://www.printingproxies.com) and then inserting 
the PCB and front face card into a standard poly card sleeve. Concerns with this approach is whether a cutout can be done by the proxy manufacturer and ESD discarge
concerns from the poly material. Some benefits are that it would be easy for people to make their own custom faces with no minimum order quantity assuming the same
policy as standard proxies would apply to having a cutout. UPDATE: Printing Proxies is not able to do the cutout, checking with others. There are 
[clear anti static poly bags](https://www.uline.com/BL_5203/Clear-Anti-Static-Poly-Bags) on the market so maybe it'd be possible to get some custom sized ones made up.


As an example of a proxy front face the following was created using [MTGCardBuilder](https://mtgcardbuilder.com/) and the art was generated using ChatGPT. The display mockup
was added after. It would be pretty easy for people to come up with their own designs using existing tools.

![nfc_counter_proxy](https://github.com/groundst8/tcg-counter-sleeve/assets/53413353/74cd7227-f47b-4b54-9fc8-70c2268b1180)
![nfc_counter_oil_proxy](https://github.com/groundst8/tcg-counter-sleeve/assets/53413353/5d550fbc-b291-4d54-9564-b1ea3dd70b28)


**Card Cutouts**
| Company | Can do cutout? | Notes |
|---------|----------------|-------|
| Printing Proxies | No | Not able to do a cutout |
| [MPC](https://www.makeplayingcards.com) | Yes | $600 to create punch molding|

**ESD Safe Sleeves**
| Company | ESD Safe poly sleeve? | Notes |
|---------|-----------------------|-------|
| Ultimate Guard | ? | Waiting to hear back |
| Dragon Shield | ? | Waiting to hear back |
| ULINE | No | clear antistatic poly bags not available in custom sizes |
| DESCO | ? | Waiting to hear back |

## Material ESD Properties

**Surface Resistivity:**

Cardstock: 10^10 to 10^12 ohms/square
Polypropylene: 10^16 to 10^18 ohms/square

Higher resistivity leads to greater static buildup potential.

**Triboelectric Series Ranking (approximate):**

Cardstock: +10 to +30
Polypropylene: -20 to -40

The further apart materials are on this scale, the more likely they are to generate static when rubbed together.

**Typical Static Voltage Generated (when rubbed against cotton):**

Cardstock: 1,000 to 3,000 volts
Polypropylene: 5,000 to 20,000 volts


**Moisture Regain (at 65% relative humidity):**

Cardstock: 6-8%
Polypropylene: <0.1%

Higher moisture regain reduces static buildup.


**Charge Decay Rate (time to dissipate 50% of charge):**

Cardstock: 10-30 seconds
Polypropylene: Several minutes to hours

# Prototyping

In either case, cardstock sleeve, or proxy it's not economical to pay to create a die punch until exact dimensions have been idenfied. It's hard to get cutouts very accurate with an x-acto knife and test cut templates. I looked into cutting machines like the Silhouette Cameo which uses a blade and laser cutters for prototyping cutouts. My local library has a makerspace with an Epilog Legend Helix 50 Watt Laser Cutter that is available for free use. It has a 24" x 18" bed so it would theoretically be possible to cut batches of 45 cards at a time which could enable low volume production without investing in creating a die punch.

**Epilog Legen Helix 50 Watt Settings for cutting Magic The Gathering card**

- Resolution: 600?
- Job Type: Vector
- Options: 
  - Auto Focus
  - Send to laser
  - Send to manager
- Speed: 70%?
- Power: 20%?
- Frequency: 500Hz?
- Horizontal Size: 24"
- Vertical Size: 18"




