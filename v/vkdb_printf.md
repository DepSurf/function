# Function: <code>vkdb_printf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81131ea0)
Location: kernel/debug/kdb/kdb_io.c:551
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81131ea0-ffffffff81132892: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8113a210)
Location: kernel/debug/kdb/kdb_io.c:551
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8113a210-ffffffff8113ac91: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81143fb0)
Location: kernel/debug/kdb/kdb_io.c:552
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81143fb0-ffffffff81144a49: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81145cd0)
Location: kernel/debug/kdb/kdb_io.c:552
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81145cd0-ffffffff81146687: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81152610)
Location: kernel/debug/kdb/kdb_io.c:552
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81152610-ffffffff81152fb8: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:552
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff811626ba-ffffffff81162760: vkdb_printf.cold.3 (STB_LOCAL)
ffffffff81161210-ffffffff81161b07: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8116f59a-ffffffff8116f640: vkdb_printf.cold.3 (STB_LOCAL)
ffffffff8116e040-ffffffff8116e937: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8117c33c-ffffffff8117c3dd: vkdb_printf.cold (STB_LOCAL)
ffffffff8117ae60-ffffffff8117b73a: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff811881dc-ffffffff8118827d: vkdb_printf.cold (STB_LOCAL)
ffffffff81186cf0-ffffffff811875ca: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:583
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8119c724-ffffffff8119c7d3: vkdb_printf.cold (STB_LOCAL)
ffffffff8119b560-ffffffff8119bc8c: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:583
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81be4d35-ffffffff81be4de4: vkdb_printf.cold (STB_LOCAL)
ffffffff811986e0-ffffffff81198daf: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:583
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81bd6ba9-ffffffff81bd6c58: vkdb_printf.cold (STB_LOCAL)
ffffffff81199530-ffffffff81199bf1: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:583
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81cb3bdf-ffffffff81cb3c8e: vkdb_printf.cold (STB_LOCAL)
ffffffff811c3310-ffffffff811c3a67: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:582
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81e64a89-ffffffff81e64b38: vkdb_printf.cold (STB_LOCAL)
ffffffff811f6b60-ffffffff811f729e: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8123ddd0)
Location: kernel/debug/kdb/kdb_io.c:596
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8123ddd0-ffffffff8123e5d2: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81254e30)
Location: kernel/debug/kdb/kdb_io.c:610
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff81254e30-ffffffff81255632: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8126ecb0)
Location: kernel/debug/kdb/kdb_io.c:612
Inline: False
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8126ecb0-ffffffff8126f4b2: vkdb_printf (STB_GLOBAL)
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
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffff8000101fcd90)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_default
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffff8000101fcd90-ffff8000101fd6c0: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c043cd84)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_default
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
c043cd84-c043d7d0: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c000000000275400)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
c000000000275400-c000000000276080: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff811807fc-ffffffff8118089d: vkdb_printf.cold (STB_LOCAL)
ffffffff8117f310-ffffffff8117fbea: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8117393c-ffffffff811739dd: vkdb_printf.cold (STB_LOCAL)
ffffffff81172460-ffffffff81172d26: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8117e5cc-ffffffff8117e66d: vkdb_printf.cold (STB_LOCAL)
ffffffff8117d0e0-ffffffff8117d9ba: vkdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vkdb_printf(enum kdb_msgsrc src, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:555
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_printf
```
**Symbols:**

```
ffffffff8118beec-ffffffff8118bf8d: vkdb_printf.cold (STB_LOCAL)
ffffffff8118aa00-ffffffff8118b2da: vkdb_printf (STB_GLOBAL)
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
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
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
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
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
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
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
