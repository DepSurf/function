# Function: <code>i2c_smbus_read_i2c_block_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167acb0)
Location: drivers/i2c/i2c-core.c:2798
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff8167acb0-ffffffff8167ada0: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dc400)
Location: drivers/i2c/i2c-core.c:3003
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff816dc400-ffffffff816dc4f1: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170c740)
Location: drivers/i2c/i2c-core.c:3291
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff8170c740-ffffffff8170c831: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817235c0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff817235c0-ffffffff817236c6: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817949e0)
Location: drivers/i2c/i2c-core-smbus.c:259
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff817949e0-ffffffff81794ae6: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:260
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff817d7c67-ffffffff817d7c73: i2c_smbus_read_i2c_block_data.cold.3 (STB_LOCAL)
ffffffff817d7530-ffffffff817d7628: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:260
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff817fedc7-ffffffff817fedd3: i2c_smbus_read_i2c_block_data.cold.4 (STB_LOCAL)
ffffffff817fe690-ffffffff817fe788: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81840035-ffffffff81840041: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff8183f8a0-ffffffff8183f984: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff818719d4-ffffffff818719e0: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff81871240-ffffffff81871324: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81945abd-ffffffff81945ac9: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff81945280-ffffffff81945363: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81c24d8f-ffffffff81c24d9b: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff8194b2c0-ffffffff8194b3a3: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81c16e38-ffffffff81c16e44: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff8192ee00-ffffffff8192eee4: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:266
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81d25b32-ffffffff81d25b3e: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff819d2030-ffffffff819d2114: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:267
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81ef188e-ffffffff81ef189a: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff81b347b0-ffffffff81b348cc: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9850)
Location: drivers/i2c/i2c-core-smbus.c:267
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81cc9850-ffffffff81cc9978: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d31570)
Location: drivers/i2c/i2c-core-smbus.c:267
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81d31570-ffffffff81d31698: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de7550)
Location: drivers/i2c/i2c-core-smbus.c:267
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81de7550-ffffffff81de7678: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4e50)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/stmpe-i2c.c:i2c_block_read
  - drivers/mfd/tc3589x.c:tc3589x_block_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffff800010ab4e50-ffff800010ab4f1c: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b96078)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/stmpe-i2c.c:i2c_block_read
  - drivers/mfd/tc3589x.c:tc3589x_block_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
c0b96078-c0b96138: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b990b0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_read_buf
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/stmpe-i2c.c:i2c_block_read
  - drivers/mfd/tc3589x.c:tc3589x_block_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
c000000000b990b0-c000000000b9918c: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bc170)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/stmpe-i2c.c:i2c_block_read
  - drivers/mfd/tc3589x.c:tc3589x_block_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffe0006bc170-ffffffe0006bc1ec: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81865b64-ffffffff81865b70: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff818653d0-ffffffff818654b4: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:258
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read
  - drivers/mfd/da903x.c:da9034_read_status
  - drivers/mfd/da903x.c:da9034_read_events
  - drivers/mfd/da903x.c:da9030_read_events
  - drivers/mfd/da903x.c:da903x_reads
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8997.c:max8997_bulk_read
  - drivers/mfd/max8998.c:max8998_bulk_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffff81880e14-ffffffff81880e20: i2c_smbus_read_i2c_block_data.cold (STB_LOCAL)
ffffffff81880680-ffffffff81880764: i2c_smbus_read_i2c_block_data (STB_GLOBAL)
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
