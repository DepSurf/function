# Function: <code>pcs_pinconf_clear_bias</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void pcs_pinconf_clear_bias(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffff80001069c320)
Location: drivers/pinctrl/pinctrl-single.c:430
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
**Symbols:**

```
ffff80001069c320-ffff80001069c3ac: pcs_pinconf_clear_bias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcs_pinconf_clear_bias(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c083ef70)
Location: drivers/pinctrl/pinctrl-single.c:430
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
**Symbols:**

```
c083ef70-c083eff8: pcs_pinconf_clear_bias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcs_pinconf_clear_bias(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c000000000833730)
Location: drivers/pinctrl/pinctrl-single.c:430
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
**Symbols:**

```
c000000000833730-c0000000008337d4: pcs_pinconf_clear_bias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcs_pinconf_clear_bias(struct pinctrl_dev *pctldev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0a1c)
Location: drivers/pinctrl/pinctrl-single.c:430
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
**Symbols:**

```
ffffffe0004a0a1c-ffffffe0004a0a72: pcs_pinconf_clear_bias (STB_LOCAL)
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
