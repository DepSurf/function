# Function: <code>vprintk_store</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4290)
Location: kernel/printk/printk.c:1828
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810f4290-ffffffff810f44a0: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ffa40)
Location: kernel/printk/printk.c:1840
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810ffa40-ffffffff810ffc50: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108190)
Location: kernel/printk/printk.c:1894
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81108190-ffffffff81108391: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114570)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81114570-ffffffff81114771: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111ffe0)
Location: kernel/printk/printk.c:1929
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8111ffe0-ffffffff811201bf: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111acf0)
Location: kernel/printk/printk.c:1959
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8111acf0-ffffffff8111b1b8: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b290)
Location: kernel/printk/printk.c:2035
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff8111b290-ffffffff8111b756: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vprintk_store(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2098
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff81cac445-ffffffff81cac487: vprintk_store.cold (STB_LOCAL)
ffffffff8113b580-ffffffff8113bb22: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vprintk_store(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2117
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff81e5c97e-ffffffff81e5c9c0: vprintk_store.cold (STB_LOCAL)
ffffffff8115e6c0-ffffffff8115ec46: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vprintk_store(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2205
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff82058b06-ffffffff82058b48: vprintk_store.cold (STB_LOCAL)
ffffffff81191600-ffffffff81191b95: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vprintk_store(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2153
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff820d739e-ffffffff820d73e0: vprintk_store.cold (STB_LOCAL)
ffffffff811a2eb0-ffffffff811a343e: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vprintk_store(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2149
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff821b252f-ffffffff821b2571: vprintk_store.cold (STB_LOCAL)
ffffffff811b0d70-ffffffff811b12fe: vprintk_store (STB_GLOBAL)
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
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010175518)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffff800010175518-ffff80001017572c: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c77f0)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c03c77f0-c03c79e4: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cec80)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c0000000001cec80-c0000000001cef54: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe000110d72)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffe000110d72-ffffffe000110f0e: vprintk_store (STB_GLOBAL)
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
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110cb50)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110cb50-ffffffff8110cd51: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd920)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810fd920-ffffffff810fdb21: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110aa40)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110aa40-ffffffff8110ac41: vprintk_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vprintk_store(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81115e50)
Location: kernel/printk/printk.c:1904
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81115e50-ffffffff81116051: vprintk_store (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct dev_printk_info *dev_info</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *dict</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t dictlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>facility, level, dict, dictlen, fmt, args</code> ➡️ <code>facility, level, dev_info, fmt, args</code>
</li>
</ul>
</details>
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
