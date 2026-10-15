# Pehla Raasta (पहला रास्ता)

Ek chhoti, single-page website jo kisi bilkul naye insaan ko paanch kadam mein duniya samjhati hai, sawaal puchti hai, raaste dikhati hai aur aaj karne layak ek chhota kaam deti hai.

Website jawab nahi deti. Wo raaste dikhati hai aur faisla insaan par chhodti hai.

## Paanch kadam

1. **Swagat**: koi login nahi, koi sahi ya galat jawab nahi.
2. **Duniya kya hai**: insaan, rishte, paisa, kaam, samaj. Har ek 2-3 line mein.
3. **Tum kya mehsoos karte ho**: teen sawaal, har ek mein chaar options.
4. **Tumhare raaste**: chaar raaste (seekhna, haath ka hunar, logon ke saath kaam, kamai aur vyavastha), har ek ke fayde aur nuksan ke saath. Jawabon se jo zyada mel khata hai wo upar dikhta hai.
5. **Pehla kadam**: chune hue raaste par aaj hi, 20 minute se kam mein karne layak ek kaam.

## Features

- Hindi (Devanagari) aur English, upar toggle se badal sakte hain
- Mobile par achhi tarah chalti hai
- Light aur dark mode, device ki setting ke hisaab se
- Har screen par helpline note (Tele-MANAS 14416)
- Koi server, database ya account nahi. Sirf bhasha ki pasand browser mein save hoti hai.

## Chalane ka tareeka

`index.html` (ya `pehla-raasta.html`) file ko kisi bhi browser mein kholein. Fonts ke liye internet chahiye (Google Fonts).

## Online daalna (free)

- **Netlify Drop**: app.netlify.com/drop par file drag karein
- **Vercel** ya **GitHub Pages**: file ko repository mein daalkar deploy karein

File ka naam `index.html` rakhein taaki seedha khule.

## Text badalna

Saara text file ke andar `D` naam ke object mein hai.

- `D.hi` mein Hindi text
- `D.en` mein English text

Har kadam ke liye alag hissa hai: `s1` se `s5`. Sawaal `s3.qs` mein, raaste `s4.paths` mein, aur pehle kadam ke kaam `s5.actions` mein hain. Naya raasta jodna ho to `s4.paths`, `s5.actions` aur `PATH_ORDER` mein ek hi key daalein, aur sawaalon ke options mein wahi key lagayein.

## Rang aur font badalna

`<style>` ke shuru mein `:root` block mein saare rang aur fonts tokens ki tarah likhe hain. Dark mode ke rang usi ke neeche alag block mein hain.

## Test kaise karein

Pehle 5-10 aise logon ko dikhayein jo aapke target user jaise hain, aur unki saaf ijazat lein.

1. Dekhein kaun kis kadam par atakta hai.
2. Dekhein kya sawaal bina samjhaye samajh aate hain.
3. 1-2 hafte baad poochein ki pehla kadam kiya ya nahi, aur kaisa laga.
4. Jo atke, wahi cheez agle version mein badlein.

## Dhyaan rakhne wali baatein

- Ye website salah hai, faisla nahi. Kisi par ek hi "sahi" tareeka na thopein.
- Ye kisi professional madad ki jagah nahi leti. Agar koi bahut dukhi ya akela ho, helpline ka number screen par hamesha dikhta hai.
- Agar aap user ka data (naam, email) lena shuru karein, to privacy aur data use ke baare mein pehle saaf likhein.

## Aage ke vichaar

- Chhote practical kaam jodna: bank account, UPI, ticket booking, doctor se baat
- Zyada sawaal aur zyada raaste
- Users ke jawab (bina naam ke) jama karna taaki pata chale kahan log atakte hain
- Aur bhashayein
