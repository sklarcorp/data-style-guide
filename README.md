Data Style Guide Overview
=========================

## Table of Contents ##

* [General Rules & Guidelines](#general-rules--guidelines)
* [Field Specific Rules & Guidelines](#field-specific-rules--guidelines)
* [Family Name](#family-name)
* [Product](#product)
* [Length](#length)
* [Sorting Length (Decimal Inches)](#sorting-length-decimal-inches)
* [Curvature](#curvature)
* [Working Surface Style](#working-surface-style)
* [Tip End Style](#tip-end-style)
* [Tip Dimensions](#tip-dimensions)
* [Tip End Style (B)](#tip-end-style-b)
* [Tip Dimensions (B)](#tip-dimensions-b)
* [Size/Model](#size--model)
* [Pattern](#pattern)
* [Handle](#handle)
* [Grade](#grade)
* [Brand](#brand)
* [Material](#material)
* [Color](#color)
* [Sterile?](#sterile)
* [Disposable?](#disposable)
* [Latex?](#latex)
* [UOM](#uom)
* [UOM Factor](#uom-factor)
* [Additional Description](#additional-description)
* [Instrument Type](#instrument-type)
* [Width](#width)
* [Height/Depth](#height--depth)
* [Diameter](#diameter)
* [Volume](#volume)
* [Action](#action)



General Rules & Guidelines
--------------------------

### Capitalization ###
* Follow the rules for [Title Case](http://en.wikipedia.org/wiki/Letter_case#Case_styles) when completing most data fields 
* Generally this means to capitalize the first letter of each word except articles, prepositions, and conjunctions
 * Examples of [Articles](http://en.wikipedia.org/wiki/Article_(grammar))  are "the"  "a"  and "an" 
 * Examples of [Prepositions](http://www.merriam-webster.com/dictionary/preposition) are "on" "in" and "to"
 * Examples of [Conjunctions](http://en.wikipedia.org/wiki/Conjunction_(grammar)) are "and"  "or"  and "but"
* **NOTE** For our purposes _do not_ capitalize units of measure (e.g. inches)

* Follow the rules for [Sentence Case](http://en.wikipedia.org/wiki/Letter_case#Case_styles) when completing `Short Description` and `Description` fields because they are more likely to follow a paragraph format and incorporate existing marketing information


### Spaces and Slashes ###
*  Generally there should be a space before and after a slash 
  *  (e.g. Handle: Bayonet / Offset Thumb)
  *  (e.g. Family Name: Hartmann / Alligator)
*  DO NOT put a space before a slash when describing a `Tip End Style` or completing any `Tip End` field
  *  (e.g. Sharp/Sharp; Sharp/Blunt; Blunt/Blunt)
*  Measurements requiring fractions should have a space between the whole number and the fraction 
  (e.g. 6 1/2" not 61/2")
*  Do not put a space between the numbers creating a fraction (e.g. 1/2" not 1 / 2")


### Spelling Out Words and Use of Symbols or Abbreviations ###
*  Spell out the words "with" and "without" - Do Not Use "w/" or "w/o" abbreviations
*  As specified in the Capitalization Section, _do not_ capitalize the "w" in "with" and "without"
*  Spell out the word "French" when referring to French measurements.   _Do Not_ use any form of abbreviation (e.g. "Fr"  "FR"  "Fr.")
*  Spell out the word "Degrees".  Do not use the symbol °
* "Inches" should be reflected as the symbol "
* "Millimeters" should be reflected as a lowercase abbreviation (e.g. "mm")
* "Centimeters should be reflected as a lowercase abbreviation (e.g. "cm")




Field Specific Rules & Guidelines
---------------------------------

### Family Name ###
* Generally the name of the doctor or surgeon who created the instrument
* If more than one name is associated with the instrument, names should be hyphenated with no spaces (e.g. Lichtwitz-Bier)
* Instrument nicknames such as "Alligator" and "Mosquito" should go in the Family Name field, not Product
* Nicknames (e.g. "Alligator") should follow the primary family name with a forward slash separating names with a space before and after the forward slash (e.g. Hartmann / Alligator; Packer / Mosquito)



### Product ###
* Indicates specific type of instrument (e.g. Scissors, Forceps)
* Anatomical details can be in this field (e.g. Antrum Trocar, Thoracic Trocar, Ear Curette) 
* "Forceps" not "Forcep" 
* "Speculum" = one, "Specula" is used for sets only
* "Needle Holder" --> Two words, no "s" on "Holder"



### Length ###
* Generally the overall length of the instrument identified in any single measurement regardless of unit
* Measurements should be followed by the applicable symbol or abbreviation
  * Inches = (") as in [06-2860 Steel Ruler](http://www.sklarcorp.com/6-steel-ruler.html)
  * Millimeters = (mm) as in [91-6100 Bipolar Adson Forceps](http://www.sklarcorp.com/bipolar-adson-forceps.html)
  * Centimeters = (cm) as in [40-3252 Sheehan Gouge](http://www.sklarcorp.com/sheehan-gouge-16cm.html)
* Measurements requiring fractions should have a space between the whole number and the fraction 
  (e.g. 6 1/2" not 61/2")
* No ending zero after whole numbers (e.g. 6" not 6.0")



### Sorting Length (Decimal Inches) ###
* Generally the overall length of the instrument identified in inches in decimal format
* Measurements in this field should not be followed by the inches symbol (e.g. an insturment with a length of 6 inches will be reflected in this field simply as "6")
* No ending zero after whole numbers (e.g. 6 not 6.0)
* Leading zero for measurements less than 1 (e.g. 0.2 not .2)


### Curvature ###
* Generally: Straight, Curved, Angled, Slightly Curved, Strongly Curved, Double / "S" Curve
* Specific angle may also be indicated 
* If an instrument is angled, indicate the specifics of the angle in parenthesis following the word "Angled" (e.g. Angled (25 degrees) or Angled (25 Degrees Upwards) or Angled (Upwards)
*  Spell out the word "Degrees".  Do not use the symbol ° 
*  Double Ended instruments will have two values in the `Curvature` field


### Working Surface Style ###
* Most Commonly: Smooth or Serrated
* May also be Cross-Serrated, Horizontally Serrated, Vertically Serrated, Partially Serrated
* Fenestrated will be indicated here
* Tungsten Carbide Needle Holders will always have either a Smooth or _Cross_-Serrated Working Surface Style
* Tungsten Carbide Forceps will always have either a Smooth or _Cross_-Serrated Working Surface Style
* **DeBakey** and **Cooley** Style Teeth will be reflected in the `Working Surface` field rather than the `Tip End Style` where Teeth details are generally recorded.
  *  _DeBakey_ Style Teeth are available in 2 variations: 
    *  1x2 rows of atraumatic teeth, as in [52-4977, DeBakey Atraumatic Forceps](http://www.sklarcorp.com/7-3-4-debakey-atraumatic-forcep-1mm.html)
    *  2x3 rows of atraumatic teeth, as in [Scheibe DeBakey Organ Seizing Forceps]( http://www.dimeda.de/produkte/search/) 
  *  _Cooley_ Style Teeth are available in 2 variations:
    *  2x2 rows of atraumatic teeth, as in [52-6696, Cooley Vascular Tissue Forceps](http://www.sklarcorp.com/9-1-2-cooley-vascular-tissue-forceps.html)
    *  3x3 rows of atraumatic teeth
    *  The [Vascular Jaw Configuration](https://db.tt/0JNcoIxd) document and [DeBakey and Cooley Style Teeth]( https://db.tt/Yhrm9qw9) image also show examples 


### Tip End Style ###
* Generally Sharp or Blunt
* May be combined Sharp/Sharp, Sharp/Blunt, Blunt/Blunt
* Teeth and/or Prong information will go in this field (e.g. "1x2 Teeth" or "1x2 Prongs")
* No spaces before or after forward slashes (e.g. "Sharp/Sharp" not "Sharp / Sharp")
* No spaces before or after "x" when indicating Teeth or Prongs (e.g. "1x2" not "1 x 2")
* "x" should be lowercase (e.g. "1x2" not "1X2")
* Adjectives such as Cupped, Spoon, Triangular etc. may be indicated here 


### Tip Dimensions ###
* Generally measurement of the tip of the instrument
* Most commonly indicated in millimeters
* "Millimeters" should be reflected as a lowercase abbreviation (e.g. "mm")
* May be indicated in inches for larger tips
* "Inches" should be reflected with the inches symbol (")
* No ending zero after whole numbers (e.g. "2mm" not "2.0mm")


### Tip End Style (B) ###
* For use with Double Ended instruments only
* Follow guidelines for Tip End Style 
* Generally Sharp or Blunt
* May be combined Sharp/Sharp, Sharp/Blunt, Blunt/Blunt
* Teeth and/or Prong information will go in this field (e.g. "1x2 Teeth" or "1x2 Prongs")
* No spaces before or after forward slashes (e.g. "Sharp/Sharp" not "Sharp / Sharp")
* No spaces before or after "x" when indicating Teeth or Prongs (e.g. "1x2" not "1 X 2")
* "x" should be lowercase (e.g. "1x2" not "1X2")
* Adjectives such as Cupped, Spoon, Triangular etc. may be indicated here 


### Tip Dimensions (B) ###
* For use with Double Ended instruments only
* Follow guidelines for Tip Dimensions
* Most commonly indicated in millimeters
* "Millimeters" should be reflected as a lowercase abbreviation (e.g. "mm")
* May be indicated in inches for larger tips
* "Inches" should be reflected with the inches symbol (")
* No ending zero after whole numbers (e.g. "2mm" not "2.0mm")


### Size / Model ###
* Adjectives such as Small, Medium, Large, and Infant, Child, Adult may be indicated here
 * [90-3957, Cusco Vaginal Speculum](http://www.sklarcorp.com/cusco-vaginal-speculum-6046.html)
 * [70-1041, Halle Nasal Speculum](http://www.sklarcorp.com/halle-nasal-speculum-5049.html)
* Sizes are sometimes reflected with the word "Size" and a whole number (e.g. Size 1, Size 2)
 * [93-1762-2, Regular Surgeon Needle](http://www.sklarcorp.com/regular-surgeon-needle-13257.html) 
* Sizes are sometimes reflected with the "Pound" Symbol (#) and a whole number (e.g. #1, #2, #3)
 * [90-5284, Gelhorn Pessary](http://www.sklarcorp.com/gelhorn-pessary-5551.html) 
* A Double-Ended instrument will have sizes reflected in this field separated by a slash (e.g. 21 / 22 or #9 / #10)
 * [90-4921, Hank Uterine Dilator](http://www.sklarcorp.com/catalogsearch/result/?q=90-4921&order=teir_level&dir=asc) 
 * [49-2985, Schluger Scaler](http://www.sklarcorp.com/schluger-scaler.html) 
* There should be a space before and after the slashes as specified in the [General Rules & Guidelines](#general-rules--guidelines)
* French measurements are reflected here
* French measurements are reflected by a whole number followed by the word "French" spelled out with a capital "F"
* For French measurements there should be a space between the number and the word "French"
 * [50-2008, Frazier Suction Tube](http://www.sklarcorp.com/frazier-suction-tube-13770.html)
* *NOTE* 1 French = 1/3 (0.33) millimeter


### Pattern ###
* Acceptable Values: Delicate, Extra Light, Extra Light _and_ Extra Delicate, Atraumatic, Heavy
* If the "Brand" is "Sklarlite™" then the pattern is "Extra Light"
* Instruments may have an "Extra Light" Pattern but not be a "Sklarlite™" product.
* If the "Brand" is "Sklarlite™ XD" then the pattern is "Extra Light and Extra Delicate"
* If an instrument has an "improved" version of the original instrument, indicate "Improved" here
* "Narrow Jaws" is indicated here


### Handle ###
* Generally describes the type of handle for the instrument 
* Most Commonly: Finger Ring, Thumb, Bayonet / Offset Thumb, Cross-Action Thumb, Plier, Dual Action Plier
* May also indicate descriptors such as Round, Octagonal, Flat, Smooth, Knurled, with Serrations, with Grooves
* Examples:
  *  Finger Ring, as in [47-1248  Iris Scissors](http://www.sklarcorp.com/iris-scissors-13806.html)
  *  Three Finger Ring, as in [80-1910  Rudd Clinic Hemorroid Ligator](http://www.sklarcorp.com/catalogsearch/result/?q=80-1910&order=teir_level&dir=asc)
  *  Finger Ring with Ratchet, as in [45-6266  Atlantic Grasper](http://www.sklarcorp.com/atlantic-grasper.html)
  *  Double Action Finger Ring, as in [40-2640 Buck Gramco Tendon Retriever](http://www.sklarcorp.com/catalogsearch/result/?q=40-2640&order=teir_level&dir=asc)
  *  Thumb, as in [97-736  Merit Dressing Forceps](http://www.sklarcorp.com/merit-dressing-forceps-4533.html)
  *  Bayonet / Offset Thumb, as in [98-0277  Jacobson Micro Forceps](http://www.sklarcorp.com/jacobson-micro-forceps-4644.html)
  *  Cross-Action Thumb, as in [24-1450  Wachenfeld Clip Forceps](http://www.sklarcorp.com/wachenfeld-clip-forceps.html)
  *  Plier, as in [40-1775  Needle Nose Pliers](http://www.sklarcorp.com/needle-nose-pliers.html)
  *  Plier with Spring, as in [93-492 Roux Syringe](http://www.sklarcorp.com/catalogsearch/result/?q=93-492&order=teir_level&dir=asc)
  *  Plier with Double Spring and Lock, as in [97-0474  Nail Nipper](http://www.sklarcorp.com/nail-nipper.html)
  *  Plier with Ratchet, as in [40-2413  Lane Bone Holding Forceps](http://www.sklarcorp.com/catalogsearch/result/?q=40-2413&order=teir_level&dir=asc)
  *  Plier with One Hook, as in [48-752 Extracting Forceps #18L Left](http://www.sklarcorp.com/extracting-forceps-18l-left.html) 
  *  Loop, as in [10-1356 Cannula Cleaning Brush](http://www.sklarcorp.com/cannula-instrument-cleaning-brush-1419.html)
  *  Loop with Grip, as in [62-8000  Aspirating Syringe](http://www.sklarcorp.com/catalogsearch/result/?q=62-8000&order=teir_level&dir=asc)
  *  Octagonal, as in [34-3624 Thoracic Trocar](http://www.sklarcorp.com/trocars/trocars/thoracic-trocar-4mm.html)
  *  Knurled, as in [41-800 Gracey Curette](http://www.sklarcorp.com/gracey-curette.html)
    *  [Definition of Knurled](http://dictionary.reference.com/browse/knurled)
    *  [Enhanced Image of a Knurled Handle](https://www.google.com/search?q=knurled&rlz=1C1CHFX_enUS559US559&es_sm=93&source=lnms&tbm=isch&sa=X&ei=3BNIU96rI8nE0AGar4HYDw&sqi=2&ved=0CAcQ_AUoAg&biw=1280&bih=899#facrc=_&imgdii=_&imgrc=2G3uG1bqIXZA6M%253A%3BhN4I_Ctqy2FtKM%3Bhttp%253A%252F%252Fwww.norcorp.com%252FPortals%252F60349%252Fimages%252F%252Fknurling.png%3Bhttp%253A%252F%252Fwww.norcorp.com%252Fdesign-aluminum-surfaces-blog%252Fbid%252F18050%252FKnurled-Finishes-on-Aluminum-Trim%3B600%3B450)
  *  T-Style, as in [40-6855 Bone Hook](http://www.sklarcorp.com/bone-hook.html)
  *  with Horizontal Grooves, as in [49-3360  Williger Raspatory](http://www.sklarcorp.com/williger-raspatory-6-1-4.html) or [11-1298  Commander Utility Shears](http://www.sklarcorp.com/commander-utility-shears.html)
  *  with Vertical Grooves, as in [40-9070 Kermisson Periosteal Raspatory](http://www.sklarcorp.com/catalogsearch/result/?q=40-9070&order=teir_level&dir=asc) or [40-7445 Chandler Elevator](http://www.sklarcorp.com/orthopedic/elevators/chandler-elevator-6461.html)
  *  with Finger Grips, as in [90-3452 Delee Retractor](http://www.sklarcorp.com/catalogsearch/result/?q=90-3452&order=teir_level&dir=asc)

### Grade ###
* Generally describes the grade of the instrument
* Most Commonly: Sklar®, Surgi-OR™, Merit™, Econo™, Econo™ Sterile
  * Sklar® = Premium (OR) Grade
  * Surgi-OR™ = Mid-Grade
  * Merit™ = Physician (Office) Grade
  * Econo™ = Floor Grade
  * Econo™ Sterile = Sterile Floor Grade

* The "Registered Trademark" symbol ® should follow "Sklar" (e.g. Sklar®)
* To enter the "Registered Trademark" symbol:
    * Mac: option+r
    * Windows: alt+0174

* The "Trademark" symbol ™ should follow Surgi-OR, Merit, and the word Econo (e.g. Surgi-OR™, Merit™, Merit™ Sterile, Econo™ and Econo™ Sterile)
*   To enter the "Trademark" symbol:
      * Mac: option+e
      * Windows: alt+0153


### Brand ###
* Generally describes the brand of a Premium Grade instrument
* Sklar brands are as follows:
  * **INSTRUMENTS**
    - **Sklarlite™** _Extra Light_ 
    - **Sklarlite XD™** _Extra Light and Extra Delicate_
    - **Sklar Blue™** _Electrosurgical_
      - _Single Blue Tip_, as in [91-5252 Sklar Blue™ Emmett Hook#2](http://www.sklarcorp.com/sklar-blue-emmett-hook-2.html)
      - _Dual Blue Tips_, as in [91-5450 Sklar Blue™ Schroeder Tenaculum](http://www.sklarcorp.com/sklar-blue-schroeder-tenaculum.html)
      - _Blue Blades_, as in [91-5047 Sklar Blue™ Pederson Vaginal Speculum](http://www.sklarcorp.com/sklar-blue-pederson-vaginal-speculum-3456.html)
      - **NOTE**  The appearance of blue coloring on an instrument does not always indicate it is a Sklar Blue™ product
      - [96-9679, Coated Electrode Needle](http://www.sklarcorp.com/coated-electrode-needle-2831.html) is NOT a Sklar Blue™ product
      - [96-9605, Electrosurgical Pencil](http://www.sklarcorp.com/electrosurgical-pencil-disposable-4596.html) is NOT a Sklar Blue ™ product
    - **Sklar Black™ Laser** _Reduced Reflectivity_
      - _Dual Gold Finger Rings_, as in [90-2330 Sklar Black™ Laser Heaney Needle Holder](http://www.sklarcorp.com/sklar-black-laser-heaney-needle-holder.html)
    - **Sklarhone™** _Knifelike Razor Edge_
      - _Dual Black Finger Rings_, as in [15-3315 Sklarhone™ Metzenbaum Scissors]( http://www.sklarcorp.com/sklarhone-metzenbaum-scissors-7942.html)
    - **Sklarcut™** _Micro-Serrated_
      - _Single Gold Finger Ring_, as in [15-3590  Sklarcut™ Iris Scissors](http://www.sklarcorp.com/sklarcut-iris-scissors-7693.html)
    - **Supercut Sklarhone™** _1 Knifelike Razor Edge and 1 Micro-serrated Edge_
      - _Dual Black Finger Rings_, as in [15-7032 Sklarhone™ Jameson Scissors Supercut](http://www.sklarcorp.com/sklarhone-jameson-scissors.html)
    - **Sklar Edge™** _TC Scissors_
      - _Dual Gold Finger Rings_, as in [16-1915 Sklar Edge™ TC Metzenbaum Scissors](http://www.sklarcorp.com/catalogsearch/result/?q=sklaredge+scissors&order=teir_level&dir=asc)
    - ~~**Sklargrip™** _TC-Coated Needle Holders_~~ _[Discontinued]_
      - ~~_Dual Gold Finger Rings_, as in [21-2070  Sklargrip™ Mayo-Hegar Needle Holder](http://www.sklarcorp.com/sklargrip-mayo-hegar-needle-holder-5119.html)~~
    - **SklarSafe™** _Safety Scalpels_
    - **SklarSpec™** _Disposable Vaginal Specula_
      - Clear Plastic, Sold in bulk quantities
      - as in [96-0847, Disposable Graves Vaginal Specula](http://www.sklarcorp.com/catalogsearch/result/?q=96-0847&order=teir_level&dir=asc)
    - **Sklar Tru-Punch™** _Single-Use Biopsy Punch_
    - **Sklar LiteGrip™** _Fenestrated Handles_
      - as in, [66-4034 Sklar LiteGrip™ Bishop-Harmon Forceps](http://www.sklarcorp.com/sklar-litegrip-fenestrated-handle-bishop-harmon-forceps.html)
    - **Sklartech 5000™** _Laparoscopic_
      - _Sklartech 5000 HX™_ - Disposable Insert, as in [31-7007 Sklartech 5000 HX™ Metzenbaum Scissor](http://www.sklarcorp.com/sklartech-5000-hx-metzenbaum-scissor-straight-for-use-w-31-7001xc-or-31-7002yc-reusable-handles-sterile-33cm-5mm-pack-of-10.html)
      - _Sklartech 5000 X™_ - 100% Disposable Instrument, as in [31-7012XC, Sklartech 5000 X™ Metzenbaum Scissors 100% Disposable](http://www.sklarcorp.com/catalogsearch/result/?q=31-7012xc&order=teir_level&dir=asc)
  
 * **CARE AND CLEANING**
    - **SklarLite™**  _Sterilization Container System_
      - Material = Stainless Steel Container and Silicone Mats & Inserts
      - Color = Silver, Yellow, Red, Blue, Green, Black
    - **Sklar-Cide™**  _High Level Disinfecting and Sterilizing Solution_
      - Material = Glutaraldehyde
      - Color = Green when Activated, Clear when Unactivated
    - **Sklar Disinfectant™**  _Ready-To-Use Spray Surface Disinfectant_
      - Material = Isopropanol
      - Color = Clear
    - **Sklar Disinfectant™ Wipes**  _Ready-To-Use, Premoistened Towelettes_
      - Material = Isopropanol, Two Dual Chain Quaternary Ammonium Chlorides, Non-Woven Cloth
      - Color = Blue Cloth with Clear Liquid
    - **Sklar Enzymatic™**  _Multi-Enzyme Detergent Concentrate_
      - Material = Protease Enzymes
      - Color = Light Yellowish Clear
    - ~~**Sklar Fresh™**  _Liquid Spray Odor Absorber_~~ _[Discontinued]_
      - ~~Material = Blend of pure biodegradable organic oils and trace elements~~
      - ~~Color = White~~
    - **Sklar Instru-Guard™**  _Lubricant and Rust-Inhibitor_
      - **Instru-Guard™ Lube**  _Polymeric Lubricant Concentrate_
        - Material = Polymeric Lubricant Concentrate
        - Color = Milk White
      - **Instru-Guard™ One-Step**  _Concentrated, Aqueous Alkaline Soultion_
        - Material = Potassium Hydroxide, Sodium Metasilicate, Methanol
        - Color = Translucent Green
    - **Sklar Kleen™**  _for Manual and Ultrasonic Cleaning_
      - **Sklar Kleen™ Low Foam**  _Automatic Washer Liquid Detergent, Low Foam_
        - Material = Polyoxypropylene-polyoxyethylene block copolymer, Sodium xylene sulfonate, Anionic phosphate ester-potassium salt, Tetrasodium EDTA
        - Color = Slightly Amber
      - **Sklar Kleen™ Liquid**  _Manual and Ultrasonic Instrument Detergent, Liquid_
        - Material = Sodium Dodecyl Benzene Sulfonate, Sodium Bicarbonate, Sodium Tripolyphosphate
        - Color = Translucent Amber
      - **Sklar Kleen™ Powder**  _Manual and Ultrasonic Instrument Detergent, Powder_
        - Material = Sodium Dodecyl Benzene Sulfonate, Sodium Bicarbonate, Sodium Tripolyphosphate
        - Color = Blue
    - **Sklar Lube Spray**  _Ready-To-Use Polymeric Lubricant_
      - Material = Polymeric Lubricant
      - Color = Milk White
    - **Sklar Lugols**  _Iodine Contrast Medium_
      - Material = Iodine, Potassium Iodide
      - Color = Deep Yellow
    - **Sklar Monsels**  _Ready-To-Use Hemostatic Paste_
      - Material = Ferric Subsulfate
      - Color = Mustard Yellow
    - **Sklar Polish™**  _Powdered Stain Remover_
      - Material = Citric Acid Powder
      - Color = White
    - **Sklar-Sheen™ Spray**  _Spray Foam Autoclave Cleaner and Conditioner_
      - Material = Phosphoric Acid
      - Color = Reddish Pink
    - **Sklar Soak™**  _Liquid Disinfectant_
      - Material = Isopropanol
      - Color = Clear
    - **Sklar Spray-Zyme™**  _Instrument Pre-Cleaner with Multi-Enzymatic Foam_  
      - Material = Lipase and Protease Enzymes
      - Color = Caribbean Green
      &nbsp;
    - Material Data Safety Sheets for Care and Cleaning Products is available at [MSDS](http://www.sklarcorp.com/msds)
    
* The "Trademark" symbol ™ should be utilized as in the examples above
     * To enter the "Trademark" symbol:
        * Mac: option+e
        * Windows: alt+0153

### Material ###
* Generally the primary material(s) from which an instrument or cleaning product is made.
* Most Common Instument Materials: Stainless Steel, Plastic, Aluminum, Silver, Tungsten Carbide
* Also Silicone
 * **NOTE**    _Silicone_ is a rubber-like synthetic compound, as in  [90-5262 Sklar Silicone Vaginal Dilators]( http://www.sklarcorp.com/sklar-silicone-vaginal-dilators-5265.html) as opposed to _Silicon_ which is a semi-conductive metalloid. 
 * There are few, if any, Sklar® instruments that actually contain Silicon.
 
* When listing multiple materials or ingredients:
 * Ask the question "Can I see where one material ends and the next begins?"
 * This will help you determine if the materials should be separated by a comma or a forward slash.

 * "Non-Discrete" materials or ingredients are separated by a comma (",") meaning you cannot see where one ends and the next begins. (e.g. There are three ingredients in a cleaning product: Potassium Hydroxide and Sodium Metasilicate and Methanol. You cannot see where one ingredient ends and another begins because they are mixed together. These are considered "Non-Discrete" and would be listed using a comma as Potassium Hydroxide, Sodium Metasilicate, Methanol.)

 * "Discrete" materials or ingredients are separated by a forward slash ("/") meaning you CAN see where one ends and the next begins. (e.g. A pair of scissors has Tungsten Carbide Inserts. You can see the line where the TC Insert ends and the Stainless Steel jaw begins. There are considered "Discrete" and would be listed using a forward slash as Tungsten Carbide / Stainless Steel.)

   * When listing multiple "Discrete" materials, begin at the working end of the instrument and move away from there.  Materials for [96-1228, Utility Shears](http://www.sklarcorp.com/utility-shears-sterile-lime-green.html) would be reflected as "Stainless Steel / Polypropylene"


### Color ###
* Generally reflects the color of the instrument based on the material from which the instrument is made
* When listing multiple colors, begin at the working end of the instrument and move away from there.  Color for [96-1228, Utility Shears](http://www.sklarcorp.com/utility-shears-sterile-lime-green.html) would be reflected as "Stainless Steel / Lime Green" or "Stainless Steel / Pink"
* There should be a space before and after the slashes as specified in the [General Rules & Guidelines Section](#general-rules--guidelines)
*   Most Common Colors: 
*   Stainless Steel = Gray
*   Silver = Silver
*   Aluminum (Non-Anodized) = Silver
*   Anodized Aluminum = Various, as in [SklarLite™ Sterilization Container Lids](http://www.sklarcorp.com/pdf/StainlessSteelwareCatalog.pdf)
    *  **NOTE**  If a material is listed as simply "Aluminum" but it is colored, the material is "Anodized Aluminum."  For our purposes, only Anondized Aluminum can be colored.  
    *  **ALSO**  Both "Non-Anodized" Aluminum and "Anodized" Aluminum can be silver.  
*   Chrome Plated = Chrome
*   Gold coating on handles = Gold
*   Sklar Black™ coating = Black
*   Sklar Blue™ coating = Blue
*   Plastic = Various
    *   [96-2950, Plastic Surgical Prep Razor](http://www.sklarcorp.com/plastic-surgical-prep-razor-non-sterile-case-of-100.html)
    *   [96-2916, Plastic Dressing Forceps](http://www.sklarcorp.com/5-plastic-dressing-forceps-non-sterile-box-of-100.html) 
    *   [10-3062, Plastic Instrument Soaking Tray](http://www.sklarcorp.com/instrument-soaking-tray-13602.html)
*   Polypropylene = Various
    *   [96-1228, Utility Shears](http://www.sklarcorp.com/utility-shears-sterile-lime-green.html)
     *  **NOTE** Polypropylene is a Plastic, but not all Plastic is Polypropylene
     *  [The Seven Most Common Plastics](http://www.reuseit.com/product-materials/the-7-most-common-plastics-and-how-they-are-typically-used.htm)
     
*   Silicone = Various
    *   [68-8002 through 68-8005 Aspirating Syringes](http://www.sklarcorp.com/catalogsearch/result/?q=aspriating+syringe&order=teir_level&dir=asc)
    *   [10-6543, Silicone Instrument Holder](http://www.sklarcorp.com/silicone-instrument-holder-for-cassettes-with-hinged-lid-3-3-20.html)
 


### Sterile? ###
* Acceptable values: Sterile, Non-Sterile
* Note the hyphen in Non-Sterile
* Assume that Sterile products are also Disposable


### Disposable? ###
* Acceptable values: Disposable or Reusable


### Latex? ###
* Acceptable values: Latex or Latex-Free
* Must be a hyphen in "Latex-Free"
* No space before or after hyphen


### UOM ###
* Unit of Measure
* Indicates grouping method of packing, ordering, or shipping instruments
* Most Commonly: "Each"  "Set"  "Pack"  "Case"  "Box"
* Abbreviated by two capital letters as follows:
 * Each = EA
 * Set = ST
 * Pack = PK
 * Box = BX
 * Case = CS
* Also
 * Bottle = BO (Think water bottle or spray bottle)
 * Jar = JR (Think shape of a Mason Jar)
 * Jug = JU (Think shape of a gallon milk jug)

* For Additional UOMs See Also [Product Naming and Grammar Conventions](https://db.tt/W6jqyE2i)



### UOM Factor ###
* Unit of Measure Factor
* A numerical value that corresponds directly to UOM, most commonly as follows:
* **Each** = 1 (e.g. the UOM for a syringe is "Each" and the UOM factor is "1" meaning they are each sold seperately)
* **Set** = commonly 2-8 and usually varying styles of one instrument (e.g. the UOM for a Tuning Fork Set is "Set" and the UOM Factor is "5" meaning the Set contains 5 differently pitched forks)
* **Pack** = commonly 12 or 24 and usually of the same instrument (e.g. the UOM for Suture Needles may be "Pack" and the UOM Factor may be "12" meaning the Pack contains 12 identical Suture Needles)
* **Box** = commonly higher quantities than in a Pack and usually of the same instrument (e.g. the UOM for Disposable Blades may be "Box" and the UOM Factor may be "100" meaning the Box contains 100 of identical Disposable Blades)
* **Case** = commonly highest quantities (e.g. the UOM for a disposable toothbrush may be "Case" and the UOM Factor may be "144" meaning there are 144 disposable toothbrushes in the Case)



### Additional Description ###
* Generally details about an instrument that do not apply to any other established fields


### Instrument Type ###
* 


### Width ###
* Generally a measurement of specific instruments for which width is a differentiating characteristic (e.g. Traction Bows, Surgical Trays, Sterilization Trays, Baskets, Retractors)


### Height / Depth ###
* Measurement applicable to specific instruments for which Height or Depth is a differentiating characteristic (e.g. Surgical Trays, Sterilization Trays, Aorta Clamps)
* May be indicated in inches or millimeters
* "Millimeters" should be reflected as a lowercase abbreviation (e.g. "mm")
* "Inches" should be reflected with the inches symbol (")
* No ending zero after whole numbers (e.g. "2mm" not "2.0mm")


### Diameter ###
* Measurement applicable to specific instruments for which Diameter is a differentiating characteristic (e.g. Wire, Wire in Mesh Baskets, Cleaning Brushes, Ophthalmic Instruments etc.)
* Most commonly indicated in millimeters
* "Millimeters" should be reflected as a lowercase abbreviation (e.g. "mm")
* May be indicated in inches for larger instruments
* "Inches" should be reflected with the inches symbol (")
* No ending zero after whole numbers (e.g. "2mm" not "2.0mm")

### Volume ###
* Measurement applicable to specific instruments for which Volume is a differentiating characteristic (e.g. Medicine Cup, Pitcher, Bowl, Basin, Syringe, Care & Cleaning Products, Solutions)


### Action ###
* 
*

