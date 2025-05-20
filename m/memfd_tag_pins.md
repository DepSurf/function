# Function: <code>memfd_tag_pins</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812941a0)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
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
In mm/memfd.c (ffffffff812a8e9e)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
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
In mm/memfd.c (ffffffff812c5306)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffff812d6c9d)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffff8130bd60)
Location: mm/memfd.c:31
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff8130bd60-ffffffff8130bf20: memfd_tag_pins.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memfd.c (ffffffff81317c20)
Location: mm/memfd.c:31
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff81317c20-ffffffff81317de0: memfd_tag_pins.constprop.0 (STB_LOCAL)
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
In mm/memfd.c (ffffffff8131de10)
Location: mm/memfd.c:31
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff8131de10-ffffffff8131dfd0: memfd_tag_pins.constprop.0 (STB_LOCAL)
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
In mm/memfd.c (ffffffff8136b1b0)
Location: mm/memfd.c:31
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff8136b1b0-ffffffff8136b3a2: memfd_tag_pins.constprop.0 (STB_LOCAL)
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
In mm/memfd.c (ffffffff813e9180)
Location: mm/memfd.c:31
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff813e9180-ffffffff813e9435: memfd_tag_pins.constprop.0 (STB_LOCAL)
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
In mm/memfd.c (ffffffff81471130)
Location: mm/memfd.c:31
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff81471130-ffffffff81471410: memfd_tag_pins.constprop.0 (STB_LOCAL)
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
In mm/memfd.c (ffffffff814a5680)
Location: mm/memfd.c:32
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff814a5680-ffffffff814a592f: memfd_tag_pins.constprop.0 (STB_LOCAL)
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
In mm/memfd.c (ffffffff814d6640)
Location: mm/memfd.c:32
Inline: True
Direct callers:
  - mm/memfd.c:memfd_wait_for_pins
```
**Symbols:**

```
ffffffff814d6640-ffffffff814d68e0: memfd_tag_pins.constprop.0 (STB_LOCAL)
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
In mm/memfd.c (ffff80001037bc3c)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (c05669c8)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (c000000000471068)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffe0002523cc)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffff812cf27d)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffff812bff0d)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffff812cd08d)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memfd.c (ffffffff812dde2d)
Location: mm/memfd.c:31
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
</details>
</li>
</ul>

## Differences
