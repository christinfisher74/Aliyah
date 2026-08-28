# Aliyah — App Build Index

## 1. Client Identity
- Client name: **Aliyah**
- Spell exactly: **Aliyah**
- Client-specific build.
- Do not modify other clients.

## 2. Existing App Program
- Preserve Aliyah's existing **12-week app program** from the Aliyah Master app.
- Do **not** add the in-person Session 3 programming to the app.
- The Trap Bar ↔ Hip Thrust and Lateral Lunge ↔ Step-Up changes discussed from Session 3 are part of Christin's in-person coaching and are **not** app programming.

## 3. Flexible Activity Logging
Add a clear **Log Activity** feature.

Aliyah can record:
- My Own Workout
- Walk
- Pilates
- Stretching / Mobility
- Other

Fields:
- Activity date
- Activity type
- Duration
- Details / notes

### Critical date requirement
- Aliyah must be able to select a **previous date** when logging.
- There must be **no 8 PM cutoff**.
- If she logs later in the evening, she can select the date on which the activity actually occurred.
- Saved activities should display chronologically.

## 4. Nutrition — Front-Load Your Day
Create an Aliyah-specific nutrition resource titled:

**Front-Load Your Day**

Purpose:
- Some days Aliyah may not get another reliable opportunity to eat.
- Encourage her to make early meals substantial rather than waiting until later and trying to catch up.
- Focus on high protein, adequate energy/calories, satisfying food, convenience, and realistic early-day meals.
- This is not a low-calorie breakfast section.

## 5. High-Protein / Higher-Calorie Breakfast Ideas
Include:
1. Egg + cheese + avocado breakfast wrap
2. Greek yogurt + granola + berries + nut butter
3. Protein oatmeal + peanut butter + banana
4. Eggs + potatoes + avocado + toast
5. High-protein breakfast sandwich
6. Cottage cheese + fruit + granola + nut butter
7. Protein smoothie with milk + Greek yogurt + banana + oats + peanut butter
8. Overnight protein oats + protein powder + nut butter

These should be substantial breakfasts, not low-calorie diet breakfasts.

## 6. Data
- Activity logs should be stored in Supabase.
- Christin should be able to see Aliyah's logged activity from Coach Hub.
- Preserve existing authentication.
- Do not unnecessarily change Supabase security/RLS.

## 7. Deployment / Cache
Fix the stale-version problem so users do not have to repeatedly delete cookies to see updated app code.
- New deployments should load the current version normally.
- Do not break authentication or Supabase sessions.
- Prefer a proper asset/version cache-busting strategy.

## 8. Do Not
- Do not add Session 3 in-person programming to the app.
- Do not modify other clients.
- Do not replace Aliyah's existing 12-week program.
- Do not unnecessarily duplicate exercises.
- Do not unnecessarily change authentication.
- Do not require cookie deletion for updates.

## 9. Final QA Checklist
- [ ] Name displays exactly as **Aliyah**
- [ ] Correct Aliyah client record loads
- [ ] Existing 12-week program loads
- [ ] Log Activity works
- [ ] My Own Workout works
- [ ] Walk works
- [ ] Pilates works
- [ ] Stretching / Mobility works
- [ ] Other works
- [ ] Previous dates can be selected
- [ ] No 8 PM cutoff
- [ ] Activity logs save to Supabase
- [ ] Activity logs are visible from Coach Hub
- [ ] Front-Load Your Day appears
- [ ] Breakfast options appear
- [ ] Updated app version loads without clearing cookies
- [ ] Aliyah client login works
- [ ] Coach Hub still works

## Source Master App
This index is based on the supplied:
`Feminine_Strength_Co_Aliyah_Master_v1 (1)(1).zip`

Source files present:
- `Feminine_Strength_Co_Aliyah_Master_v1/`
- `Feminine_Strength_Co_Aliyah_Master_v1/index.html`
- `Feminine_Strength_Co_Aliyah_Master_v1/supabase_schema_v1.sql`
- `Feminine_Strength_Co_Aliyah_Master_v1/styles.css`
- `Feminine_Strength_Co_Aliyah_Master_v1/service-worker.js`
- `Feminine_Strength_Co_Aliyah_Master_v1/README.md`
- `Feminine_Strength_Co_Aliyah_Master_v1/manifest.json`
- `Feminine_Strength_Co_Aliyah_Master_v1/app.js`
- `Feminine_Strength_Co_Aliyah_Master_v1/config.js`
