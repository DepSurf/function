# Function: <code>do_take_over_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f9520)
Location: drivers/tty/vt/vt.c:3747
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff814f9520-ffffffff814f96bf: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81549bf0)
Location: drivers/tty/vt/vt.c:3746
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff81549bf0-ffffffff81549d6e: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81576620)
Location: drivers/tty/vt/vt.c:3745
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff81576620-ffffffff8157679e: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158a4f0)
Location: drivers/tty/vt/vt.c:3754
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8158a4f0-ffffffff8158a684: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815eeab0)
Location: drivers/tty/vt/vt.c:3758
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff815eeab0-ffffffff815eec49: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3756
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8162c5fe-ffffffff8162c63c: do_take_over_console.cold.28 (STB_LOCAL)
ffffffff81627e10-ffffffff81627f88: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4071
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8164a72e-ffffffff8164a76c: do_take_over_console.cold.32 (STB_LOCAL)
ffffffff81645580-ffffffff81645713: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4127
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8167f1b8-ffffffff8167f209: do_take_over_console.cold (STB_LOCAL)
ffffffff81679a60-ffffffff81679bf7: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff816a1917-ffffffff816a1955: do_take_over_console.cold (STB_LOCAL)
ffffffff8169c250-ffffffff8169c3e9: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174ff30)
Location: drivers/tty/vt/vt.c:4168
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8174ff30-ffffffff8174ff77: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176b2f0)
Location: drivers/tty/vt/vt.c:4256
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8176b2f0-ffffffff8176b337: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174f500)
Location: drivers/tty/vt/vt.c:4256
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8174f500-ffffffff8174f547: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d17b0)
Location: drivers/tty/vt/vt.c:4261
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff817d17b0-ffffffff817d17f7: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190f400)
Location: drivers/tty/vt/vt.c:4261
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff8190f400-ffffffff8190f451: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a68d70)
Location: drivers/tty/vt/vt.c:4260
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff81a68d70-ffffffff81a68dc1: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab3450)
Location: drivers/tty/vt/vt.c:4209
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff81ab3450-ffffffff81ab34a1: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b06130)
Location: drivers/tty/vt/vt.c:4209
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff81b06130-ffffffff81b06181: do_take_over_console (STB_GLOBAL)
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
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010873a68)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffff800010873a68-ffff800010873c64: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c097677c)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
c097677c-c0976960: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009148b0)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
c0000000009148b0-c000000000914b74: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000545414)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffe000545414-ffffffe0005455be: do_take_over_console (STB_GLOBAL)
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
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff81667377-ffffffff816673b5: do_take_over_console.cold (STB_LOCAL)
ffffffff81661cb0-ffffffff81661e49: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff816476f7-ffffffff81647735: do_take_over_console.cold (STB_LOCAL)
ffffffff81642030-ffffffff816421c9: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff81695757-ffffffff81695795: do_take_over_console.cold (STB_LOCAL)
ffffffff81690090-ffffffff81690229: do_take_over_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_take_over_console(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4158
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:do_fbcon_takeover
```
**Symbols:**

```
ffffffff816afd27-ffffffff816afd65: do_take_over_console.cold (STB_LOCAL)
ffffffff816aa690-ffffffff816aa829: do_take_over_console (STB_GLOBAL)
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
