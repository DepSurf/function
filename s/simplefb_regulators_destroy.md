# Function: <code>simplefb_regulators_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:380
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:386
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:407
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:407
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:407
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:407
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/simplefb.c (ffff800010761890)
Location: drivers/video/fbdev/simplefb.c:383
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
```
**Symbols:**

```
ffff800010760ef8-ffff800010760f4c: simplefb_regulators_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/simplefb.c (c08e4034)
Location: drivers/video/fbdev/simplefb.c:383
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
```
**Symbols:**

```
c08e36b8-c08e3708: simplefb_regulators_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/simplefb.c (c0000000008c5388)
Location: drivers/video/fbdev/simplefb.c:383
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
```
**Symbols:**

```
c0000000008c48c0-c0000000008c4948: simplefb_regulators_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/simplefb.c (ffffffe000508528)
Location: drivers/video/fbdev/simplefb.c:383
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
Direct callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_destroy
```
**Symbols:**

```
ffffffe000507d0c-ffffffe000507d60: simplefb_regulators_destroy.part.0 (STB_LOCAL)
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
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
In drivers/video/fbdev/simplefb.c (0)
Location: drivers/video/fbdev/simplefb.c:399
Inline: True
```
</details>
</li>
</ul>

## Differences
