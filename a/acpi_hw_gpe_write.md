# Function: <code>acpi_hw_gpe_write</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_write(u64 value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816d8e14)
Location: drivers/acpi/acpica/hwgpe.c:81
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_enable_write
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff816d8e14-ffffffff816d8e5e: acpi_hw_gpe_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_write(u64 value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816badac)
Location: drivers/acpi/acpica/hwgpe.c:81
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_enable_write
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff816badac-ffffffff816badf6: acpi_hw_gpe_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_write(u64 value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81731df3)
Location: drivers/acpi/acpica/hwgpe.c:81
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_enable_write
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81731df3-ffffffff81731e3d: acpi_hw_gpe_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_write(u64 value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81862b70)
Location: drivers/acpi/acpica/hwgpe.c:81
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_enable_write
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81862b70-ffffffff81862bc9: acpi_hw_gpe_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_write(u64 value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff819a00f5)
Location: drivers/acpi/acpica/hwgpe.c:81
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff819a0410-ffffffff819a0478: acpi_hw_gpe_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_write(u64 value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff819e6dc4)
Location: drivers/acpi/acpica/hwgpe.c:81
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff819e70e0-ffffffff819e7148: acpi_hw_gpe_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_gpe_write(u64 value, struct acpi_gpe_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81a31b14)
Location: drivers/acpi/acpica/hwgpe.c:81
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
```
**Symbols:**

```
ffffffff81a31e30-ffffffff81a31e98: acpi_hw_gpe_write (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
