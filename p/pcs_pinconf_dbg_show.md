# Function: <code>pcs_pinconf_dbg_show</code>

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
void pcs_pinconf_dbg_show(struct pinctrl_dev *pctldev, struct seq_file *s, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffff80001069b700)
Location: drivers/pinctrl/pinctrl-single.c:624
Inline: True
```
**Symbols:**

```
ffff80001069b700-ffff80001069b718: pcs_pinconf_dbg_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pcs_pinconf_dbg_show(struct pinctrl_dev *pctldev, struct seq_file *s, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c083e3f0)
Location: drivers/pinctrl/pinctrl-single.c:624
Inline: True
```
**Symbols:**

```
c083e3f0-c083e408: pcs_pinconf_dbg_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcs_pinconf_dbg_show(struct pinctrl_dev *pctldev, struct seq_file *s, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c000000000832650)
Location: drivers/pinctrl/pinctrl-single.c:624
Inline: False
```
**Symbols:**

```
c000000000832650-c00000000083265c: pcs_pinconf_dbg_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pcs_pinconf_dbg_show(struct pinctrl_dev *pctldev, struct seq_file *s, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffffffe00049fe32)
Location: drivers/pinctrl/pinctrl-single.c:624
Inline: True
```
**Symbols:**

```
ffffffe00049fe32-ffffffe00049fe4c: pcs_pinconf_dbg_show (STB_LOCAL)
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
