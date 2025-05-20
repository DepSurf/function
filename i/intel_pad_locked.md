# Function: <code>intel_pad_locked</code>

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
bool intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5390)
Location: drivers/pinctrl/intel/pinctrl-intel.c:222
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_usable
```
**Symbols:**

```
ffffffff814d5390-ffffffff814d542b: intel_pad_locked (STB_LOCAL)
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
int intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:212
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81632180-ffffffff8163229c: intel_pad_locked (STB_LOCAL)
ffffffff81bf5969-ffffffff81bf5985: intel_pad_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:222
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81615d80-ffffffff81615e73: intel_pad_locked (STB_LOCAL)
ffffffff81be7888-ffffffff81be78a4: intel_pad_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:222
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81685070-ffffffff816851c3: intel_pad_locked (STB_LOCAL)
ffffffff81ce12f9-ffffffff81ce1357: intel_pad_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:222
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff817a1860-ffffffff817a199f: intel_pad_locked (STB_LOCAL)
ffffffff81ea7ad2-ffffffff81ea7b2b: intel_pad_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:229
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff818b89d0-ffffffff818b8b16: intel_pad_locked (STB_LOCAL)
ffffffff8208e47b-ffffffff8208e4be: intel_pad_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:231
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff818fba50-ffffffff818fbb93: intel_pad_locked (STB_LOCAL)
ffffffff8210e757-ffffffff8210e793: intel_pad_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_pad_locked(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:232
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show
```
**Symbols:**

```
ffffffff81943080-ffffffff819431c3: intel_pad_locked (STB_LOCAL)
ffffffff821ec3b5-ffffffff821ec3f1: intel_pad_locked.cold (STB_LOCAL)
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
