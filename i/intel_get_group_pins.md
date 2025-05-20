# Function: <code>intel_get_group_pins</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d4c30)
Location: drivers/pinctrl/intel/pinctrl-intel.c:280
Inline: False
```
**Symbols:**

```
ffffffff814d4c30-ffffffff814d4c86: intel_get_group_pins (STB_LOCAL)
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
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81630b10)
Location: drivers/pinctrl/intel/pinctrl-intel.c:275
Inline: False
```
**Symbols:**

```
ffffffff81630b10-ffffffff81630b69: intel_get_group_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816147b0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:285
Inline: False
```
**Symbols:**

```
ffffffff816147b0-ffffffff81614806: intel_get_group_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81683a20)
Location: drivers/pinctrl/intel/pinctrl-intel.c:285
Inline: False
```
**Symbols:**

```
ffffffff81683a20-ffffffff81683a76: intel_get_group_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0060)
Location: drivers/pinctrl/intel/pinctrl-intel.c:285
Inline: False
```
**Symbols:**

```
ffffffff817a0060-ffffffff817a00c2: intel_get_group_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b6f40)
Location: drivers/pinctrl/intel/pinctrl-intel.c:292
Inline: False
```
**Symbols:**

```
ffffffff818b6f40-ffffffff818b6fa2: intel_get_group_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fa050)
Location: drivers/pinctrl/intel/pinctrl-intel.c:294
Inline: False
```
**Symbols:**

```
ffffffff818fa050-ffffffff818fa0b2: intel_get_group_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_get_group_pins(struct pinctrl_dev *pctldev, unsigned int group, const unsigned int **pins, unsigned int *npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941390)
Location: drivers/pinctrl/intel/pinctrl-intel.c:296
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get
```
**Symbols:**

```
ffffffff81941390-ffffffff819413f2: intel_get_group_pins (STB_GLOBAL)
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
