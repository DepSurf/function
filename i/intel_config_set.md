# Function: <code>intel_config_set</code>

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
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d57d0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:706
Inline: False
```
**Symbols:**

```
ffffffff814d57d0-ffffffff814d5a62: intel_config_set (STB_LOCAL)
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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:797
Inline: False
```
**Symbols:**

```
ffffffff81632b20-ffffffff81632e2e: intel_config_set (STB_LOCAL)
ffffffff81bf59a2-ffffffff81bf59cc: intel_config_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:807
Inline: False
```
**Symbols:**

```
ffffffff81616820-ffffffff81616b25: intel_config_set (STB_LOCAL)
ffffffff81be78c1-ffffffff81be78ea: intel_config_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:804
Inline: False
```
**Symbols:**

```
ffffffff81685a90-ffffffff81685d95: intel_config_set (STB_LOCAL)
ffffffff81ce138d-ffffffff81ce13b6: intel_config_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:804
Inline: False
```
**Symbols:**

```
ffffffff817a2320-ffffffff817a2669: intel_config_set (STB_LOCAL)
ffffffff81ea7b5b-ffffffff81ea7b85: intel_config_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b9590)
Location: drivers/pinctrl/intel/pinctrl-intel.c:816
Inline: False
```
**Symbols:**

```
ffffffff818b9590-ffffffff818b98e0: intel_config_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fc7d0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:828
Inline: False
```
**Symbols:**

```
ffffffff818fc7d0-ffffffff818fc99a: intel_config_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_config_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int nconfigs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff819438e0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:796
Inline: False
```
**Symbols:**

```
ffffffff819438e0-ffffffff81943cbd: intel_config_set (STB_LOCAL)
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
