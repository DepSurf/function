# Function: <code>csi_P</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814fc128)
Location: drivers/tty/vt/vt.c:1642
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8154c231)
Location: drivers/tty/vt/vt.c:1640
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
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
In drivers/tty/vt/vt.c (ffffffff81578a63)
Location: drivers/tty/vt/vt.c:1639
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158c89d)
Location: drivers/tty/vt/vt.c:1648
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815f1359)
Location: drivers/tty/vt/vt.c:1654
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8162aabf)
Location: drivers/tty/vt/vt.c:1652
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8164903a)
Location: drivers/tty/vt/vt.c:1980
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167debb)
Location: drivers/tty/vt/vt.c:1990
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a06b8)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void csi_P(struct vc_data *vc, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e1d0)
Location: drivers/tty/vt/vt.c:2025
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8174e1d0-ffffffff8174e2fc: csi_P (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void csi_P(struct vc_data *vc, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817697a0)
Location: drivers/tty/vt/vt.c:2033
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff817697a0-ffffffff817698cc: csi_P (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174d390)
Location: drivers/tty/vt/vt.c:2033
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8174d390-ffffffff8174d4be: csi_P.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817cf0c0)
Location: drivers/tty/vt/vt.c:2039
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff817cf0c0-ffffffff817cf20a: csi_P.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190d2d0)
Location: drivers/tty/vt/vt.c:2039
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8190d2d0-ffffffff8190d41c: csi_P.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a67f00)
Location: drivers/tty/vt/vt.c:2039
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81a67f00-ffffffff81a67ff3: csi_P.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab25e0)
Location: drivers/tty/vt/vt.c:1994
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81ab25e0-ffffffff81ab26d3: csi_P.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b052c0)
Location: drivers/tty/vt/vt.c:1993
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81b052c0-ffffffff81b053b3: csi_P.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff8000108778f8)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c097a278)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000919824)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe0005483c6)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81666118)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81646498)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816944f8)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816aead8)
Location: drivers/tty/vt/vt.c:2014
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
