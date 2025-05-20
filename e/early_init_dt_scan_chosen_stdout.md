# Function: <code>early_init_dt_scan_chosen_stdout</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (0)
Location: include/linux/of_fdt.h:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (0)
Location: include/linux/of_fdt.h:103
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (0)
Location: include/linux/of_fdt.h:103
Inline: True
```
</details>
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
int early_init_dt_scan_chosen_stdout();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114aae74)
Location: drivers/of/fdt.c:908
Inline: False
Direct callers:
  - arch/arm64/kernel/acpi.c:acpi_boot_table_init
```
**Symbols:**

```
ffff8000114aae74-ffff8000114ab014: early_init_dt_scan_chosen_stdout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int early_init_dt_scan_chosen_stdout();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15af3e0)
Location: drivers/of/fdt.c:908
Inline: False
Direct callers:
  - drivers/tty/serial/earlycon.c:param_setup_earlycon
```
**Symbols:**

```
c15af3e0-c15af574: early_init_dt_scan_chosen_stdout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int early_init_dt_scan_chosen_stdout();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013bae70)
Location: drivers/of/fdt.c:908
Inline: False
Direct callers:
  - drivers/tty/serial/earlycon.c:param_setup_earlycon
```
**Symbols:**

```
c0000000013bae70-c0000000013bb070: early_init_dt_scan_chosen_stdout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int early_init_dt_scan_chosen_stdout();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003b1de)
Location: drivers/of/fdt.c:908
Inline: False
Direct callers:
  - drivers/tty/serial/earlycon.c:param_setup_earlycon
```
**Symbols:**

```
ffffffe00003b1de-ffffffe00003b326: early_init_dt_scan_chosen_stdout (STB_GLOBAL)
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
