# Function: <code>acpi_map_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_ioremap *acpi_map_lookup(acpi_physical_address phys, acpi_size size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814798b4)
Location: drivers/acpi/osl.c:282
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_write_memory
```
**Symbols:**

```
ffffffff814798b4-ffffffff814798ea: acpi_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_ioremap *acpi_map_lookup(acpi_physical_address phys, acpi_size size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c7f21)
Location: drivers/acpi/osl.c:214
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff814c7f21-ffffffff814c7f57: acpi_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_ioremap *acpi_map_lookup(acpi_physical_address phys, acpi_size size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814e9e31)
Location: drivers/acpi/osl.c:215
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
**Symbols:**

```
ffffffff814e9e31-ffffffff814e9e67: acpi_map_lookup (STB_LOCAL)
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
In drivers/acpi/osl.c (ffffffff814f64c8)
Location: drivers/acpi/osl.c:214
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
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
In drivers/acpi/osl.c (ffffffff81536c78)
Location: drivers/acpi/osl.c:214
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156c89d)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815844cd)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b50cf)
Location: drivers/acpi/osl.c:205
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d62ff)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8167ffff)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169ead6)
Location: drivers/acpi/osl.c:222
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681786)
Location: drivers/acpi/osl.c:225
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f6876)
Location: drivers/acpi/osl.c:225
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff818236c5)
Location: drivers/acpi/osl.c:224
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81954925)
Location: drivers/acpi/osl.c:224
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199ad25)
Location: drivers/acpi/osl.c:224
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e31a5)
Location: drivers/acpi/osl.c:224
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_unmap_generic_address
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763d10)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca05f)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b30df)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca5df)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e4465)
Location: drivers/acpi/osl.c:219
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
  - drivers/acpi/osl.c:acpi_os_read_memory
  - drivers/acpi/osl.c:acpi_os_get_iomem
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
