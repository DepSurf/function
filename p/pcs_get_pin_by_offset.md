# Function: <code>pcs_get_pin_by_offset</code>

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
int pcs_get_pin_by_offset(struct pcs_device *pcs, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffff80001069ba60)
Location: drivers/pinctrl/pinctrl-single.c:797
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
```
**Symbols:**

```
ffff80001069ba60-ffff80001069badc: pcs_get_pin_by_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcs_get_pin_by_offset(struct pcs_device *pcs, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c083e71c)
Location: drivers/pinctrl/pinctrl-single.c:797
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
**Symbols:**

```
c083e71c-c083e780: pcs_get_pin_by_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcs_get_pin_by_offset(struct pcs_device *pcs, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c000000000832b60)
Location: drivers/pinctrl/pinctrl-single.c:797
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
**Symbols:**

```
c000000000832b60-c000000000832bf0: pcs_get_pin_by_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcs_get_pin_by_offset(struct pcs_device *pcs, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a00c2)
Location: drivers/pinctrl/pinctrl-single.c:797
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
**Symbols:**

```
ffffffe0004a00c2-ffffffe0004a012c: pcs_get_pin_by_offset (STB_LOCAL)
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
