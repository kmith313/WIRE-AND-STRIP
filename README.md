# WIRE-AND-STRIP
WIRE AND STRIP DAILY CONSUMPTION REPORT

## Updates
- Oil Recovery Sheet hata di gayi hai.
- Item Master ab seedha aapki WIRE_AND_STRIP_CONSUMPTION_SAMPLE.xlsx ke 25 items (Category + Name + Unit) se banti hai. Opening Balance har worker apna alag khud bharega — kisi ke liye pehle se bhara hua nahi hoga.
- Har worker apna Receive / Issue data khud bharta hai; Dashboard me "Received" wahi data dikhata hai jo Receive Entry tab me daala gaya ho, month wise.
- XEN (Admin) "All Workers Combined" tab me sabka data alag-alag (dropdown se) ya sabko jod kar ek saath dekh sakta hai.
- Item Master tab me ab "Paste from Excel — Bulk Import" box hai — Excel se rows copy karke seedha paste karke ek click me apna Opening Balance bhar sakte hain.
- Naya: **"Wire & Strip Repair Standards"** card (Item Master tab me) — 10, 16, 25, 63, 100, 160, 250 KVA capacity ke liye Strip aur Wire ka standard (KG) dikhata hai. Koi bhi badal sakta hai, lekin pehle **"Change STD"** button dabana zaroori hai — usse pehle values locked (read-only) rehti hain.
- Naya: **"Wire & Strip Consumption"** tab (Excel jaisa hi format) — Month select karke har worker apna data bhar sakta hai. **Opening aur Receive dono editable hain** (auto-fill hoke aata hai, lekin chahe to khud change bhi kar sakte hain — Opening ka change agle mahino me automatically carry-forward hota hai). Baaki Issue to Other Division/Workshop, Consumed (New/Old) aur Repair khud bharna hai.
- Naya: **"Consumption Summary"** tab — From Month → To Month range select karke summary dekh sakte hain. Opening hamesha **"From" month** ka hi dikhta hai, baaki sab columns us poori range ka total hote hain.
- XEN ko "All Workers Combined" tab me dono report (Monthly + Range Summary) ka **combined + individual (worker-wise)** version dikhta hai.
- Table header/border ka visual glitch (do-line header overlap) fix kar diya — ab column borders bhi saaf dikhte hain, aur "Issue To" / "Consumed" group headers sahi se dikhte hain.
