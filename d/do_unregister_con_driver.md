# Function: <code>do_unregister_con_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f6f90)
Location: drivers/tty/vt/vt.c:3670
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff814f6f90-ffffffff814f7020: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81547bd0)
Location: drivers/tty/vt/vt.c:3669
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81547bd0-ffffffff81547c63: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815744d0)
Location: drivers/tty/vt/vt.c:3668
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff815744d0-ffffffff81574563: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81589050)
Location: drivers/tty/vt/vt.c:3677
Inline: True
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81589050-ffffffff815890e5: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815edb70)
Location: drivers/tty/vt/vt.c:3681
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff815edb70-ffffffff815edc05: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81627040)
Location: drivers/tty/vt/vt.c:3679
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81627040-ffffffff816270d3: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81644c50)
Location: drivers/tty/vt/vt.c:3994
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81644c50-ffffffff81644ce3: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81679160)
Location: drivers/tty/vt/vt.c:4050
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81679160-ffffffff816791fb: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169b3e0)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff8169b3e0-ffffffff8169b47b: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174dc30)
Location: drivers/tty/vt/vt.c:4091
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff8174dc30-ffffffff8174dccb: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81769200)
Location: drivers/tty/vt/vt.c:4179
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81769200-ffffffff8176929b: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174cdf0)
Location: drivers/tty/vt/vt.c:4179
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff8174cdf0-ffffffff8174ce8b: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817ceca0)
Location: drivers/tty/vt/vt.c:4184
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff817ceca0-ffffffff817ced72: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190c9d0)
Location: drivers/tty/vt/vt.c:4184
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff8190c9d0-ffffffff8190cabd: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a67660)
Location: drivers/tty/vt/vt.c:4183
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81a67660-ffffffff81a6774d: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab1d40)
Location: drivers/tty/vt/vt.c:4132
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81ab1d40-ffffffff81ab1e2d: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b04a20)
Location: drivers/tty/vt/vt.c:4132
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81b04a20-ffffffff81b04b0d: do_unregister_con_driver (STB_GLOBAL)
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
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010872960)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffff800010872960-ffff800010872a34: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0975828)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
c0975828-c09758dc: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009134c0)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
c0000000009134c0-c0000000009135c4: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000544680)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffe000544680-ffffffe00054472a: do_unregister_con_driver (STB_GLOBAL)
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
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81660e40)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff81660e40-ffffffff81660edb: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816411c0)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff816411c0-ffffffff8164125b: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168f220)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff8168f220-ffffffff8168f2bb: do_unregister_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_unregister_con_driver(const struct consw *csw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a9820)
Location: drivers/tty/vt/vt.c:4081
Inline: True
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unregistered
  - drivers/tty/vt/vt.c:give_up_console
```
**Symbols:**

```
ffffffff816a9820-ffffffff816a98bb: do_unregister_con_driver (STB_GLOBAL)
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
