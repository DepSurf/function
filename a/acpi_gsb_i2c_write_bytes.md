# Function: <code>acpi_gsb_i2c_write_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167db24)
Location: drivers/i2c/i2c-core.c:263
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de8bc)
Location: drivers/i2c/i2c-core.c:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170ec7c)
Location: drivers/i2c/i2c-core.c:454
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff817248f2)
Location: drivers/i2c/i2c-core-acpi.c:457
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff81795dc8)
Location: drivers/i2c/i2c-core-acpi.c:457
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8844)
Location: drivers/i2c/i2c-core-acpi.c:468
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff88b)
Location: drivers/i2c/i2c-core-acpi.c:500
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff81840ad8)
Location: drivers/i2c/i2c-core-acpi.c:523
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff81872438)
Location: drivers/i2c/i2c-core-acpi.c:552
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_gsb_i2c_write_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:544
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81946560-ffffffff819466ad: acpi_gsb_i2c_write_bytes (STB_LOCAL)
ffffffff81946c9c-ffffffff81946cb8: acpi_gsb_i2c_write_bytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_gsb_i2c_write_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:544
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8194c4c0-ffffffff8194c60d: acpi_gsb_i2c_write_bytes (STB_LOCAL)
ffffffff81c24e48-ffffffff81c24e64: acpi_gsb_i2c_write_bytes.cold (STB_LOCAL)
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
In drivers/i2c/i2c-core-acpi.c (ffffffff8192ff95)
Location: drivers/i2c/i2c-core-acpi.c:540
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff819d3265)
Location: drivers/i2c/i2c-core-acpi.c:573
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_gsb_i2c_write_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:589
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81b356f0-ffffffff81b3586a: acpi_gsb_i2c_write_bytes (STB_LOCAL)
ffffffff81ef18f2-ffffffff81ef190d: acpi_gsb_i2c_write_bytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_gsb_i2c_write_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cca920)
Location: drivers/i2c/i2c-core-acpi.c:609
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cca920-ffffffff81ccaab2: acpi_gsb_i2c_write_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_gsb_i2c_write_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32690)
Location: drivers/i2c/i2c-core-acpi.c:598
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d32690-ffffffff81d3284c: acpi_gsb_i2c_write_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_gsb_i2c_write_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8670)
Location: drivers/i2c/i2c-core-acpi.c:598
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de8670-ffffffff81de882c: acpi_gsb_i2c_write_bytes (STB_LOCAL)
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
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5e70)
Location: drivers/i2c/i2c-core-acpi.c:552
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818665c8)
Location: drivers/i2c/i2c-core-acpi.c:552
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
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
In drivers/i2c/i2c-core-acpi.c (ffffffff81881878)
Location: drivers/i2c/i2c-core-acpi.c:552
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
