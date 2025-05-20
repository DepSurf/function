# Function: <code>parse_dt_cfg</code>

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
void parse_dt_cfg(struct device_node *np, const struct pinconf_generic_params *params, unsigned int count, long unsigned int *cfg, unsigned int *ncfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffff800010691440)
Location: drivers/pinctrl/pinconf-generic.c:202
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
**Symbols:**

```
ffff800010691440-ffff800010691560: parse_dt_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void parse_dt_cfg(struct device_node *np, const struct pinconf_generic_params *params, unsigned int count, long unsigned int *cfg, unsigned int *ncfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c0832ff0)
Location: drivers/pinctrl/pinconf-generic.c:202
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
**Symbols:**

```
c0832ff0-c08330f0: parse_dt_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void parse_dt_cfg(struct device_node *np, const struct pinconf_generic_params *params, unsigned int count, long unsigned int *cfg, unsigned int *ncfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (c00000000082d4e0)
Location: drivers/pinctrl/pinconf-generic.c:202
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
**Symbols:**

```
c00000000082d4e0-c00000000082d67c: parse_dt_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void parse_dt_cfg(struct device_node *np, const struct pinconf_generic_params *params, unsigned int count, long unsigned int *cfg, unsigned int *ncfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffffffe00049cc82)
Location: drivers/pinctrl/pinconf-generic.c:202
Inline: False
Direct callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
```
**Symbols:**

```
ffffffe00049cc82-ffffffe00049cd6a: parse_dt_cfg (STB_LOCAL)
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
