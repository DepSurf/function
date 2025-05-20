# Function: <code>of_clk_get_hw_from_clkspec</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:340
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:346
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:350
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:350
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:350
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:350
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:343
Inline: True
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:343
Inline: True
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:354
Inline: True
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:354
Inline: True
```
</details>
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
In drivers/clk/clk.c (ffff8000107c3560)
Location: drivers/clk/clk.c:4554
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_get_hw
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_core_get
Direct callers:
  - drivers/clk/clk.c:of_clk_get_hw
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffff8000107bcf68-ffff8000107bd054: of_clk_get_hw_from_clkspec.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (c08eef6c)
Location: drivers/clk/clk.c:4554
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_get_hw
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_core_get
Direct callers:
  - drivers/clk/clk.c:of_clk_get_hw
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
c08e9068-c08e9120: of_clk_get_hw_from_clkspec.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffe000510f00)
Location: drivers/clk/clk.c:4554
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_get_hw
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_core_get
Direct callers:
  - drivers/clk/clk.c:of_clk_get_hw
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_core_get
```
**Symbols:**

```
ffffffe00050c3fe-ffffffe00050c4a4: of_clk_get_hw_from_clkspec.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:346
Inline: True
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:346
Inline: True
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:346
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
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:346
Inline: True
```
</details>
</li>
</ul>

## Differences
