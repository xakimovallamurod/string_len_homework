# Satr uzunligi: len()

## string_len01

Ism berilgan. Uning uzunligini `len()` yordamida qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod"
Chiqarish: 9
```

**Misol 2:**

```Python
Kirish: ism="Xakimov"
Chiqarish: 7
```

---

## string_len02

Satr berilgan. Agar uning uzunligi juft bo'lsa `True`, toq bo'lsa `False` qaytaring.

**Misol 1:**

```Python
Kirish: s="Toshkent"
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: s="Xakimov"
Chiqarish: False
```

---

## string_len03

Ikki satr a va b berilgan. Agar ularning uzunliklari teng bo'lsa `True`, aks holda `False` qaytaring.

**Misol 1:**

```Python
Kirish: a="Python", b="Django"
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: a="Allamurod", b="Xakimov"
Chiqarish: False
```

---

## string_len04

Satr s berilgan. Uzunligi s ning uzunligiga teng bo'lgan, `*` belgilaridan iborat satr qaytaring (parolni yashirish uchun).

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "*********"
```

**Misol 2:**

```Python
Kirish: s="1234"
Chiqarish: "****"
```

---

## string_len05

Ism va familiya berilgan. Ularning umumiy uzunligini qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov"
Chiqarish: 16
```

---

## string_len06

Ikki satr s1 va s2 berilgan. Qisqarog'ini qaytaring. Uzunliklari teng bo'lsa, s2 ni qaytaring.

**Misol 1:**

```Python
Kirish: s1="Allamurod", s2="Xakimov"
Chiqarish: "Xakimov"
```

**Misol 2:**

```Python
Kirish: s1="code", s2="exam"
Chiqarish: "exam"
```

---

## string_len07

Allamurod yangi parol o'ylab topdi. Agar parol uzunligi kamida 8 ta belgi bo'lsa `True`, aks holda `False` qaytaring.

**Misol 1:**

```Python
Kirish: parol="Allamurod2000"
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: parol="qwe123"
Chiqarish: False
```

---

## string_len08

Allamurod ijtimoiy tarmoqqa post yozmoqda. Matn va ruxsat etilgan maksimal uzunlik n berilgan. Agar matn uzunligi n dan oshsa `True`, aks holda `False` qaytaring.

**Misol 1:**

```Python
Kirish: matn="Bugun Python o'rgandim", n=15
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: matn="Salom", n=15
Chiqarish: False
```

---

## string_len09

Ism va familiya berilgan. Ularni orasiga bo'sh joy qo'yib birlashtiring va hosil bo'lgan satr uzunligini qaytaring.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov"
Chiqarish: 17
```

---

## string_len10

So'z berilgan. Uzunligi 5 dan kichik bo'lsa "Qisqa", 5–10 bo'lsa "O'rta", 10 dan katta bo'lsa "Uzun" qaytaring.

**Misol 1:**

```Python
Kirish: s="Olma"
Chiqarish: "Qisqa"
```

**Misol 2:**

```Python
Kirish: s="Allamurod"
Chiqarish: "O'rta"
```

**Misol 3:**

```Python
Kirish: s="Dasturlashtirish"
Chiqarish: "Uzun"
```

---

## string_len11

Satr berilgan (uzunligi 2 dan katta). Agar uzunligi toq bo'lsa o'rtadagi belgini, juft bo'lsa o'rtadagi ikkita belgini qaytaring. `len()` va indeksdan foydalaning.

**Misol 1:**

```Python
Kirish: s="Allamurod"
Chiqarish: "m"
```

**Misol 2:**

```Python
Kirish: s="Toshkent"
Chiqarish: "hk"
```

**Misol 3:**

```Python
Kirish: s="Xakimov"
Chiqarish: "i"
```

---

## string_len12

So'z berilgan. Agar uning birinchi va oxirgi belgisi bir xil bo'lsa `True`, aks holda `False` qaytaring. Oxirgi belgini `len()` yordamida toping.

**Misol 1:**

```Python
Kirish: s="radar"
Chiqarish: True
```

**Misol 2:**

```Python
Kirish: s="Allamurod"
Chiqarish: False
```

---

## string_len13

Uchta satr berilgan. Ulardan nechtasining uzunligi toq ekanini qaytaring.

**Misol 1:**

```Python
Kirish: s1="Allamurod", s2="Xakimov", s3="Toshkent"
Chiqarish: 2
```

**Misol 2:**

```Python
Kirish: s1="code", s2="exam", s3="uz"
Chiqarish: 0
```

---

## string_len14

Uchta satr berilgan. Eng uzunini qaytaring. Uzunliklari teng bo'lsa, birinchi uchraganini qaytaring.

**Misol 1:**

```Python
Kirish: s1="Allamurod", s2="Xakimov", s3="Toshkent"
Chiqarish: "Allamurod"
```

**Misol 2:**

```Python
Kirish: s1="uz", s2="code", s3="exam"
Chiqarish: "code"
```

---

## string_len15

Matn berilgan. Uni ramkaga olib qaytaring: yuqori va pastki qator "+", matn uzunligicha "-" va "+" dan, o'rta qator "|" + matn + "|" dan iborat. Qatorlarni `\n` bilan ajrating.

**Misol 1:**

```Python
Kirish: matn="Allamurod"
Chiqarish: "+---------+\n|Allamurod|\n+---------+"
```

---

## string_len16

Ism va familiya berilgan. Initsiallar va umumiy harflar sonidan iborat satr qaytaring: "<ism[0]>.<familiya[0]>. <umumiy uzunlik>".

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov"
Chiqarish: "A.X. 16"
```

---

## string_len17

Satr s va son n berilgan. Agar satr uzunligi n dan kichik bo'lsa, uni oxiriga nuqta (".") qo'shib n uzunlikkacha to'ldiring. Aks holda satrni o'zgarishsiz qaytaring.

**Misol 1:**

```Python
Kirish: s="Allamurod", n=12
Chiqarish: "Allamurod..."
```

**Misol 2:**

```Python
Kirish: s="Allamurod", n=5
Chiqarish: "Allamurod"
```

---

## string_len18

Ikki so'z berilgan. Agar ularning uzunligi teng bo'lsa "Teng" qaytaring. Aks holda "<uzun so'z> <farq> ta harfga uzun" ko'rinishidagi satrni qaytaring.

**Misol 1:**

```Python
Kirish: s1="Allamurod", s2="Xakimov"
Chiqarish: "Allamurod 2 ta harfga uzun"
```

**Misol 2:**

```Python
Kirish: s1="Olma", s2="Toshkent"
Chiqarish: "Toshkent 4 ta harfga uzun"
```

**Misol 3:**

```Python
Kirish: s1="code", s2="exam"
Chiqarish: "Teng"
```

---

## string_len19

Allamurod parollarini tekshirmoqda. Parol uzunligi 6 dan kam bo'lsa "Zaif", 6–9 bo'lsa "O'rtacha", 10 va undan ko'p bo'lsa "Kuchli" qaytaring.

**Misol 1:**

```Python
Kirish: parol="12345"
Chiqarish: "Zaif"
```

**Misol 2:**

```Python
Kirish: parol="Xakimov26"
Chiqarish: "O'rtacha"
```

**Misol 3:**

```Python
Kirish: parol="Allamurod2000!"
Chiqarish: "Kuchli"
```

---

## string_len20

Ism, familiya va tug'ilgan yil berilgan. Login yarating: ismning birinchi harfi + familiyaning birinchi harfi + tug'ilgan yil + ism va familiya umumiy uzunligi.

**Misol 1:**

```Python
Kirish: ism="Allamurod", familiya="Xakimov", yil=2000
Chiqarish: "AX200016"
```

