# Function: <code>i2c_new_dummy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167c7d0)
Location: drivers/i2c/i2c-core.c:1150
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
**Symbols:**

```
ffffffff8167c7d0-ffffffff8167c82f: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dd4b0)
Location: drivers/i2c/i2c-core.c:1277
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/i2c/i2c-core.c:i2c_new_secondary_device
```
**Symbols:**

```
ffffffff816dd4b0-ffffffff816dd50f: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170d830)
Location: drivers/i2c/i2c-core.c:1415
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/i2c/i2c-core.c:i2c_new_secondary_device
```
**Symbols:**

```
ffffffff8170d830-ffffffff8170d88f: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720da0)
Location: drivers/i2c/i2c-core-base.c:861
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_secondary_device
```
**Symbols:**

```
ffffffff81720da0-ffffffff81720e1e: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81792120)
Location: drivers/i2c/i2c-core-base.c:878
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_secondary_device
```
**Symbols:**

```
ffffffff81792120-ffffffff8179219e: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d4b30)
Location: drivers/i2c/i2c-core-base.c:857
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_secondary_device
```
**Symbols:**

```
ffffffff817d4b30-ffffffff817d4bae: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fbc80)
Location: drivers/i2c/i2c-core-base.c:869
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_secondary_device
```
**Symbols:**

```
ffffffff817fbc80-ffffffff817fbcfe: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183d5d8)
Location: drivers/i2c/i2c-core-base.c:915
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_secondary_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
**Symbols:**

```
ffffffff8183d590-ffffffff8183d5b2: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186ef90)
Location: drivers/i2c/i2c-core-base.c:920
Inline: False
```
**Symbols:**

```
ffffffff8186ef90-ffffffff8186efb2: i2c_new_dummy (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab2928)
Location: drivers/i2c/i2c-core-base.c:920
Inline: False
```
**Symbols:**

```
ffff800010ab2928-ffff800010ab29b8: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93ffc)
Location: drivers/i2c/i2c-core-base.c:920
Inline: False
```
**Symbols:**

```
c0b93ffc-c0b94020: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b96320)
Location: drivers/i2c/i2c-core-base.c:920
Inline: False
```
**Symbols:**

```
c000000000b96320-c000000000b9635c: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba5e2)
Location: drivers/i2c/i2c-core-base.c:920
Inline: False
```
**Symbols:**

```
ffffffe0006ba5e2-ffffffe0006ba628: i2c_new_dummy (STB_GLOBAL)
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
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81863120)
Location: drivers/i2c/i2c-core-base.c:920
Inline: False
```
**Symbols:**

```
ffffffff81863120-ffffffff81863142: i2c_new_dummy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187e380)
Location: drivers/i2c/i2c-core-base.c:920
Inline: False
```
**Symbols:**

```
ffffffff8187e380-ffffffff8187e3a2: i2c_new_dummy (STB_GLOBAL)
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
