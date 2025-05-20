# Function: <code>agpioc_reserve_wrap</code>

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
In drivers/char/agp/frontend.c (ffffffff8151c588)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff8156f2bb)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff8159b97b)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff815af807)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff81616377)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff81650166)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff8166e306)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816a3b20)
Location: drivers/char/agp/frontend.c:799
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
```
**Symbols:**

```
ffffffff816a3b20-ffffffff816a3d14: agpioc_reserve_wrap.isra.0 (STB_LOCAL)
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
In drivers/char/agp/frontend.c (ffffffff816c6c1b)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8177b2a0)
Location: drivers/char/agp/frontend.c:797
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
```
**Symbols:**

```
ffffffff8177b2a0-ffffffff8177b4a3: agpioc_reserve_wrap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (c0000000009538d0)
Location: drivers/char/agp/frontend.c:799
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
```
**Symbols:**

```
c0000000009538d0-c000000000953c00: agpioc_reserve_wrap.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8168c66b)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff8166a06b)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff816ba8db)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
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
In drivers/char/agp/frontend.c (ffffffff816d4eab)
Location: drivers/char/agp/frontend.c:799
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
```
</details>
</li>
</ul>

## Differences
