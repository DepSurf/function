# Function: <code>genpd_iterate_idle_states</code>

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
In drivers/base/power/domain.c (ffff800010907fe0)
Location: drivers/base/power/domain.c:2608
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
Direct callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
**Symbols:**

```
ffff800010907b38-ffff800010907d24: genpd_iterate_idle_states.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (c09f28a4)
Location: drivers/base/power/domain.c:2608
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
Direct callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
**Symbols:**

```
c09f1f18-c09f2138: genpd_iterate_idle_states.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a7b80)
Location: drivers/base/power/domain.c:2608
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
Direct callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
**Symbols:**

```
c0000000009a7120-c0000000009a73bc: genpd_iterate_idle_states.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain.c (ffffffe00058f0b4)
Location: drivers/base/power/domain.c:2608
Inline: True
Inline callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
Direct callers:
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
  - drivers/base/power/domain.c:of_genpd_parse_idle_states
```
**Symbols:**

```
ffffffe00058eed6-ffffffe00058f092: genpd_iterate_idle_states.part.0 (STB_LOCAL)
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
