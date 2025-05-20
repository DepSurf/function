# Function: <code>do_remove_conflicting_framebuffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146da70)
Location: drivers/video/fbdev/core/fbmem.c:1581
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
**Symbols:**

```
ffffffff8146da70-ffffffff8146dbe3: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bbda0)
Location: drivers/video/fbdev/core/fbmem.c:1581
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff814bbda0-ffffffff814bbf21: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814ddda0)
Location: drivers/video/fbdev/core/fbmem.c:1581
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff814ddda0-ffffffff814ddf21: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9360)
Location: drivers/video/fbdev/core/fbmem.c:1589
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff814e9360-ffffffff814e94d3: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151dea0)
Location: drivers/video/fbdev/core/fbmem.c:1602
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff8151dea0-ffffffff8151e013: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1590
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff81553b30-ffffffff81553bdd: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff81554ab4-ffffffff81554b99: do_remove_conflicting_framebuffers.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1624
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff8156b360-ffffffff8156b40e: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff8156c3d4-ffffffff8156c4d9: do_remove_conflicting_framebuffers.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1557
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff8159b890-ffffffff8159b930: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff8159c8a9-ffffffff8159c9a0: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff815bce90-ffffffff815bcf30: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff815bdc50-ffffffff815bdd47: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1555
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff81666d10-ffffffff81666db0: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff81667c90-ffffffff81667d78: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1548
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff816878f0-ffffffff81687990: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff81bfebde-ffffffff81bfecc6: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1546
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff8166a560-ffffffff8166a600: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff81bf076d-ffffffff81bf0855: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816de750)
Location: drivers/video/fbdev/core/fbmem.c:1552
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff816de750-ffffffff816de89e: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1566
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
**Symbols:**

```
ffffffff81808400-ffffffff81808621: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff81eb3786-ffffffff81eb3905: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
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
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff800010743590)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffff800010743590-ffff800010743718: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c08c7c64)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
c08c7c64-c08c7e14: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a4c80)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
c0000000008a4c80-c0000000008a4ee0: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f455e)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffe0004f455e-ffffffe0004f46e0: do_remove_conflicting_framebuffers (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff815b0fe0-ffffffff815b1080: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff815b1da0-ffffffff815b1e97: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff815a0170-ffffffff815a0210: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff815a0f30-ffffffff815a1027: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff815b1570-ffffffff815b1610: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff815b2330-ffffffff815b2427: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void do_remove_conflicting_framebuffers(struct apertures_struct *a, const char *name, bool primary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1547
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
  - drivers/video/fbdev/core/fbmem.c:remove_conflicting_framebuffers
```
**Symbols:**

```
ffffffff815cafe0-ffffffff815cb080: do_remove_conflicting_framebuffers (STB_LOCAL)
ffffffff815cbda0-ffffffff815cbe97: do_remove_conflicting_framebuffers.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
