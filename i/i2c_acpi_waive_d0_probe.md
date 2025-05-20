# Function: <code>i2c_acpi_waive_d0_probe</code>

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
bool i2c_acpi_waive_d0_probe(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b34dd0)
Location: drivers/i2c/i2c-core-acpi.c:535
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81b34dd0-ffffffff81b34e2c: i2c_acpi_waive_d0_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool i2c_acpi_waive_d0_probe(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cc9ee0)
Location: drivers/i2c/i2c-core-acpi.c:555
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81cc9ee0-ffffffff81cc9f3c: i2c_acpi_waive_d0_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool i2c_acpi_waive_d0_probe(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d31c30)
Location: drivers/i2c/i2c-core-acpi.c:544
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81d31c30-ffffffff81d31c8c: i2c_acpi_waive_d0_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool i2c_acpi_waive_d0_probe(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de7c10)
Location: drivers/i2c/i2c-core-acpi.c:544
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81de7c10-ffffffff81de7c6c: i2c_acpi_waive_d0_probe (STB_GLOBAL)
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
