# Function: <code>vprintk_default</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d8b30)
Location: kernel/printk/printk.c:1846
Inline: True
```
**Symbols:**

```
ffffffff810d8b30-ffffffff810d8b6d: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dd630)
Location: kernel/printk/printk.c:1933
Inline: True
```
**Symbols:**

```
ffffffff810dd630-ffffffff810dd66d: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3c50)
Location: kernel/printk/printk.c:1825
Inline: True
```
**Symbols:**

```
ffffffff810e3c50-ffffffff810e3c97: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3830)
Location: kernel/printk/printk.c:1797
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810e3830-ffffffff810e3877: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810eb4f0)
Location: kernel/printk/printk.c:1785
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810eb4f0-ffffffff810eb537: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4aa0)
Location: kernel/printk/printk.c:1946
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810f4aa0-ffffffff810f4ae7: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81100110)
Location: kernel/printk/printk.c:1947
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81100110-ffffffff81100157: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811088e0)
Location: kernel/printk/printk.c:2002
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff811088e0-ffffffff81108927: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114cc0)
Location: kernel/printk/printk.c:2012
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81114cc0-ffffffff81114d07: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81120330)
Location: kernel/printk/printk.c:2037
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81120330-ffffffff81120351: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b2e0)
Location: kernel/printk/printk.c:2113
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8111b2e0-ffffffff8111b2ff: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b9c0)
Location: kernel/printk/printk.c:2183
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff8111b9c0-ffffffff8111b9df: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113c090)
Location: kernel/printk/printk.c:2253
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff8113c090-ffffffff8113c0af: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115ee30)
Location: kernel/printk/printk.c:2280
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff8115ee30-ffffffff8115ee5e: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81191da0)
Location: kernel/printk/printk.c:2368
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff81191da0-ffffffff81191dce: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3640)
Location: kernel/printk/printk.c:2316
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff811a3640-ffffffff811a366e: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b23e0)
Location: kernel/printk/printk.c:2316
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff811b23e0-ffffffff811b240e: vprintk_default (STB_GLOBAL)
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
int vprintk_default(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010175d88)
Location: kernel/printk/printk.c:2012
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffff800010175d88-ffff800010175e18: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c7fa4)
Location: kernel/printk/printk.c:2012
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c03c7fa4-c03c8018: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cf780)
Location: kernel/printk/printk.c:2012
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c0000000001cf780-c0000000001cf804: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vprintk_default(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe000111484)
Location: kernel/printk/printk.c:2012
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffe000111484-ffffffe0001114be: vprintk_default (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110d2a0)
Location: kernel/printk/printk.c:2012
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110d2a0-ffffffff8110d2e7: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe020)
Location: kernel/printk/printk.c:2012
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810fe020-ffffffff810fe067: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b190)
Location: kernel/printk/printk.c:2012
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110b190-ffffffff8110b1d7: vprintk_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vprintk_default(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116660)
Location: kernel/printk/printk.c:2012
Inline: True
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81116660-ffffffff811166a7: vprintk_default (STB_GLOBAL)
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
