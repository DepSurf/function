# Function: <code>meson8_pmx_disable_other_groups</code>

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
In drivers/pinctrl/meson/pinctrl-meson8-pmx.c (ffff800010696330)
Location: drivers/pinctrl/meson/pinctrl-meson8-pmx.c:32
Inline: True
Direct callers:
  - drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_request_gpio
  - drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_set_mux
```
**Symbols:**

```
ffff800010696330-ffff80001069643c: meson8_pmx_disable_other_groups.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void meson8_pmx_disable_other_groups(struct meson_pinctrl *pc, unsigned int pin, int sel_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/meson/pinctrl-meson8-pmx.c (c083684c)
Location: drivers/pinctrl/meson/pinctrl-meson8-pmx.c:32
Inline: False
Direct callers:
  - drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_request_gpio
  - drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_set_mux
```
**Symbols:**

```
c083684c-c0836940: meson8_pmx_disable_other_groups (STB_LOCAL)
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
