# Function: <code>vprintk_func</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119ea45)
Location: kernel/printk/internal.h:34
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811ae490)
Location: kernel/printk/internal.h:34
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810e4ff0)
Location: kernel/printk/printk_safe.c:364
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff810e4ff0-ffffffff810e5048: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810ed250)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff810ed250-ffffffff810ed2a8: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810f5520)
Location: kernel/printk/printk_safe.c:373
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff810f5520-ffffffff810f55d5: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81100cc0)
Location: kernel/printk/printk_safe.c:373
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff81100cc0-ffffffff81100d7c: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81109460)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff81109460-ffffffff8110951c: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81115830)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff81115830-ffffffff811158ec: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811211d0)
Location: kernel/printk/printk_safe.c:362
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff811211d0-ffffffff811212cd: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111be50)
Location: kernel/printk/printk_safe.c:370
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff8111be50-ffffffff8111bf4b: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff800010176fc8)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffff800010176fc8-ffff800010177128: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c03c8d48)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
c03c8d48-c03c8e3c: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c0000000001d0910)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
c0000000001d0910-c0000000001d0ac0: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffe000111f7e)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffe000111f7e-ffffffe0001120b4: vprintk_func (STB_GLOBAL)
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
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110de10)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff8110de10-ffffffff8110decc: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810feb70)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff810feb70-ffffffff810fec2c: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110bd00)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff8110bd00-ffffffff8110bdbc: vprintk_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vprintk_func(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81117210)
Location: kernel/printk/printk_safe.c:361
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk
  - kernel/printk/printk.c:vprintk
```
**Symbols:**

```
ffffffff81117210-ffffffff811172ee: vprintk_func (STB_GLOBAL)
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
