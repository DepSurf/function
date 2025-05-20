# Function: <code>bitmap_getnum</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503a80)
Location: lib/bitmap.c:516
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff81503a80-ffffffff81503af7: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521a20)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff81521a20-ffffffff81521a97: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584f49)
Location: lib/bitmap.c:524
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a2049)
Location: lib/bitmap.c:524
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8fe3)
Location: lib/bitmap.c:524
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816120a0)
Location: lib/bitmap.c:645
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
  - lib/bitmap.c:bitmap_parse_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de550)
Location: lib/bitmap.c:661
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817ce851)
Location: lib/bitmap.c:672
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180cd6a)
Location: lib/bitmap.c:672
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap-str.c (ffffffff818619ba)
Location: lib/bitmap-str.c:239
Inline: True
Inline callers:
  - lib/bitmap-str.c:bitmap_parselist
  - lib/bitmap-str.c:bitmap_parselist
  - lib/bitmap-str.c:bitmap_parselist
  - lib/bitmap-str.c:bitmap_parselist
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b140)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffff80001062b140-ffff80001062b1c8: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d2474)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
c07d2474-c07d2500: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd750)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
c0000000007cd750-c0000000007cd7f4: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045bcd6)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffe00045bcd6-ffffffe00045bd2a: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a000)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff8151a000-ffffffff8151a077: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a2f0)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff8150a2f0-ffffffff8150a367: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516090)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff81516090-ffffffff81516107: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *bitmap_getnum(const char *str, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f820)
Location: lib/bitmap.c:536
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff8152f820-ffffffff8152f897: bitmap_getnum (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
