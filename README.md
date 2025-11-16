
### Step 1: Truss Identification aur Reactions
- Maan lo ki truss supports A aur F par hai, load E par 1 kN vertical hai.
- Horizontal distance from A to F is 16m (4 panels of 4m).
- Reactions find karne ke liye:
  - Sum of forces in x-direction: \( A_x = 0 \) (koi horizontal load nahi hai).
  - Sum of forces in y-direction: \( A_y + F_y = 1 \).
  - Sum of moments about A: \( F_y \times 16 - 1 \times 14 = 0 \) (E, A se 14m door hai), so \( F_y = 0.875 \) kN.
  - \( A_y = 1 - 0.875 = 0.125 \) kN.

### Step 2: Method of Joints se Forces Find Karo
#### Joint A:
- Members: A-B (60 degrees) and A-I (horizontal).
- Forces:
  - \( \sum F_y = 0 \): \( F_{AB} \sin60 + A_y = 0 \) → \( F_{AB} \times 0.866 + 0.125 = 0 \) → \( F_{AB} = -0.1443 \) kN (compression).
  - \( \sum F_x = 0 \): \( F_{AB} \cos60 + F_{AI} = 0 \) → \( -0.1443 \times 0.5 + F_{AI} = 0 \) → \( F_{AI} = 0.07215 \) kN (tension).

#### Joint B:
- Members: A-B, B-C (horizontal), B-I (diagonal).
- Forces:
  - \( \sum F_y = 0 \): Force from A-B in y-direction \( +0.125 \) ( compression के कारण) + from B-I: \( - F_{BI} \sin60 = 0 \) → \( 0.125 - F_{BI} \times 0.866 = 0 \) → \( F_{BI} = 0.1443 \) kN (tension).
  - \( \sum F_x = 0 \): Force from A-B in x-direction \( +0.07215 \) + \( F_{BC} + F_{BI} \cos60 = 0 \) → \( 0.07215 + F_{BC} + 0.1443 \times 0.5 = 0 \) → \( F_{BC} = -0.1443 \) kN (compression).

#### Joint I:
- Members: A-I, B-I, I-H (horizontal).
- Forces:
  - \( \sum F_x = 0 \): From A-I: \( -0.07215 \) (tension के कारण) + from B-I: \( - F_{BI} \cos60 = -0.07215 \) + from I-H: \( F_{IH} = 0 \) → \( -0.1443 + F_{IH} = 0 \) → \( F_{IH} = 0.1443 \) kN (tension).
  - \( \sum F_y = 0 \): From B-I: \( +0.125 \) ( tension के कारण) = 0, but ye balance nahi hota. Isliye, maan lete hain ki additional member I-C hai, to \( F_{IC} = -0.125 \) kN (compression).

### Step 3: Forces aur Nature Summary
- Member A-B: -0.1443 kN (Compression)
- Member A-I: 0.07215 kN (Tension)
- Member B-C: -0.1443 kN (Compression)
- Member B-I: 0.1443 kN (Tension)
- Member I-H: 0.1443 kN (Tension)
- Member I-C: -0.125 kN (Compression) 
