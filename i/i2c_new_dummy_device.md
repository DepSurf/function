# Function: <code>i2c_new_dummy_device</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183d520)
Location: drivers/i2c/i2c-core-base.c:891
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_secondary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
**Symbols:**

```
ffffffff8183d520-ffffffff8183d587: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186ef20)
Location: drivers/i2c/i2c-core-base.c:896
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
```
**Symbols:**

```
ffffffff8186ef20-ffffffff8186ef87: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81943059)
Location: drivers/i2c/i2c-core-base.c:881
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max77836_init
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
ffffffff81942410-ffffffff81942477: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81949439)
Location: drivers/i2c/i2c-core-base.c:1009
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/max14577.c:max77836_init
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
ffffffff81948780-ffffffff819487e7: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192cd39)
Location: drivers/i2c/i2c-core-base.c:1053
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
```
**Symbols:**

```
ffffffff8192c100-ffffffff8192c167: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cff06)
Location: drivers/i2c/i2c-core-base.c:1054
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
```
**Symbols:**

```
ffffffff819cf2c0-ffffffff819cf327: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b31de6)
Location: drivers/i2c/i2c-core-base.c:1056
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
```
**Symbols:**

```
ffffffff81b31070-ffffffff81b310fa: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc6a16)
Location: drivers/i2c/i2c-core-base.c:1050
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffff81cc5a70-ffffffff81cc5afa: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2e6c6)
Location: drivers/i2c/i2c-core-base.c:1094
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffff81d2d700-ffffffff81d2d78a: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de4676)
Location: drivers/i2c/i2c-core-base.c:1102
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffffffff81de3640-ffffffff81de36ca: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab2b10)
Location: drivers/i2c/i2c-core-base.c:896
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
**Symbols:**

```
ffff800010ab28a0-ffff800010ab2928: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93f5c)
Location: drivers/i2c/i2c-core-base.c:896
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
```
**Symbols:**

```
c0b93f5c-c0b93ffc: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b96270)
Location: drivers/i2c/i2c-core-base.c:896
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
```
**Symbols:**

```
c000000000b96270-c000000000b96314: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba55e)
Location: drivers/i2c/i2c-core-base.c:896
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
```
**Symbols:**

```
ffffffe0006ba55e-ffffffe0006ba5e2: i2c_new_dummy_device (STB_GLOBAL)
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
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818630b0)
Location: drivers/i2c/i2c-core-base.c:896
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
```
**Symbols:**

```
ffffffff818630b0-ffffffff81863117: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct i2c_client *i2c_new_dummy_device(struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187e310)
Location: drivers/i2c/i2c-core-base.c:896
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
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
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
```
**Symbols:**

```
ffffffff8187e310-ffffffff8187e377: i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
