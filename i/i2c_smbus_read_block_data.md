# Function: <code>i2c_smbus_read_block_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167aab0)
Location: drivers/i2c/i2c-core.c:2755
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff8167aab0-ffffffff8167ab99: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dc210)
Location: drivers/i2c/i2c-core.c:2960
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff816dc210-ffffffff816dc2f7: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170c550)
Location: drivers/i2c/i2c-core.c:3248
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8170c550-ffffffff8170c637: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817233c0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817233c0-ffffffff817234b5: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817947e0)
Location: drivers/i2c/i2c-core-smbus.c:216
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817947e0-ffffffff817948d5: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:217
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817d7c5b-ffffffff817d7c67: i2c_smbus_read_block_data.cold.2 (STB_LOCAL)
ffffffff817d7340-ffffffff817d7429: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:217
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817fedbb-ffffffff817fedc7: i2c_smbus_read_block_data.cold.3 (STB_LOCAL)
ffffffff817fe4a0-ffffffff817fe589: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81840029-ffffffff81840035: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff8183f6d0-ffffffff8183f7a5: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff818719c8-ffffffff818719d4: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff81871070-ffffffff81871145: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81945ab1-ffffffff81945abd: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff819450b0-ffffffff81945185: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81c24d83-ffffffff81c24d8f: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff8194b0f0-ffffffff8194b1c5: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81c16e2c-ffffffff81c16e38: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff8192ec30-ffffffff8192ed07: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:223
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d25b26-ffffffff81d25b32: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff819d1e60-ffffffff819d1f37: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:224
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81ef1882-ffffffff81ef188e: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff81b34570-ffffffff81b3467f: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc95e0)
Location: drivers/i2c/i2c-core-smbus.c:224
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cc95e0-ffffffff81cc96fb: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d31300)
Location: drivers/i2c/i2c-core-smbus.c:224
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d31300-ffffffff81d3141b: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de72e0)
Location: drivers/i2c/i2c-core-smbus.c:224
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de72e0-ffffffff81de73fb: i2c_smbus_read_block_data (STB_GLOBAL)
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
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4cf8)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffff800010ab4cf8-ffff800010ab4da8: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95f38)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
```
**Symbols:**

```
c0b95f38-c0b95fe8: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98f30)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
```
**Symbols:**

```
c000000000b98f30-c000000000b98ff8: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bc09c)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
```
**Symbols:**

```
ffffffe0006bc09c-ffffffe0006bc0fe: i2c_smbus_read_block_data (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81865b58-ffffffff81865b64: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff81865200-ffffffff818652d5: i2c_smbus_read_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_block_data(const struct i2c_client *client, u8 command, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:215
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81880e08-ffffffff81880e14: i2c_smbus_read_block_data.cold (STB_LOCAL)
ffffffff818804b0-ffffffff81880585: i2c_smbus_read_block_data (STB_GLOBAL)
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
