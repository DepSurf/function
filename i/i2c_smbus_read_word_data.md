# Function: <code>i2c_smbus_read_word_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167a9e0)
Location: drivers/i2c/i2c-core.c:2708
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff8167a9e0-ffffffff8167aa43: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dc140)
Location: drivers/i2c/i2c-core.c:2913
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff816dc140-ffffffff816dc1a3: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170c480)
Location: drivers/i2c/i2c-core.c:3201
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8170c480-ffffffff8170c4e3: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817232f0)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817232f0-ffffffff81723351: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794710)
Location: drivers/i2c/i2c-core-smbus.c:169
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81794710-ffffffff81794771: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d7270)
Location: drivers/i2c/i2c-core-smbus.c:170
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817d7270-ffffffff817d72d1: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe3d0)
Location: drivers/i2c/i2c-core-smbus.c:170
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817fe3d0-ffffffff817fe431: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f600)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8183f600-ffffffff8183f662: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870fa0)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81870fa0-ffffffff81871002: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819455de)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81944fe0-ffffffff81945042: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194b61e)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8194b020-ffffffff8194b082: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192f164)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8192eb60-ffffffff8192ebc2: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d2394)
Location: drivers/i2c/i2c-core-smbus.c:176
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff819d1d90-ffffffff819d1df2: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34bad)
Location: drivers/i2c/i2c-core-smbus.c:177
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81b34430-ffffffff81b344ca: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9c7d)
Location: drivers/i2c/i2c-core-smbus.c:177
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cc9480-ffffffff81cc951a: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d318ee)
Location: drivers/i2c/i2c-core-smbus.c:177
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d311a0-ffffffff81d3123a: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de78ce)
Location: drivers/i2c/i2c-core-smbus.c:177
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de7180-ffffffff81de721a: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4c00)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffff800010ab4c00-ffff800010ab4c80: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95e38)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
c0b95e38-c0b95eb8: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98e30)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
c000000000b98e30-c000000000b98eb0: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bc006)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffe0006bc006-ffffffe0006bc050: i2c_smbus_read_word_data (STB_GLOBAL)
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81865130)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81865130-ffffffff81865192: i2c_smbus_read_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 i2c_smbus_read_word_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818803e0)
Location: drivers/i2c/i2c-core-smbus.c:168
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_read_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff818803e0-ffffffff81880442: i2c_smbus_read_word_data (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
