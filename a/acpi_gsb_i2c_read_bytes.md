# Function: <code>acpi_gsb_i2c_read_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167d6d0)
Location: drivers/i2c/i2c-core.c:231
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff8167d6d0-ffffffff8167d844: acpi_gsb_i2c_read_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de440)
Location: drivers/i2c/i2c-core.c:328
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff816de440-ffffffff816de5d6: acpi_gsb_i2c_read_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170e800)
Location: drivers/i2c/i2c-core.c:422
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8170e800-ffffffff8170e996: acpi_gsb_i2c_read_bytes (STB_LOCAL)
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
In drivers/i2c/i2c-core-acpi.c (ffffffff81724721)
Location: drivers/i2c/i2c-core-acpi.c:425
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
In drivers/i2c/i2c-core-acpi.c (ffffffff81795bf7)
Location: drivers/i2c/i2c-core-acpi.c:425
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
In drivers/i2c/i2c-core-acpi.c (ffffffff817d86a5)
Location: drivers/i2c/i2c-core-acpi.c:425
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
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff963)
Location: drivers/i2c/i2c-core-acpi.c:457
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
In drivers/i2c/i2c-core-acpi.c (ffffffff81840bbd)
Location: drivers/i2c/i2c-core-acpi.c:480
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
In drivers/i2c/i2c-core-acpi.c (ffffffff8187251d)
Location: drivers/i2c/i2c-core-acpi.c:509
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
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:501
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81946070-ffffffff81946211: acpi_gsb_i2c_read_bytes (STB_LOCAL)
ffffffff81946c53-ffffffff81946c7c: acpi_gsb_i2c_read_bytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:501
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8194bfb0-ffffffff8194c151: acpi_gsb_i2c_read_bytes (STB_LOCAL)
ffffffff81c24dff-ffffffff81c24e28: acpi_gsb_i2c_read_bytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:497
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8192fc10-ffffffff8192fdc6: acpi_gsb_i2c_read_bytes (STB_LOCAL)
ffffffff81c16e73-ffffffff81c16e9c: acpi_gsb_i2c_read_bytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:530
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff819d2ee0-ffffffff819d3093: acpi_gsb_i2c_read_bytes (STB_LOCAL)
ffffffff81d25b6d-ffffffff81d25b96: acpi_gsb_i2c_read_bytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:546
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81b354f0-ffffffff81b356f0: acpi_gsb_i2c_read_bytes (STB_LOCAL)
ffffffff81ef18c9-ffffffff81ef18f2: acpi_gsb_i2c_read_bytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cca6e0)
Location: drivers/i2c/i2c-core-acpi.c:566
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cca6e0-ffffffff81cca910: acpi_gsb_i2c_read_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32450)
Location: drivers/i2c/i2c-core-acpi.c:555
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d32450-ffffffff81d32680: acpi_gsb_i2c_read_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_gsb_i2c_read_bytes(struct i2c_client *client, u8 cmd, u8 *data, u8 data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8430)
Location: drivers/i2c/i2c-core-acpi.c:555
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de8430-ffffffff81de8660: acpi_gsb_i2c_read_bytes (STB_LOCAL)
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
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5d28)
Location: drivers/i2c/i2c-core-acpi.c:509
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
In drivers/i2c/i2c-core-acpi.c (ffffffff818666ad)
Location: drivers/i2c/i2c-core-acpi.c:509
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
In drivers/i2c/i2c-core-acpi.c (ffffffff8188195d)
Location: drivers/i2c/i2c-core-acpi.c:509
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
