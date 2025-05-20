# Function: <code>i2c_smbus_write_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167a8d0)
Location: drivers/i2c/i2c-core.c:2653
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff8167a8d0-ffffffff8167a905: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de854)
Location: drivers/i2c/i2c-core.c:2858
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff816dc030-ffffffff816dc065: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170ec14)
Location: drivers/i2c/i2c-core.c:3146
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8170c370-ffffffff8170c3a5: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817231f0)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817231f0-ffffffff8172321b: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794610)
Location: drivers/i2c/i2c-core-smbus.c:114
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81794610-ffffffff8179463b: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d7170)
Location: drivers/i2c/i2c-core-smbus.c:115
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817d7170-ffffffff817d719b: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe2d0)
Location: drivers/i2c/i2c-core-smbus.c:115
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817fe2d0-ffffffff817fe2fb: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f500)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8183f500-ffffffff8183f52c: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870ea0)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81870ea0-ffffffff81870ecc: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944ee0)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81944ee0-ffffffff81944f0c: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194af20)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8194af20-ffffffff8194af4c: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192ea60)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8192ea60-ffffffff8192ea8c: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1c90)
Location: drivers/i2c/i2c-core-smbus.c:121
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff819d1c90-ffffffff819d1cbc: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b342b0)
Location: drivers/i2c/i2c-core-smbus.c:122
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81b342b0-ffffffff81b342ee: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc92d0)
Location: drivers/i2c/i2c-core-smbus.c:122
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cc92d0-ffffffff81cc930e: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30ff0)
Location: drivers/i2c/i2c-core-smbus.c:122
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d30ff0-ffffffff81d3102e: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6fd0)
Location: drivers/i2c/i2c-core-smbus.c:122
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de6fd0-ffffffff81de700e: i2c_smbus_write_byte (STB_GLOBAL)
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
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4ac0)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffff800010ab4ac0-ffff800010ab4b08: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95cf4)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
```
**Symbols:**

```
c0b95cf4-c0b95d38: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98d00)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
```
**Symbols:**

```
c000000000b98d00-c000000000b98d30: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbf30)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
```
**Symbols:**

```
ffffffe0006bbf30-ffffffe0006bbf70: i2c_smbus_write_byte (STB_GLOBAL)
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
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81865030)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81865030-ffffffff8186505c: i2c_smbus_write_byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client *client, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818802e0)
Location: drivers/i2c/i2c-core-smbus.c:113
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff818802e0-ffffffff8188030c: i2c_smbus_write_byte (STB_GLOBAL)
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
