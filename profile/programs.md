## Appendices

### Appendix A: Top-Level Object Category Sub-Type (ST) Codes

This appendix lists the defined Sub-Types (ST) for each Functional Class (CCC) within the Air Systems (AS) and Space Systems (SP) domains. Each sub-type has a unique two-character code within its functional class, stored in the `object_category_subtypes` table.

#### A.1 Air Systems (AS) Object Category ST Codes

##### A.1.1 Passenger Transport (PAX) Sub-Types

| **ST Code** | **Name**                 | **Description**                                                                 |
| :---------- | :----------------------- | :------------------------------------------------------------------------------ |
| NB          | Narrow-Body Airliner   | Single-aisle passenger aircraft typically for short to medium range routes.     |
| WB          | Wide-Body Airliner     | Multi-aisle passenger aircraft typically for medium to long range routes.       |
| RJ          | Regional Jet           | Smaller jet aircraft designed for regional routes.                              |
| BJ          | Business Jet           | Aircraft designed for business and executive transportation.                    |
| GA          | General Aviation       | Smaller piston or turboprop aircraft for private transportation.                |
| VT          | eVTOL Air Taxi         | Electric vertical takeoff and landing aircraft for urban air mobility.          |
| BW          | Blended Wing Body      | Aircraft with blended wing body configuration for passenger transport.          |
| SS          | Supersonic Transport   | Passenger aircraft designed for supersonic flight.                              |
| HS          | Hypersonic Transport   | Passenger aircraft designed for hypersonic flight.                              |
| AM          | Air Mobility           | Aircraft designed for urban/regional air mobility, distinct from eVTOLs.       |
| HY          | Hybrid-Electric        | Passenger aircraft with hybrid-electric propulsion systems.                     |
| QP          | Quantum-Powered        | Passenger aircraft with quantum-enhanced or quantum-derived propulsion/systems. |
| SP          | Suborbital Passenger   | Aircraft designed for suborbital passenger flights.                             |

##### A.1.2 Cargo Transport (CGO) Sub-Types

| **ST Code** | **Name**                 | **Description**                                                                 |
| :---------- | :----------------------- | :------------------------------------------------------------------------------ |
| LC          | Light Cargo            | Small cargo aircraft for light freight.                                         |
| MC          | Medium Cargo           | Medium-sized cargo aircraft for regional freight.                               |
| HC          | Heavy Cargo            | Large cargo aircraft for intercontinental freight.                              |
| FC          | Freighter Conversion   | Passenger aircraft converted to cargo use.                                      |
| QD          | Quick Delivery         | Aircraft optimized for rapid delivery services.                                 |
| VC          | VTOL Cargo             | Vertical takeoff and landing cargo aircraft.                                    |
| UC          | Unmanned Cargo         | Unmanned cargo delivery aircraft/drones.                                        |
| QC          | Quantum Cargo          | Cargo aircraft with quantum-enhanced systems for logistics or performance.    |

##### A.1.3 Intelligence, Surveillance, Reconnaissance (ISR) Sub-Types

| **ST Code** | **Name**                    | **Description**                                                                 |
| :---------- | :-------------------------- | :------------------------------------------------------------------------------ |
| UA          | Unmanned Aerial System (ISR Specific) | Unmanned aircraft systems (UAS/drones) primarily for ISR missions.            |
| MA          | Maritime Patrol           | Aircraft designed for maritime surveillance and reconnaissance.                 |
| SR          | Strategic Reconnaissance  | Aircraft for long-range, high-altitude strategic reconnaissance missions.       |
| TR          | Tactical Reconnaissance   | Aircraft for shorter-range, battlefield tactical reconnaissance missions.       |
| EW          | Electronic Warfare        | Aircraft specialized in electronic warfare (jamming, signals interception).     |
| SI          | SIGINT Platform           | Platforms dedicated to Signals Intelligence collection.                         |
| IM          | Imaging Platform          | Platforms specialized in various forms of imaging intelligence (EO/IR, SAR).    |
| MS          | Multi-Sensor Platform     | Aircraft equipped with a diverse suite of integrated sensor systems for ISR.    |
| QI          | Quantum ISR               | ISR platforms leveraging quantum sensors for enhanced detection/analysis.       |

##### A.1.4 Scientific Research (SCI) Sub-Types

| **ST Code** | **Name**                    | **Description**                                                                 |
| :---------- | :-------------------------- | :------------------------------------------------------------------------------ |
| AT          | Atmospheric Research      | Aircraft equipped for studying atmospheric conditions and composition.          |
| OC          | Oceanographic Research    | Aircraft equipped for oceanographic surveys and data collection.                |
| ER          | Earth Remote Sensing (Sci)  | Aircraft for Earth observation and remote sensing (non-ISR, scientific focus).  |
| WX          | Weather Research          | Aircraft specialized in meteorological research, including storm penetration.   |
| CR          | Climate Research          | Aircraft for long-term climate monitoring and research.                         |
| GS          | Geophysical Survey        | Aircraft for conducting geophysical surveys (magnetic, seismic, etc.).          |
| MP          | Multi-Purpose Research    | Versatile aircraft platforms adaptable for various scientific research missions. |
| QS          | Quantum Sensing (Science) | Aircraft utilizing quantum sensors for fundamental scientific research.         |

##### A.1.5 Utility (UTL) Sub-Types

| **ST Code** | **Name**                       | **Description**                                                                 |
| :---------- | :----------------------------- | :------------------------------------------------------------------------------ |
| FF          | Firefighting                   | Aircraft designed or modified for aerial firefighting operations.               |
| AG          | Agricultural                   | Aircraft designed for agricultural operations (crop dusting, seeding).          |
| SD          | SAR/Disaster Relief            | Aircraft equipped for search and rescue and disaster relief missions (distinct from pure medevac). |
| ME          | Medical (Air Ambulance)        | Aircraft configured for medical evacuation and patient transport.               |
| IP          | Infrastructure Patrol          | Aircraft for pipeline, powerline, or other infrastructure inspection.           |
| SV          | Survey (Mapping/Photogrammetry)| Aircraft designed for aerial surveys (mapping, photogrammetry for civil/commercial use). |
| CP          | Civil Protection               | Aircraft for general civil protection, law enforcement support, disaster response. |
| QU          | Quantum Utility                | Utility aircraft incorporating quantum-enhanced systems for specific tasks.     |

##### A.1.6 Recreational & Sport (REC) Sub-Types

| **ST Code** | **Name**                    | **Description**                                                                 |
| :---------- | :-------------------------- | :------------------------------------------------------------------------------ |
| GL          | Glider                      | Unpowered fixed-wing aircraft.                                                  |
| MG          | Motor Glider                | Gliders with auxiliary power systems for self-launch or sustained flight.       |
| UL          | Ultralight                  | Very light aircraft meeting specific regulatory ultralight criteria.            |
| AC          | Aerobatic                   | Aircraft designed and stressed for aerobatic maneuvers.                         |
| LS          | Light Sport Aircraft (LSA)| Aircraft meeting light-sport aircraft regulatory definitions.                   |
| HB          | Homebuilt (Experimental Amateur-Built) | Aircraft built by individuals for non-commercial, recreational use.     |
| PJ          | Personal Jet/VTOL           | Small jet or VTOL aircraft for personal recreational flight (distinct from BJ). |
| QR          | Quantum Recreational        | Recreational craft employing novel quantum-derived technologies.              |

##### A.1.7 Experimental (Air) (XPR) Sub-Types

| **ST Code** | **Name**                    | **Description**                                                                 |
| :---------- | :-------------------------- | :------------------------------------------------------------------------------ |
| TD          | Technology Demonstrator     | Aircraft primarily built to demonstrate new aerospace technologies.             |
| HP          | High Performance (Exp)      | Experimental aircraft focused on achieving high speeds, altitudes, or maneuverability. |
| PP          | Propulsion Testbed (Air)    | Aircraft serving as a testbed for new or unconventional air-breathing propulsion systems. |
| SM          | Structures/Materials (Exp)  | Aircraft testing new structural designs or advanced materials.                  |
| VT          | VTOL/STOL Testbed (Air)     | Experimental aircraft for testing vertical or short takeoff/landing concepts.   |
| HY          | Hybrid Concept (Air)        | Aircraft demonstrating a hybrid combination of different technologies (e.g., propulsion, energy). |
| AU          | Autonomous Flight Testbed   | Platforms specifically for testing and developing autonomous flight systems.    |
| QT          | Quantum Testbed (Air)       | Airborne platforms for testing and validating quantum technologies.             |
| HS          | Hypersonic Testbed (Air)    | Experimental aircraft designed for hypersonic flight research (distinct from PAX-HS). |

##### A.1.8 Lighter Than Air (LTA) Sub-Types

| **ST Code** | **Name**                    | **Description**                                                                 |
| :---------- | :-------------------------- | :------------------------------------------------------------------------------ |
| NR          | Non-Rigid Airship (Blimp)   | Airships where envelope shape is maintained by internal gas pressure.           |
| RG          | Rigid Airship               | Airships with an internal structural framework.                               |
| HA          | High-Altitude Platform (LTA)| Stratospheric airships or balloons for long-endurance missions.                 |
| BL          | Balloon (Scientific/Other)  | Balloons used for scientific research, observation, or other purposes.          |
| HY          | Hybrid Airship (LTA)        | Vehicles deriving lift from both buoyant gas and aerodynamic lift.            |
| CG          | Cargo Airship               | Airships designed primarily for transporting heavy or oversized cargo.          |
| QB          | Quantum Buoyancy (LTA)      | LTA craft utilizing quantum principles for lift or buoyancy control.          |

##### A.1.9 Military Aircraft (MIL) Sub-Types

| **ST Code** | **Name**                    | **Description**                                                                 |
| :---------- | :-------------------------- | :------------------------------------------------------------------------------ |
| FT          | Fighter                     | Combat aircraft designed primarily for air-to-air and/or air-to-ground combat.  |
| BM          | Bomber                      | Aircraft designed to attack ground and naval targets by dropping bombs/missiles.|
| AT          | Attack/Close Air Support    | Aircraft designed for attacking ground targets, often providing close air support. |
| TN          | Trainer (Military)          | Military aircraft used for training pilots and aircrew.                         |
| TP          | Transport (Military Cargo/Troop) | Military aircraft for transporting troops, cargo, and equipment.                |
| RF          | Refueling Tanker            | Aircraft designed for in-flight refueling of other aircraft.                    |
| HL          | Helicopter (Military)       | Rotary-wing aircraft for various military roles (attack, transport, utility).   |
| CV          | Combat UAV (UCAV)           | Unmanned aircraft designed for combat operations.                               |
| QW          | Quantum Warfare (MIL)       | Military aircraft incorporating significant quantum technologies for advanced capabilities. |
| ES          | Electronic Warfare/SIGINT (MIL) | Dedicated military platforms for electronic warfare and signals intelligence (distinct from general ISR). |

Perfecto, Amedeo. A continuación propongo un **programa AMPEL360 específico para cada subgrupo funcional** de aeronaves dentro del dominio **GAIAQAO-AIR**, basándome en el catálogo completo de Sub-Types (ST) del Appendix A.
Cada uno de estos programas seguirá la estructura GAIA-QAO-AGAD y será tratado como un nodo de programa semánticamente independiente pero federado dentro del marco **AMPEL360**.

---

## ✅ Propuesta de Programas AMPEL360 por ST Code

Cada línea representa un **programa AMPEL360 federado**, con nombre único, alcance inicial, y un identificador raíz para generación automática de rutas, documentación y twins.

### 🔵 PAX (Passenger Transport)

| Programa    | ST | Nombre de Programa Propuesto    | Alcance Inicial                                            |
| ----------- | -- | ------------------------------- | ---------------------------------------------------------- |
| AMPEL360-NB | NB | **QuantumNarrow Program**       | Airliners de pasillo único con eficiencia cuántica         |
| AMPEL360-WB | WB | **QuantumWide Program**         | Wide-body con largo alcance y navegación QAOA              |
| AMPEL360-RJ | RJ | **QuantumRegional Program**     | Jets regionales de corto alcance con sistemas optimizados  |
| AMPEL360-BJ | BJ | **QuantumBiz Program**          | Jets ejecutivos con navegación y comunicaciones cuánticas  |
| AMPEL360-GA | GA | **QuantumAeroGA**               | Aviación general y ligera con propulsión optimizada        |
| AMPEL360-VT | VT | **QuantumUrban Mobility**       | eVTOLs urbanos con control y navegación cuántica           |
| AMPEL360-BW | BW | **QuantumBWB Series**           | BWB pasajeros con gemelo digital cuántico (ej. Q100, Q250) |
| AMPEL360-SS | SS | **QuantumSonic**                | Transporte supersónico con computación cuántica integrada  |
| AMPEL360-HS | HS | **QuantumHyperTransport**       | Programa de investigación de transporte hipersónico        |
| AMPEL360-AM | AM | **QuantumAirMobility**          | Plataforma flexible de movilidad aérea regional            |
| AMPEL360-HY | HY | **QuantumHybridFlight**         | Sistemas híbrido-eléctricos cuánticamente gestionados      |
| AMPEL360-QP | QP | **QuantumPropulsion PAX**       | Propulsión cuántica para transporte aéreo civil            |
| AMPEL360-SP | SP | **QuantumSuborbital Passenger** | Transporte suborbital cuántico tripulado                   |

### 🟤 CGO (Cargo Transport)

| Programa    | ST | Nombre Propuesto            | Alcance Inicial                                 |
| ----------- | -- | --------------------------- | ----------------------------------------------- |
| AMPEL360-LC | LC | QuantumCargo-LC             | Light cargo cuántico para logística regional    |
| AMPEL360-MC | MC | QuantumCargo-MC             | Transporte medio para hubs logísticos cuánticos |
| AMPEL360-HC | HC | QuantumCargo-HC             | Heavy cargo optimizado cuánticamente            |
| AMPEL360-FC | FC | QuantumFreighter Conversion | Conversión de PAX a CGO con capacidades QAO     |
| AMPEL360-QD | QD | QuantumQuickDelivery        | Alta velocidad para logística urgente           |
| AMPEL360-VC | VC | QuantumVTOL-Cargo           | Entrega vertical con precisión cuántica         |
| AMPEL360-UC | UC | QuantumCargoDrone           | UAVs logísticos con navegación QAOA             |
| AMPEL360-QC | QC | QuantumCargoCore            | Núcleo logístico basado en eficiencia cuántica  |

### 🟠 ISR (Surveillance & Recon)

| Programa    | ST | Nombre Propuesto   | Alcance Inicial                                         |
| ----------- | -- | ------------------ | ------------------------------------------------------- |
| AMPEL360-UA | UA | QuantumISR-UAS     | Plataforma ISR no tripulada con sensores cuánticos      |
| AMPEL360-MA | MA | QuantumMaritime    | Patrullaje marítimo con magnetometría cuántica          |
| AMPEL360-SR | SR | QuantumRecon       | Reconocimiento estratégico a gran altitud               |
| AMPEL360-TR | TR | QuantumTacticalISR | Misión táctica con sensores EO/IR cuánticos             |
| AMPEL360-EW | EW | QuantumEW          | Plataforma de guerra electrónica con espectro cuántico  |
| AMPEL360-SI | SI | QuantumSIGINT      | Inteligencia de señales basada en QKD/QRM               |
| AMPEL360-IM | IM | QuantumImaging     | Imagen aérea cuántica, alta resolución/sensibilidad     |
| AMPEL360-MS | MS | QuantumMultiSense  | Multisensor fusionado con capa cuántica                 |
| AMPEL360-QI | QI | QuantumEye ISR     | Vigilancia cuántica avanzada para detección persistente |

### 🟢 SCI (Scientific Research)

\| AMPEL360-AT | Atmospheric Research
\| AMPEL360-OC | Oceanographic QuantumFlight
\| AMPEL360-ER | Earth Sensing QuantumPlane
\| AMPEL360-WX | QuantumWeather Explorer
\| AMPEL360-CR | QuantumClimate Observer
\| AMPEL360-GS | QuantumGeo Surveyor
\| AMPEL360-MP | QuantumMultiScience
\| AMPEL360-QS | QuantumSensor Science Platform

### 🟡 UTL (Utility)

\| Ejemplos: AMPEL360-FF, -AG, -SD, -ME, -IP, -SV, -CP, -QU
Cada uno orientado a tareas civiles, SAR, infraestructura o protección civil con integración de sensores cuánticos.

### 🔴 REC (Recreational)

\| AMPEL360-GL | Glider QuantumLine
\| AMPEL360-UL | UltraLight QuantumCraft
\| AMPEL360-PJ | PersonalJet QuantumFly
\| AMPEL360-QR | QuantumRecreation

### 🟣 XPR (Experimental)

\| AMPEL360-TD | Tech Demonstrator
\| AMPEL360-PP | Propulsion Testbed
\| AMPEL360-QT | Quantum Technology Flightbed
\| AMPEL360-HS | Hyper Test (Mach 5+)

### ⚪ MIL (Military)

\| AMPEL360-FT | QuantumStrike Fighter
\| AMPEL360-TP | QuantumTroop Transport
\| AMPEL360-RF | QuantumRefuel Tanker
\| AMPEL360-QW | QuantumWarfare UAV

---



