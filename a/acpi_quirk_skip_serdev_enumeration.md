# Function: <code>acpi_quirk_skip_serdev_enumeration</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_quirk_skip_serdev_enumeration(struct device *controller_parent, bool *skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff81840d10)
Location: drivers/acpi/x86/utils.c:370
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
**Symbols:**

```
ffffffff81840d10-ffffffff81840db1: acpi_quirk_skip_serdev_enumeration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_quirk_skip_serdev_enumeration(struct device *controller_parent, bool *skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff81977710)
Location: drivers/acpi/x86/utils.c:403
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
**Symbols:**

```
ffffffff81977710-ffffffff819777dd: acpi_quirk_skip_serdev_enumeration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_quirk_skip_serdev_enumeration(struct device *controller_parent, bool *skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff819be230)
Location: drivers/acpi/x86/utils.c:432
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
**Symbols:**

```
ffffffff819be230-ffffffff819be329: acpi_quirk_skip_serdev_enumeration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_quirk_skip_serdev_enumeration(struct device *controller_parent, bool *skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff81a08b20)
Location: drivers/acpi/x86/utils.c:431
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
**Symbols:**

```
ffffffff81a08b20-ffffffff81a08c19: acpi_quirk_skip_serdev_enumeration (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
