# Function: <code>vt_kmsg_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f7f6a)
Location: drivers/tty/vt/vt.c:2535
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:tioclinux
Direct callers:
  - kernel/power/console.c:pm_prepare_console
  - kernel/power/console.c:pm_restore_console
```
**Symbols:**

```
ffffffff814fa660-ffffffff814fa67e: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8154b457)
Location: drivers/tty/vt/vt.c:2534
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff8154b2b0-ffffffff8154b2ce: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81577c87)
Location: drivers/tty/vt/vt.c:2533
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81577ae0-ffffffff81577afe: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158bb85)
Location: drivers/tty/vt/vt.c:2542
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff8158b9e0-ffffffff8158b9fe: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815f062e)
Location: drivers/tty/vt/vt.c:2546
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff815f0480-ffffffff815f04a0: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816299cc)
Location: drivers/tty/vt/vt.c:2544
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81629940-ffffffff8162995f: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816476a5)
Location: drivers/tty/vt/vt.c:2876
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81647600-ffffffff8164761f: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167bd41)
Location: drivers/tty/vt/vt.c:2911
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff8167bc90-ffffffff8167bcb5: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169e561)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff8169e4b0-ffffffff8169e4d5: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817513e5)
Location: drivers/tty/vt/vt.c:2944
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81751330-ffffffff81751355: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176ce35)
Location: drivers/tty/vt/vt.c:3033
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff8176cd80-ffffffff8176cda5: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817509b5)
Location: drivers/tty/vt/vt.c:3033
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81750910-ffffffff8175092e: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d3365)
Location: drivers/tty/vt/vt.c:3062
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff817d32c0-ffffffff817d32de: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81911385)
Location: drivers/tty/vt/vt.c:3062
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff819112d0-ffffffff819112f4: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a6c2c5)
Location: drivers/tty/vt/vt.c:3062
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81a6c200-ffffffff81a6c224: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab6a02)
Location: drivers/tty/vt/vt.c:3016
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81ab6920-ffffffff81ab6944: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b096e1)
Location: drivers/tty/vt/vt.c:3015
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81b09600-ffffffff81b09624: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010876044)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffff800010875cb8-ffff800010875d18: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (c0978d8c)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
  - drivers/tty/vt/vt.c:tioclinux
```
**Symbols:**

```
c0976dd0-c0976e10: vt_kmsg_redirect.part.0 (STB_LOCAL)
c0978aa0-c0978ad4: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000917a28)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
c000000000917870-c0000000009178bc: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000547460)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
```
**Symbols:**

```
ffffffe00054736e-ffffffe0005473b4: vt_kmsg_redirect (STB_GLOBAL)
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
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81663fc1)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81663f10-ffffffff81663f35: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81644341)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff81644290-ffffffff816442b5: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816923a1)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff816922f0-ffffffff81692315: vt_kmsg_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vt_kmsg_redirect(int new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816ac991)
Location: drivers/tty/vt/vt.c:2935
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:vt_console_print
Direct callers:
  - kernel/power/console.c:pm_restore_console
  - kernel/power/console.c:pm_prepare_console
```
**Symbols:**

```
ffffffff816ac8e0-ffffffff816ac905: vt_kmsg_redirect (STB_GLOBAL)
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
