# Function: <code>vprintk_emit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d84b0)
Location: kernel/printk/printk.c:1659
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk
  - kernel/printk/printk.c:printk_emit
  - kernel/printk/printk.c:printk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810d84b0-ffffffff810d89ce: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dcf70)
Location: kernel/printk/printk.c:1736
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
  - kernel/printk/printk.c:printk_emit
  - kernel/printk/printk.c:vprintk
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810dcf70-ffffffff810dd474: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3610)
Location: kernel/printk/printk.c:1668
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_deferred
  - kernel/printk/printk.c:printk_emit
  - kernel/printk/printk.c:vprintk
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810e3610-ffffffff810e3aab: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3490)
Location: kernel/printk/printk.c:1695
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_emit
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810e3490-ffffffff810e3823: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810eb150)
Location: kernel/printk/printk.c:1683
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_emit
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810eb150-ffffffff810eb4e3: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4710)
Location: kernel/printk/printk.c:1881
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_emit
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810f4710-ffffffff810f4951: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ffea0)
Location: kernel/printk/printk.c:1893
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810ffea0-ffffffff81100107: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108660)
Location: kernel/printk/printk.c:1944
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81108660-ffffffff811088d8: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114a40)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81114a40-ffffffff81114cb8: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811201c0)
Location: kernel/printk/printk.c:1979
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff811201c0-ffffffff81120322: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b1c0)
Location: kernel/printk/printk.c:2060
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff8111b1c0-ffffffff8111b2df: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b760)
Location: kernel/printk/printk.c:2136
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff8111b760-ffffffff8111b9ba: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vprintk_emit(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2209
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81cac4e8-ffffffff81cac524: vprintk_emit.cold (STB_LOCAL)
ffffffff8113be60-ffffffff8113c08a: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vprintk_emit(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2230
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81e5c9c0-ffffffff81e5c9e9: vprintk_emit.cold (STB_LOCAL)
ffffffff8115ec50-ffffffff8115ee2f: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vprintk_emit(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2318
Inline: False
Direct callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_printk_emit
```
**Symbols:**

```
ffffffff82058b48-ffffffff82058b71: vprintk_emit.cold (STB_LOCAL)
ffffffff81191bb0-ffffffff81191d8f: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vprintk_emit(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2266
Inline: False
Direct callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_printk_emit
```
**Symbols:**

```
ffffffff820d73e0-ffffffff820d7409: vprintk_emit.cold (STB_LOCAL)
ffffffff811a3450-ffffffff811a362f: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vprintk_emit(int facility, int level, const struct dev_printk_info *dev_info, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2262
Inline: False
Direct callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_printk_emit
```
**Symbols:**

```
ffffffff821b2662-ffffffff821b269f: vprintk_emit.cold (STB_LOCAL)
ffffffff811b21c0-ffffffff811b23c3: vprintk_emit (STB_GLOBAL)
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
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010175a38)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffff800010175a38-ffff800010175d84: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c7c80)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
c03c7c80-c03c7fa4: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cf460)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
c0000000001cf460-c0000000001cf780: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe0001111fc)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_default
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffe0001111fc-ffffffe000111484: vprintk_emit (STB_GLOBAL)
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
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110d020)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff8110d020-ffffffff8110d298: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fdde0)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff810fdde0-ffffffff810fe011: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110af10)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff8110af10-ffffffff8110b188: vprintk_emit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vprintk_emit(int facility, int level, const char *dict, size_t dictlen, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811163b0)
Location: kernel/printk/printk.c:1954
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff811163b0-ffffffff81116654: vprintk_emit (STB_GLOBAL)
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
