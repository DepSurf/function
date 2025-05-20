# Function: <code>dt_remember_or_free_map</code>

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
int dt_remember_or_free_map(struct pinctrl *p, const char *statename, struct pinctrl_dev *pctldev, struct pinctrl_map *map, unsigned int num_maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (ffff8000106909b0)
Location: drivers/pinctrl/devicetree.c:64
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
ffff8000106909b0-ffff800010690ad4: dt_remember_or_free_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dt_remember_or_free_map(struct pinctrl *p, const char *statename, struct pinctrl_dev *pctldev, struct pinctrl_map *map, unsigned int num_maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (c08325f8)
Location: drivers/pinctrl/devicetree.c:64
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
c08325f8-c08326f4: dt_remember_or_free_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dt_remember_or_free_map(struct pinctrl *p, const char *statename, struct pinctrl_dev *pctldev, struct pinctrl_map *map, unsigned int num_maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (c00000000082c860)
Location: drivers/pinctrl/devicetree.c:64
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
c00000000082c860-c00000000082ca18: dt_remember_or_free_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dt_remember_or_free_map(struct pinctrl *p, const char *statename, struct pinctrl_dev *pctldev, struct pinctrl_map *map, unsigned int num_maps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (ffffffe00049c3d4)
Location: drivers/pinctrl/devicetree.c:64
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
ffffffe00049c3d4-ffffffe00049c4be: dt_remember_or_free_map (STB_LOCAL)
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
