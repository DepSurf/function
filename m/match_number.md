# Function: <code>match_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff813f8400)
Location: lib/parser.c:128
Inline: False
Direct callers:
  - lib/parser.c:match_int
  - lib/parser.c:match_octal
  - lib/parser.c:match_hex
```
**Symbols:**

```
ffffffff813f8400-ffffffff813f84cb: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8143f2a0)
Location: lib/parser.c:128
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff8143f2a0-ffffffff8143f36c: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8145c2f0)
Location: lib/parser.c:128
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff8145c2f0-ffffffff8145c3bc: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff814617c0)
Location: lib/parser.c:128
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff814617c0-ffffffff8146188c: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8148d6c0)
Location: lib/parser.c:128
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff8148d6c0-ffffffff8148d78c: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff814c2410)
Location: lib/parser.c:128
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff814c2410-ffffffff814c24da: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff814d6af0)
Location: lib/parser.c:128
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff814d6af0-ffffffff814d6b95: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff81502930)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff81502930-ffffffff815029d3: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff815208d0)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff815208d0-ffffffff81520973: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81583b30)
Location: lib/parser.c:126
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff81583b30-ffffffff81583bdd: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815a09b0)
Location: lib/parser.c:126
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff815a09b0-ffffffff815a0a5d: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815a7800)
Location: lib/parser.c:128
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff815a7800-ffffffff815a78a9: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81610740)
Location: lib/parser.c:129
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff81610740-ffffffff816107e9: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff816dcbf0)
Location: lib/parser.c:129
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff816dcbf0-ffffffff816dccad: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff817cc860)
Location: lib/parser.c:138
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff817cc860-ffffffff817cc91a: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8180ac70)
Location: lib/parser.c:138
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff8180ac70-ffffffff8180ad2a: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81851450)
Location: lib/parser.c:138
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff81851450-ffffffff8185150a: match_number (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffff800010629e00)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffff800010629e00-ffff800010629eb8: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int match_number(substring_t *s, int *result, int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (c07d10e0)
Location: lib/parser.c:126
Inline: False
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
c07d10e0-c07d1184: match_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (c0000000007cbb90)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
c0000000007cbb90-c0000000007cbc7c: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffe00045a926)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffe00045a926-ffffffe00045a99c: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff81518eb0)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff81518eb0-ffffffff81518f53: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff815091b0)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff815091b0-ffffffff81509253: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff81514f40)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff81514f40-ffffffff81514fe3: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/parser.c (ffffffff8152e6b0)
Location: lib/parser.c:126
Inline: True
Direct callers:
  - lib/parser.c:match_hex
  - lib/parser.c:match_octal
  - lib/parser.c:match_int
```
**Symbols:**

```
ffffffff8152e6b0-ffffffff8152e753: match_number.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
