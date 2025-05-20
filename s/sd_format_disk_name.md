# Function: <code>sd_format_disk_name</code>

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
In drivers/scsi/sd.c (ffffffff815bd130)
Location: drivers/scsi/sd.c:2953
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81616560)
Location: drivers/scsi/sd.c:2934
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81645af6)
Location: drivers/scsi/sd.c:3021
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81659288)
Location: drivers/scsi/sd.c:3187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff816c28dc)
Location: drivers/scsi/sd.c:3232
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff817002dd)
Location: drivers/scsi/sd.c:3206
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81721a63)
Location: drivers/scsi/sd.c:3246
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff8175feb9)
Location: drivers/scsi/sd.c:3232
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81783e19)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81843660)
Location: drivers/scsi/sd.c:3275
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81843660-ffffffff818436d5: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81853980)
Location: drivers/scsi/sd.c:3324
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81853980-ffffffff818539f5: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81837390)
Location: drivers/scsi/sd.c:3339
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81837390-ffffffff81837405: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff818c26c0)
Location: drivers/scsi/sd.c:3309
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff818c26c0-ffffffff818c2735: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81a0f360)
Location: drivers/scsi/sd.c:3371
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81a0f360-ffffffff81a0f3ed: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81b8f440)
Location: drivers/scsi/sd.c:3419
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81b8f440-ffffffff81b8f4cd: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81be5650)
Location: drivers/scsi/sd.c:3537
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81be5650-ffffffff81be56dd: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81c3ab80)
Location: drivers/scsi/sd.c:3608
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81c3ab80-ffffffff81c3ac0d: sd_format_disk_name.constprop.0 (STB_LOCAL)
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
In drivers/scsi/sd.c (ffff80001098a600)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (c0a5c838)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (c000000000a4ade0)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffe0005ee9d4)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81738509)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff8171a1a9)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81778c99)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
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
In drivers/scsi/sd.c (ffffffff81792ab9)
Location: drivers/scsi/sd.c:3244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
</details>
</li>
</ul>

## Differences
