# Function: <code>i2c_client_get_device_id</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct i2c_device_id *i2c_client_get_device_id(const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc47e0)
Location: drivers/i2c/i2c-core-base.c:2245
Inline: False
Direct callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
**Symbols:**

```
ffffffff81cc47e0-ffffffff81cc4849: i2c_client_get_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct i2c_device_id *i2c_client_get_device_id(const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c760)
Location: drivers/i2c/i2c-core-base.c:2358
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
**Symbols:**

```
ffffffff81d2c760-ffffffff81d2c7c9: i2c_client_get_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct i2c_device_id *i2c_client_get_device_id(const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de2630)
Location: drivers/i2c/i2c-core-base.c:2376
Inline: False
Direct callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/adp5520.c:adp5520_probe
```
**Symbols:**

```
ffffffff81de2630-ffffffff81de2699: i2c_client_get_device_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
