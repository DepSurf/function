# Function: <code>i2c_smbus_write_word_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167aa50)
Location: drivers/i2c/i2c-core.c:2729
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
```
**Symbols:**

```
ffffffff8167aa50-ffffffff8167aaac: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de838)
Location: drivers/i2c/i2c-core.c:2934
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
```
**Symbols:**

```
ffffffff816dc1b0-ffffffff816dc20c: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170ebf8)
Location: drivers/i2c/i2c-core.c:3222
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
```
**Symbols:**

```
ffffffff8170c4f0-ffffffff8170c54c: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81723360)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81723360-ffffffff817233b9: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794780)
Location: drivers/i2c/i2c-core-smbus.c:190
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81794780-ffffffff817947d9: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d72e0)
Location: drivers/i2c/i2c-core-smbus.c:191
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817d72e0-ffffffff817d7339: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe440)
Location: drivers/i2c/i2c-core-smbus.c:191
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817fe440-ffffffff817fe499: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f670)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8183f670-ffffffff8183f6ca: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81871010)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81871010-ffffffff8187106a: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81945050)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81945050-ffffffff819450aa: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194b090)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8194b090-ffffffff8194b0ea: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192ebd0)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8192ebd0-ffffffff8192ec2a: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1e00)
Location: drivers/i2c/i2c-core-smbus.c:197
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff819d1e00-ffffffff819d1e5a: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b344d0)
Location: drivers/i2c/i2c-core-smbus.c:198
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81b344d0-ffffffff81b34562: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9530)
Location: drivers/i2c/i2c-core-smbus.c:198
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cc9530-ffffffff81cc95c2: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d31250)
Location: drivers/i2c/i2c-core-smbus.c:198
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d31250-ffffffff81d312e2: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de7230)
Location: drivers/i2c/i2c-core-smbus.c:198
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de7230-ffffffff81de72c2: i2c_smbus_write_word_data (STB_GLOBAL)
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
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4c80)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffff800010ab4c80-ffff800010ab4cf8: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95eb8)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
```
**Symbols:**

```
c0b95eb8-c0b95f38: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98eb0)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
```
**Symbols:**

```
c000000000b98eb0-c000000000b98f2c: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bc050)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
```
**Symbols:**

```
ffffffe0006bc050-ffffffe0006bc09c: i2c_smbus_write_word_data (STB_GLOBAL)
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
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818651a0)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff818651a0-ffffffff818651fa: i2c_smbus_write_word_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client *client, u8 command, u16 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880450)
Location: drivers/i2c/i2c-core-smbus.c:189
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81880450-ffffffff818804aa: i2c_smbus_write_word_data (STB_GLOBAL)
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
