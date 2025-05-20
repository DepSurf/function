# Function: <code>do_unbind_con_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f9330)
Location: drivers/tty/vt/vt.c:3237
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff814f9330-ffffffff814f9520: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815499d0)
Location: drivers/tty/vt/vt.c:3236
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff815499d0-ffffffff81549beb: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81576400)
Location: drivers/tty/vt/vt.c:3235
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81576400-ffffffff8157661b: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158a2e0)
Location: drivers/tty/vt/vt.c:3244
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8158a2e0-ffffffff8158a4ee: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ee890)
Location: drivers/tty/vt/vt.c:3249
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff815ee890-ffffffff815eeaa3: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81627bf0)
Location: drivers/tty/vt/vt.c:3247
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81627bf0-ffffffff81627e03: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81645360)
Location: drivers/tty/vt/vt.c:3562
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_event_notify
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81645360-ffffffff8164557d: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3598
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8167f1a5-ffffffff8167f1b8: do_unbind_con_driver.cold (STB_LOCAL)
ffffffff81679880-ffffffff81679a58: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169c070)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8169c070-ffffffff8169c246: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174ff80)
Location: drivers/tty/vt/vt.c:3639
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8174ff80-ffffffff81750156: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176b340)
Location: drivers/tty/vt/vt.c:3728
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8176b340-ffffffff8176b516: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174f550)
Location: drivers/tty/vt/vt.c:3728
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8174f550-ffffffff8174f726: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d1800)
Location: drivers/tty/vt/vt.c:3733
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff817d1800-ffffffff817d1ab3: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190f460)
Location: drivers/tty/vt/vt.c:3733
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8190f460-ffffffff8190f73d: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a68de0)
Location: drivers/tty/vt/vt.c:3732
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81a68de0-ffffffff81a690bd: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab34c0)
Location: drivers/tty/vt/vt.c:3681
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81ab34c0-ffffffff81ab379d: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b061a0)
Location: drivers/tty/vt/vt.c:3681
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81b061a0-ffffffff81b0647d: do_unbind_con_driver (STB_GLOBAL)
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
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010873860)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffff800010873860-ffff800010873a68: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0976548)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
c0976548-c097677c: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000914590)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
c000000000914590-c0000000009148a8: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000545246)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffe000545246-ffffffe000545414: do_unbind_con_driver (STB_GLOBAL)
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
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81661ad0)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81661ad0-ffffffff81661ca6: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81641e50)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff81641e50-ffffffff81642026: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168feb0)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff8168feb0-ffffffff81690086: do_unbind_con_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_unbind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816aa4b0)
Location: drivers/tty/vt/vt.c:3629
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_fb_unbind
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff816aa4b0-ffffffff816aa686: do_unbind_con_driver (STB_GLOBAL)
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
