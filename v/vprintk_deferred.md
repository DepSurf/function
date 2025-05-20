# Function: <code>vprintk_deferred</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4690)
Location: kernel/printk/printk.c:2723
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810e4690-ffffffff810e46d3: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ec950)
Location: kernel/printk/printk.c:2717
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810ec950-ffffffff810ec993: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4b20)
Location: kernel/printk/printk.c:2898
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff810f4b20-ffffffff810f4b63: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811002d0)
Location: kernel/printk/printk.c:2910
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff811002d0-ffffffff81100313: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108ab0)
Location: kernel/printk/printk.c:2975
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff81108ab0-ffffffff81108af7: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114e90)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff81114e90-ffffffff81114ed7: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81120830)
Location: kernel/printk/printk.c:3053
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff81120830-ffffffff81120882: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b7d0)
Location: kernel/printk/printk.c:3132
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff8111b7d0-ffffffff8111b820: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111be90)
Location: kernel/printk/printk.c:3196
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff8111be90-ffffffff8111bee0: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3260
Inline: False
Direct callers:
  - kernel/printk/printk.c:_printk_deferred
```
**Symbols:**

```
ffffffff81cac602-ffffffff81cac616: vprintk_deferred.cold (STB_LOCAL)
ffffffff8113c2b0-ffffffff8113c30c: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3516
Inline: False
Direct callers:
  - kernel/printk/printk.c:_printk_deferred
```
**Symbols:**

```
ffffffff81e5cb5c-ffffffff81e5cb71: vprintk_deferred.cold (STB_LOCAL)
ffffffff8115f420-ffffffff8115f47a: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119270a)
Location: kernel/printk/printk.c:3779
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
```
**Symbols:**

```
ffffffff82058bd5-ffffffff82058bea: vprintk_deferred.cold (STB_LOCAL)
ffffffff81192630-ffffffff8119268a: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3faa)
Location: kernel/printk/printk.c:3820
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
```
**Symbols:**

```
ffffffff820d746d-ffffffff820d7482: vprintk_deferred.cold (STB_LOCAL)
ffffffff811a3ed0-ffffffff811a3f2a: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b3627)
Location: kernel/printk/printk.c:3943
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff811b3580-ffffffff811b35ae: vprintk_deferred (STB_GLOBAL)
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
int vprintk_deferred(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010175fe0)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffff800010175fe0-ffff800010176040: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c8238)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
c03c8238-c03c827c: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cfa70)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
c0000000001cfa70-c0000000001cfac4: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe000111644)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffe000111644-ffffffe00011168a: vprintk_deferred (STB_GLOBAL)
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
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110d470)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff8110d470-ffffffff8110d4b7: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe1f0)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff810fe1f0-ffffffff810fe237: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b360)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff8110b360-ffffffff8110b3a7: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vprintk_deferred(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116840)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
```
**Symbols:**

```
ffffffff81116840-ffffffff81116870: vprintk_deferred (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
