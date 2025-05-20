# Function: <code>pinctrl_generic_get_group_pins</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_generic_get_group_pins(struct pinctrl_dev *pctldev, unsigned int selector, const unsigned int **pins, unsigned int *num_pins);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068c950)
Location: drivers/pinctrl/core.c:554
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_group_get
```
**Symbols:**

```
ffff80001068c950-ffff80001068c9d8: pinctrl_generic_get_group_pins (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_generic_get_group_pins(struct pinctrl_dev *pctldev, unsigned int selector, const unsigned int **pins, unsigned int *num_pins);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082ea4c)
Location: drivers/pinctrl/core.c:554
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_group_get
```
**Symbols:**

```
c082ea4c-c082eabc: pinctrl_generic_get_group_pins (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_generic_get_group_pins(struct pinctrl_dev *pctldev, unsigned int selector, const unsigned int **pins, unsigned int *num_pins);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c0000000008259b0)
Location: drivers/pinctrl/core.c:554
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
```
**Symbols:**

```
c0000000008259b0-c000000000825a5c: pinctrl_generic_get_group_pins (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_generic_get_group_pins(struct pinctrl_dev *pctldev, unsigned int selector, const unsigned int **pins, unsigned int *num_pins);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000498c0c)
Location: drivers/pinctrl/core.c:554
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
```
**Symbols:**

```
ffffffe000498c0c-ffffffe000498c84: pinctrl_generic_get_group_pins (STB_GLOBAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
