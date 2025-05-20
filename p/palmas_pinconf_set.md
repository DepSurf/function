# Function: <code>palmas_pinconf_set</code>

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
int palmas_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-palmas.c (ffff800010696950)
Location: drivers/pinctrl/pinctrl-palmas.c:857
Inline: False
```
**Symbols:**

```
ffff800010696950-ffff800010696bf4: palmas_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int palmas_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-palmas.c (c0836bb8)
Location: drivers/pinctrl/pinctrl-palmas.c:857
Inline: False
```
**Symbols:**

```
c0836bb8-c0836e90: palmas_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int palmas_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-palmas.c (c000000000831830)
Location: drivers/pinctrl/pinctrl-palmas.c:857
Inline: False
```
**Symbols:**

```
c000000000831830-c000000000831be8: palmas_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int palmas_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-palmas.c (ffffffe00049f3a4)
Location: drivers/pinctrl/pinctrl-palmas.c:857
Inline: False
```
**Symbols:**

```
ffffffe00049f3a4-ffffffe00049f64a: palmas_pinconf_set (STB_LOCAL)
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
