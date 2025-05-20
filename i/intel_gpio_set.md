# Function: <code>intel_gpio_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-intel-mid.c (ffffffff8142a080)
Location: drivers/gpio/gpio-intel-mid.c:126
Inline: True
Direct callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff8142a080-ffffffff8142a0d8: intel_gpio_set (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d56e0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:770
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff814d56e0-ffffffff814d5745: intel_gpio_set (STB_LOCAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81631c10)
Location: drivers/pinctrl/intel/pinctrl-intel.c:934
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff81631c10-ffffffff81631c95: intel_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816158c0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:944
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff816158c0-ffffffff81615945: intel_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81684b80)
Location: drivers/pinctrl/intel/pinctrl-intel.c:941
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff81684b80-ffffffff81684c05: intel_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a1310)
Location: drivers/pinctrl/intel/pinctrl-intel.c:946
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff817a1310-ffffffff817a13a4: intel_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b83e0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:958
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff818b83e0-ffffffff818b8474: intel_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fb450)
Location: drivers/pinctrl/intel/pinctrl-intel.c:970
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff818fb450-ffffffff818fb4e4: intel_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81942a80)
Location: drivers/pinctrl/intel/pinctrl-intel.c:938
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output
```
**Symbols:**

```
ffffffff81942a80-ffffffff81942b19: intel_gpio_set (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
