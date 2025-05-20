# Function: <code>of_flat_dt_get_machine_name</code>

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
const char *of_flat_dt_get_machine_name();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aacb0)
Location: drivers/of/fdt.c:795
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - drivers/of/fdt.c:of_flat_dt_match_machine
```
**Symbols:**

```
ffff8000114aacb0-ffff8000114aacfc: of_flat_dt_get_machine_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *of_flat_dt_get_machine_name();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15af204)
Location: drivers/of/fdt.c:795
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_flat_dt_match_machine
```
**Symbols:**

```
c15af204-c15af24c: of_flat_dt_get_machine_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *of_flat_dt_get_machine_name();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013bac18)
Location: drivers/of/fdt.c:795
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_flat_dt_match_machine
```
**Symbols:**

```
c0000000013bac18-c0000000013bac7c: of_flat_dt_get_machine_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *of_flat_dt_get_machine_name();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003b062)
Location: drivers/of/fdt.c:795
Inline: False
Direct callers:
  - drivers/of/fdt.c:of_flat_dt_match_machine
```
**Symbols:**

```
ffffffe00003b062-ffffffe00003b0aa: of_flat_dt_get_machine_name (STB_GLOBAL)
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
