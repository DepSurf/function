# Function: <code>pcs_pinconf_get</code>

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
int pcs_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffff80001069bd30)
Location: drivers/pinctrl/pinctrl-single.c:459
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
```
**Symbols:**

```
ffff80001069bd30-ffff80001069bf24: pcs_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcs_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c083e99c)
Location: drivers/pinctrl/pinctrl-single.c:459
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
```
**Symbols:**

```
c083e99c-c083eb8c: pcs_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcs_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c000000000832ee0)
Location: drivers/pinctrl/pinctrl-single.c:459
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
```
**Symbols:**

```
c000000000832ee0-c000000000833190: pcs_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcs_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0320)
Location: drivers/pinctrl/pinctrl-single.c:459
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_group_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
```
**Symbols:**

```
ffffffe0004a0320-ffffffe0004a0486: pcs_pinconf_get (STB_LOCAL)
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
