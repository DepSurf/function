# Function: <code>ab3100_mask_and_set_register_interruptible</code>

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
In drivers/mfd/ab3100-core.c (ffffffff8159219d)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff815e6f8d)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff81613d9d)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff81627d6d)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff8169067d)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff816cc789)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff816edd49)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff817274b7)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff8174b767)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ab3100_mask_and_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 andmask, u8 ormask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:279
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
```
**Symbols:**

```
ffffffff818097c0-ffffffff818098b6: ab3100_mask_and_set_register_interruptible (STB_LOCAL)
ffffffff8180a05b-ffffffff8180a118: ab3100_mask_and_set_register_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ab3100_mask_and_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 andmask, u8 ormask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:279
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
```
**Symbols:**

```
ffffffff81819600-ffffffff818196f6: ab3100_mask_and_set_register_interruptible (STB_LOCAL)
ffffffff81c1473b-ffffffff81c147f8: ab3100_mask_and_set_register_interruptible.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffff800010949964)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (c0a327ec)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (c0000000009f4f18)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffe0005bb5f2)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
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
In drivers/mfd/ab3100-core.c (ffffffff8173ec27)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
In drivers/mfd/ab3100-core.c (ffffffff8175a067)
Location: drivers/mfd/ab3100-core.c:279
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible
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
