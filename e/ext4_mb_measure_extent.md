# Function: <code>ext4_mb_measure_extent</code>

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
In fs/ext4/mballoc.c (ffffffff812d25a7)
Location: fs/ext4/mballoc.c:1727
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff81301cc6)
Location: fs/ext4/mballoc.c:1736
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff81317d46)
Location: fs/ext4/mballoc.c:1736
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff8130ecc1)
Location: fs/ext4/mballoc.c:1744
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff81333d11)
Location: fs/ext4/mballoc.c:1744
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff81361f80)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff8137a190)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff813a3cbc)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff813bcb2c)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff814085b0)
Location: fs/ext4/mballoc.c:1800
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
**Symbols:**

```
ffffffff814085b0-ffffffff8140866e: ext4_mb_measure_extent.constprop.0 (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff8141b010)
Location: fs/ext4/mballoc.c:1766
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
**Symbols:**

```
ffffffff8141b010-ffffffff8141b0ce: ext4_mb_measure_extent.constprop.0 (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff81421470)
Location: fs/ext4/mballoc.c:2103
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
**Symbols:**

```
ffffffff81421470-ffffffff8142152e: ext4_mb_measure_extent.constprop.0 (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff8147523f)
Location: fs/ext4/mballoc.c:2107
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff814f73e7)
Location: fs/ext4/mballoc.c:2104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8159198b)
Location: fs/ext4/mballoc.c:2067
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c8b75)
Location: fs/ext4/mballoc.c:2210
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815feb05)
Location: fs/ext4/mballoc.c:2226
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffff8000104938b0)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (c0654d44)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (c0000000005bc540)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffe0003182fa)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff813b510c)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff813a5b9c)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff813b296c)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
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
In fs/ext4/mballoc.c (ffffffff813c74bc)
Location: fs/ext4/mballoc.c:1729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
</details>
</li>
</ul>

## Differences
