# Function: <code>vprintk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d89d0)
Location: kernel/printk/printk.c:1825
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/compat.c:compat_printk
  - fs/ext4/super.c:__ext4_abort
  - fs/ecryptfs/main.c:__ecryptfs_printk
```
**Symbols:**

```
ffffffff810d89d0-ffffffff810d89f1: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dd480)
Location: kernel/printk/printk.c:1912
Inline: False
Direct callers:
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/compat.c:compat_printk
  - fs/ext4/super.c:__ext4_abort
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff810dd480-ffffffff810dd4a1: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3ab0)
Location: kernel/printk/printk.c:1804
Inline: False
Direct callers:
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff810e3ab0-ffffffff810e3ad1: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e1df0)
Location: kernel/printk/printk.c:1776
Inline: False
Direct callers:
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff810e1df0-ffffffff810e1e00: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9ef0)
Location: kernel/printk/printk.c:1764
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff810e9ef0-ffffffff810e9f00: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f21d0)
Location: kernel/printk/printk.c:1925
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff810f21d0-ffffffff810f21e0: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd920)
Location: kernel/printk/printk.c:1941
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff810fd920-ffffffff810fd930: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81105c60)
Location: kernel/printk/printk.c:1996
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff81105c60-ffffffff81105c70: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81111fe0)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff81111fe0-ffffffff81111ff0: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111d750)
Location: kernel/printk/printk.c:2031
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff8111d750-ffffffff8111d760: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811181c0)
Location: kernel/printk/printk.c:2107
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff811181c0-ffffffff811181d0: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111c150)
Location: kernel/printk/printk_safe.c:360
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/printk/printk.c:printk
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff8111c150-ffffffff8111c254: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8113c390)
Location: kernel/printk/printk_safe.c:29
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/printk/printk.c:_printk
  - kernel/time/timer_list.c:SEQ_printf
  - mm/kfence/report.c:seq_con_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff8113c390-ffffffff8113c413: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8115f510)
Location: kernel/printk/printk_safe.c:29
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/printk/printk.c:_printk
  - kernel/time/timer_list.c:SEQ_printf
  - mm/kfence/report.c:seq_con_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff8115f510-ffffffff8115f5ab: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81192820)
Location: kernel/printk/printk_safe.c:29
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/printk/printk.c:_printk
  - kernel/time/timer_list.c:SEQ_printf
  - mm/kfence/report.c:seq_con_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff81192820-ffffffff811928bb: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811a40c0)
Location: kernel/printk/printk_safe.c:29
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/printk/printk.c:_printk
  - kernel/time/timer_list.c:SEQ_printf
  - mm/kfence/report.c:seq_con_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff811a40c0-ffffffff811a415b: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811b3710)
Location: kernel/printk/printk_safe.c:29
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/printk/printk.c:_printk
  - kernel/time/timer_list.c:SEQ_printf
  - mm/kfence/report.c:seq_con_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff811b3710-ffffffff811b3784: vprintk (STB_GLOBAL)
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
int vprintk(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010172310)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffff800010172310-ffff800010172354: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vprintk(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c4ed0)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
c03c4ed0-c03c4eec: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vprintk(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cb750)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
c0000000001cb750-c0000000001cb784: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vprintk(const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010e652)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffe00010e652-ffffffe00010e684: vprintk (STB_GLOBAL)
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
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110a5c0)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff8110a5c0-ffffffff8110a5d0: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fb4a0)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff810fb4a0-ffffffff810fb4b0: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811084b0)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff811084b0-ffffffff811084c0: vprintk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vprintk(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81113850)
Location: kernel/printk/printk.c:2006
Inline: False
Direct callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/time/timer_list.c:SEQ_printf
  - fs/ecryptfs/main.c:__ecryptfs_printk
  - drivers/net/phy/phy_device.c:phy_attached_print
```
**Symbols:**

```
ffffffff81113850-ffffffff81113860: vprintk (STB_GLOBAL)
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
