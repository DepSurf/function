# Function: <code>agp_controller_release_current</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8151b9e0)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_ioctl
```
**Symbols:**

```
ffffffff8151b9e0-ffffffff8151ba41: agp_controller_release_current.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8156e720)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff8156e720-ffffffff8156e781: agp_controller_release_current.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8159ade0)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff8159ade0-ffffffff8159ae41: agp_controller_release_current.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff815aee40)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff815aee40-ffffffff815aeea1: agp_controller_release_current.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816159b0)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff816159b0-ffffffff81615a11: agp_controller_release_current.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8164f730)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff8164f730-ffffffff8164f791: agp_controller_release_current.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8166d9f0)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff8166d9f0-ffffffff8166da51: agp_controller_release_current.isra.10 (STB_LOCAL)
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
In drivers/char/agp/frontend.c (ffffffff816a35a0)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff816a35a0-ffffffff816a3601: agp_controller_release_current.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816c6330)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff816c6330-ffffffff816c6391: agp_controller_release_current.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void agp_controller_release_current(struct agp_controller *controller, struct agp_file_private *controller_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8177a880)
Location: drivers/char/agp/frontend.c:423
Inline: False
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff8177a880-ffffffff8177a8e2: agp_controller_release_current (STB_LOCAL)
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
In drivers/char/agp/frontend.c (c000000000952e00)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
c000000000952e00-c000000000952ee0: agp_controller_release_current.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8168bd80)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff8168bd80-ffffffff8168bde1: agp_controller_release_current.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff81669780)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff81669780-ffffffff816697e1: agp_controller_release_current.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816b9ff0)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff816b9ff0-ffffffff816ba051: agp_controller_release_current.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816d45c0)
Location: drivers/char/agp/frontend.c:425
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
```
**Symbols:**

```
ffffffff816d45c0-ffffffff816d4621: agp_controller_release_current.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
