# Function: <code>vc_uniscr_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81649061)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (ffffffff8167dee0)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (ffffffff816a06dd)
Location: drivers/tty/vt/vt.c:398
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e221)
Location: drivers/tty/vt/vt.c:404
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_P
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817697f1)
Location: drivers/tty/vt/vt.c:397
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:csi_P
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174d3e1)
Location: drivers/tty/vt/vt.c:397
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817cf111)
Location: drivers/tty/vt/vt.c:393
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190d323)
Location: drivers/tty/vt/vt.c:393
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff81a67570)
Location: drivers/tty/vt/vt.c:393
Inline: True
```
**Symbols:**

```
ffffffff81a67570-ffffffff81a675f7: vc_uniscr_delete.constprop.0 (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffffffff81ab1c50)
Location: drivers/tty/vt/vt.c:379
Inline: True
```
**Symbols:**

```
ffffffff81ab1c50-ffffffff81ab1cd7: vc_uniscr_delete.constprop.0 (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffffffff81b048b0)
Location: drivers/tty/vt/vt.c:378
Inline: True
```
**Symbols:**

```
ffffffff81b048b0-ffffffff81b04933: vc_uniscr_delete.constprop.0 (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffff800010877918)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (c097a298)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (c00000000091984c)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (ffffffe0005483e4)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (ffffffff8166613d)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (ffffffff816464bd)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (ffffffff8169451d)
Location: drivers/tty/vt/vt.c:398
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
In drivers/tty/vt/vt.c (ffffffff816aeafd)
Location: drivers/tty/vt/vt.c:398
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
</ul>

## Differences
