# Function: <code>intel_config_set_pull</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d592e)
Location: drivers/pinctrl/intel/pinctrl-intel.c:581
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632bae)
Location: drivers/pinctrl/intel/pinctrl-intel.c:658
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816168b5)
Location: drivers/pinctrl/intel/pinctrl-intel.c:668
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81685b25)
Location: drivers/pinctrl/intel/pinctrl-intel.c:665
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a23c9)
Location: drivers/pinctrl/intel/pinctrl-intel.c:665
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b9634)
Location: drivers/pinctrl/intel/pinctrl-intel.c:677
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_config_set_pull(struct intel_pinctrl *pctrl, unsigned int pin, long unsigned int config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fc600)
Location: drivers/pinctrl/intel/pinctrl-intel.c:686
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
```
**Symbols:**

```
ffffffff818fc600-ffffffff818fc7bf: intel_config_set_pull (STB_LOCAL)
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943988)
Location: drivers/pinctrl/intel/pinctrl-intel.c:672
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
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
</ul>
