# Function: <code>i2c_smbus_write_i2c_block_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167aee0)
Location: drivers/i2c/i2c-core.c:2818
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff8167aee0-ffffffff8167afe3: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dc650)
Location: drivers/i2c/i2c-core.c:3023
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff816dc650-ffffffff816dc750: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170c990)
Location: drivers/i2c/i2c-core.c:3311
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff8170c990-ffffffff8170ca90: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81723820)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81723820-ffffffff8172391d: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794c50)
Location: drivers/i2c/i2c-core-smbus.c:279
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81794c50-ffffffff81794d4d: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d77a0)
Location: drivers/i2c/i2c-core-smbus.c:280
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff817d77a0-ffffffff817d789c: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe900)
Location: drivers/i2c/i2c-core-smbus.c:280
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff817fe900-ffffffff817fe9fc: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183faf0)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff8183faf0-ffffffff8183fbde: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81871490)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81871490-ffffffff8187157e: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81945370)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81945370-ffffffff8194545e: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194b3b0)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff8194b3b0-ffffffff8194b49e: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192eef0)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff8192eef0-ffffffff8192efd2: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d2120)
Location: drivers/i2c/i2c-core-smbus.c:286
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff819d2120-ffffffff819d2202: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b348d0)
Location: drivers/i2c/i2c-core-smbus.c:287
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81b348d0-ffffffff81b349fb: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9990)
Location: drivers/i2c/i2c-core-smbus.c:287
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81cc9990-ffffffff81cc9abb: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d316b0)
Location: drivers/i2c/i2c-core-smbus.c:287
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81d316b0-ffffffff81d317db: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de7690)
Location: drivers/i2c/i2c-core-smbus.c:287
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81de7690-ffffffff81de77bb: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab5090)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/stmpe-i2c.c:i2c_block_write
  - drivers/mfd/tc3589x.c:tc3589x_block_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffff800010ab5090-ffff800010ab5134: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b96260)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/stmpe-i2c.c:i2c_block_write
  - drivers/mfd/tc3589x.c:tc3589x_block_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
c0b96260-c0b962f0: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b993d0)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_write_buf
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/stmpe-i2c.c:i2c_block_write
  - drivers/mfd/tc3589x.c:tc3589x_block_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
c000000000b993d0-c000000000b99480: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bc30e)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/stmpe-i2c.c:i2c_block_write
  - drivers/mfd/tc3589x.c:tc3589x_block_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffe0006bc30e-ffffffe0006bc380: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81865620)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff81865620-ffffffff8186570e: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client *client, u8 command, u8 length, const u8 *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818808d0)
Location: drivers/i2c/i2c-core-smbus.c:278
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write
  - drivers/mfd/da903x.c:da9034_mask_events
  - drivers/mfd/da903x.c:da9034_unmask_events
  - drivers/mfd/da903x.c:da9030_mask_events
  - drivers/mfd/da903x.c:da9030_unmask_events
  - drivers/mfd/da903x.c:da903x_writes
  - drivers/mfd/max8997.c:max8997_bulk_write
  - drivers/mfd/max8998.c:max8998_bulk_write
```
**Symbols:**

```
ffffffff818808d0-ffffffff818809be: i2c_smbus_write_i2c_block_data (STB_GLOBAL)
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
