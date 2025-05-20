# Function: <code>mvebu_pinctrl_find_setting_by_name</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aa568)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:121
Inline: True
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_set
```
**Symbols:**

```
ffff8000106aa568-ffff8000106aa5f8: mvebu_pinctrl_find_setting_by_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mvebu_mpp_ctrl_setting *mvebu_pinctrl_find_setting_by_name(struct mvebu_pinctrl *pctl, struct mvebu_pinctrl_group *grp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c0849c7c)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:121
Inline: False
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_set
```
**Symbols:**

```
c0849c7c-c0849cf4: mvebu_pinctrl_find_setting_by_name (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
