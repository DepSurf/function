# Function: <code>byt_gpio_direct_irq_check</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81609c30)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:803
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
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
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162e340)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:803
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
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
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81611ea0)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:803
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl *vg, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81ce1002)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:803
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
```
**Symbols:**

```
ffffffff816802f0-ffffffff81680340: byt_gpio_direct_irq_check (STB_LOCAL)
ffffffff81ce0fed-ffffffff81ce101d: byt_gpio_direct_irq_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl *vg, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81ea7728)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:814
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
```
**Symbols:**

```
ffffffff8179c190-ffffffff8179c1ee: byt_gpio_direct_irq_check (STB_LOCAL)
ffffffff81ea7710-ffffffff81ea7740: byt_gpio_direct_irq_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl *vg, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2b9d)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:814
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
```
**Symbols:**

```
ffffffff818b2b40-ffffffff818b2bc3: byt_gpio_direct_irq_check (STB_LOCAL)
ffffffff8208e362-ffffffff8208e377: byt_gpio_direct_irq_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl *vg, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f5bf5)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:810
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
```
**Symbols:**

```
ffffffff818f5b90-ffffffff818f5c20: byt_gpio_direct_irq_check (STB_LOCAL)
ffffffff8210e63e-ffffffff8210e653: byt_gpio_direct_irq_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl *vg, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193df1e)
Location: drivers/pinctrl/intel/pinctrl-baytrail.c:729
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction
```
**Symbols:**

```
ffffffff8193deb0-ffffffff8193df49: byt_gpio_direct_irq_check (STB_LOCAL)
ffffffff821ec27b-ffffffff821ec290: byt_gpio_direct_irq_check.cold (STB_LOCAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
