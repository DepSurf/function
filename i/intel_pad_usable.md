# Function: <code>intel_pad_usable</code>

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
bool intel_pad_usable(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5430)
Location: drivers/pinctrl/intel/pinctrl-intel.c:259
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
```
**Symbols:**

```
ffffffff814d5430-ffffffff814d5464: intel_pad_usable (STB_LOCAL)
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632655)
Location: drivers/pinctrl/intel/pinctrl-intel.c:255
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81616235)
Location: drivers/pinctrl/intel/pinctrl-intel.c:265
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81685565)
Location: drivers/pinctrl/intel/pinctrl-intel.c:265
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a1d97)
Location: drivers/pinctrl/intel/pinctrl-intel.c:265
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b8f59)
Location: drivers/pinctrl/intel/pinctrl-intel.c:272
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fbfd9)
Location: drivers/pinctrl/intel/pinctrl-intel.c:274
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943d09)
Location: drivers/pinctrl/intel/pinctrl-intel.c:275
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
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
