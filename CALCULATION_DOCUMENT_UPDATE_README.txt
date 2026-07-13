SARVATHAA COURSE DOCUMENT + CALCULATION UPDATE

What was added:
1. Private PDF course notes were added inside private_course_docs/:
   - piping.pdf
   - chocolate-garnish.pdf
   - baking.pdf
   - icing-cake.pdf
   - creams.pdf
   - mousselines.pdf
   - ganache.pdf

2. The customer course page now shows:
   - Videos
   - Course Notes document viewer
   - Excel Calculation / Buying Calculator

3. Calculator improvements:
   - Clear customer help boxes explain Qty per count, Total Qty, Wastage, Final Buying Qty, Pack Size, Pack Price, Optional Revenue.
   - Pack Size column is now visible.
   - Reusable tools are treated as one-time purchase, not multiplied by batch count.
   - Ingredients and consumables are multiplied by count.
   - Optional Revenue explains profit/balance.

Where to change ingredients/tools:
Open app.py and search COURSE_CALCULATIONS.
Each course has its own items list.

Where to place real documents later:
private_course_docs/
Keep the same file names listed above unless you update COURSE_DOCUMENT_FILES in app.py.
