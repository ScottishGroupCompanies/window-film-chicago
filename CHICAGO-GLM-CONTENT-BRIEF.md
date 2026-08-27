You are writing website copy for Window Film Chicago, a window tinting/film
installation company serving Chicago, IL and 19 surrounding suburbs. Same
company as Window Film Philadelphia / Window Film Salt Lake City — real
2008 founding, real founder Martin Faith, real 8-person install team. This
is a genuine market expansion, not a new brand.

OUTPUT FORMAT: Return a single JSON object matching the schema at the
bottom of this brief. Do not include any text outside the JSON object.

## Non-negotiable facts (do not alter, do not invent alternatives)
- Company: Window Film Chicago (division of the same company operating
  Window Film Philadelphia / Salt Lake City)
- Phone: (773) 453-2005
- Email: contact@windowfilmchicago.com
- Domain: windowfilmchicago.com
- Founded: 2008 (real — Martin Faith, Glasgow-born stained-glass artisan,
  switched to window film after his own utility bill dropped from
  $8.98/day to $2.54/day)
- Team: Martin Faith (Founder/CEO), Mike Kinsey, Katie Pelowich,
  Travis Thompson, Blake Parish, Cannon Russell, Kelly Escorcia,
  Shanna Sweet — all real, reuse verbatim bios/framing, do not invent
  new team members or titles
- Manufacturer partners (real, same everywhere): 3M, LLumar, Vista,
  Solar Gard, Huper Optik, Madico, Solyx, HDClear, Hanita, Graffiti
  Shield, C-Bond, Casper

## Service area (locked)
Main page: Chicago (full page, deep local content)
Directory page: list of 20 suburbs, brief 1-line description each, no
deep individual content per suburb:
Arlington Heights, Aurora, Berwyn, Bolingbrook, Cicero, Des Plaines,
Elgin, Evanston, Mount Prospect, Naperville, Oak Lawn, Oak Park,
Orland Park, Palatine, Schaumburg, Skokie, Tinley Park, Waukegan, Wheaton
(Chicago itself is the main page, not part of the directory list)

## Regional facts to use authentically (verified correct — do not swap in
## another city's facts, do not invent stats not listed here)
- Climate: IECC Zone 5A. Cold, snowy winters (lake-effect snow off Lake
  Michigan). Hot, humid summers. High wind exposure — Chicago's
  "wind tunnel" effect between skyscrapers is a real, marketable
  phenomenon relevant to window film (wind load stress on glass).
- Transit: CTA / "the L" (Chicago's elevated train system) — NEVER
  write SEPTA, UTA, or any other city's transit system name.
- Architecture: Chicago two-flats, three-flats, courtyard apartments,
  the "Chicago bungalow belt" (iconic 1-1.5 story brick bungalows built
  1910s-1930s). NEVER write "rowhouses" — that's Philadelphia's housing
  stock, not Chicago's. This exact mistake ("Brick Rowhouse Heat
  Problem") is still live and uncorrected on the Salt Lake City site —
  do not repeat it here.
- Landmarks: Willis Tower, Millennium Park / Cloud Gate ("The Bean"),
  Chicago River, Michigan Avenue, the Loop, Navy Pier
- Real, citable climate data to use (matching the style of NWS/EPA
  citations used on other city pages):
  - Chicago avg July high: ~84°F (NWS Chicago)
  - Chicago avg January low: ~22°F (cold-climate energy-loss angle —
    single-pane vintage building stock loses heat, window film with
    low-E properties helps year-round, not just summer cooling)
  - Peak summer UV index: 8-9 (moderate-high, lower than SLC's high-
    altitude 10+, do not reuse SLC's number)
  - Lake Michigan glare/reflection off the lake is a genuine, real
    phenomenon worth mentioning for lakefront-facing properties
- Do NOT invent: crime statistics, star ratings, review counts,
  project counts, "X% of our installs are security film" style
  fabricated proportions. If you want a "why security film matters"
  angle, keep it general/qualitative, not a fabricated number.

## Tone / style (match existing site voice)
- Confident, locally-specific, benefit-led. Use real citations (NWS,
  EPA, weather.gov-style sources) the way other city pages do —
  link text like "the EPA classifies Chicago as ___" only if you are
  confident this is generally true and phrased hedged/general, not a
  fabricated specific claim.
- Section pattern per main city page (matching Salt Lake City's structure):
  1. Hero headline + subhead
  2. "[City]'s [Local Climate/Building] Problem" section — 1 intro
     paragraph + 3 bullet points + a 3-stat climate fact strip + 1
     closing paragraph mentioning "Since 2008" + service links
  3. "Why choose us" trust/expert section
  4. Commercial / Residential property-type split section
  5. "Window Film for Every Chicago Property Type" — 6 property type
     cards (homes, commercial offices, retail/storefronts, healthcare,
     schools/universities, government buildings)
  6. Brands section (reuse existing brand descriptions, no rewrite needed)
  7. Trust/why-choose-us testimonial-adjacent section
  8. "Chicago Neighborhoods We Serve" — list real Chicago neighborhoods
     (not the 19 suburbs — those go on the separate directory page).
     Use real Chicago neighborhoods: Lincoln Park, Wicker Park, Logan
     Square, Lakeview, Hyde Park, Pilsen, West Loop, etc.
  9. Resources/spec-sheet links section (reuse existing manufacturer
     PDF links as-is, no rewrite needed)

## JSON output schema
{
  "meta": {
    "title": "...",
    "description": "..."
  },
  "hero": {
    "headline": "...",
    "subhead": "..."
  },
  "climate_problem_section": {
    "headline": "...",
    "intro_paragraph": "...",
    "bullets": ["...", "...", "..."],
    "stat_strip": [
      {"number": "...", "label": "..."},
      {"number": "...", "label": "..."},
      {"number": "...", "label": "..."}
    ],
    "closing_paragraph": "..."
  },
  "why_choose_us": {
    "eyebrow": "...",
    "title": "...",
    "body": "..."
  },
  "property_types": [
    {"title": "...", "description": "..."}
  ],
  "neighborhoods_served": ["...", "..."],
  "directory_page": {
    "intro_paragraph": "...",
    "suburbs": [
      {"name": "...", "one_line_description": "..."}
    ]
  }
}
