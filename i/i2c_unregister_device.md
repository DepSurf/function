# Function: <code>i2c_unregister_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81678f30)
Location: drivers/i2c/i2c-core.c:1100
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:__unregister_dummy
  - drivers/i2c/i2c-core.c:__unregister_client
  - drivers/i2c/i2c-core.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core.c:i2c_sysfs_delete_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_remove
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_remove
  - drivers/mfd/max8997.c:max8997_i2c_remove
  - drivers/mfd/max8997.c:max8997_i2c_remove
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_remove
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
```
**Symbols:**

```
ffffffff81678f30-ffffffff81678f44: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816da230)
Location: drivers/i2c/i2c-core.c:1225
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_remove
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core.c:__unregister_dummy
  - drivers/i2c/i2c-core.c:__unregister_client
  - drivers/i2c/i2c-core.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core.c:i2c_sysfs_delete_device
```
**Symbols:**

```
ffffffff816da230-ffffffff816da272: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170a800)
Location: drivers/i2c/i2c-core.c:1363
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core.c:__unregister_dummy
  - drivers/i2c/i2c-core.c:__unregister_client
  - drivers/i2c/i2c-core.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core.c:i2c_sysfs_delete_device
```
**Symbols:**

```
ffffffff8170a800-ffffffff8170a842: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8171f020)
Location: drivers/i2c/i2c-core-base.c:809
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
```
**Symbols:**

```
ffffffff8171f020-ffffffff8171f062: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791115)
Location: drivers/i2c/i2c-core-base.c:820
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
```
**Symbols:**

```
ffffffff81790e30-ffffffff81790e8a: i2c_unregister_device.part.37 (STB_LOCAL)
ffffffff81790e90-ffffffff81790ea7: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d3b7f)
Location: drivers/i2c/i2c-core-base.c:799
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
```
**Symbols:**

```
ffffffff817d3870-ffffffff817d38ca: i2c_unregister_device.part.31 (STB_LOCAL)
ffffffff817d38d0-ffffffff817d38e6: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817faadf)
Location: drivers/i2c/i2c-core-base.c:811
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/tps80031.c:tps80031_remove
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
```
**Symbols:**

```
ffffffff817fa9b0-ffffffff817faa0a: i2c_unregister_device.part.32 (STB_LOCAL)
ffffffff817faa10-ffffffff817faa26: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183b78f)
Location: drivers/i2c/i2c-core-base.c:833
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
ffffffff8183b6d0-ffffffff8183b72a: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff8183b730-ffffffff8183b74f: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186d11f)
Location: drivers/i2c/i2c-core-base.c:838
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
ffffffff8186d060-ffffffff8186d0ba: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff8186d0c0-ffffffff8186d0df: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81941501)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81940a70-ffffffff81940aca: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff81940ad0-ffffffff81940aef: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819478d1)
Location: drivers/i2c/i2c-core-base.c:951
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81946e40-ffffffff81946e9d: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff81946ea0-ffffffff81946ebf: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192b1e1)
Location: drivers/i2c/i2c-core-base.c:994
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff8192a740-ffffffff8192a7a8: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff8192a7b0-ffffffff8192a7cf: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819ce3b3)
Location: drivers/i2c/i2c-core-base.c:995
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff819cd8e0-ffffffff819cd948: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff819cd950-ffffffff819cd96f: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b2eab0)
Location: drivers/i2c/i2c-core-base.c:997
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81b2eab0-ffffffff81b2eb37: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc2750)
Location: drivers/i2c/i2c-core-base.c:998
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81cc2750-ffffffff81cc27d4: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a170)
Location: drivers/i2c/i2c-core-base.c:1013
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81d2a170-ffffffff81d2a1f4: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de0030)
Location: drivers/i2c/i2c-core-base.c:1021
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_destroy
  - drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:delete_device_store
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81de0030-ffffffff81de00b4: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab03bc)
Location: drivers/i2c/i2c-core-base.c:838
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
ffff800010ab0280-ffff800010ab0320: i2c_unregister_device.part.0 (STB_LOCAL)
ffff800010ab0320-ffff800010ab0358: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b919dc)
Location: drivers/i2c/i2c-core-base.c:838
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
c0b91914-c0b91958: i2c_unregister_device.part.0 (STB_LOCAL)
c0b91958-c0b91984: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b93304)
Location: drivers/i2c/i2c-core-base.c:838
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
c000000000b93200-c000000000b93274: i2c_unregister_device.part.0 (STB_LOCAL)
c000000000b93280-c000000000b932a8: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b85a4)
Location: drivers/i2c/i2c-core-base.c:838
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
ffffffe0006b84d0-ffffffe0006b8518: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffe0006b8518-ffffffe0006b854a: i2c_unregister_device (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818612af)
Location: drivers/i2c/i2c-core-base.c:838
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
ffffffff818611f0-ffffffff8186124a: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff81861250-ffffffff8186126f: i2c_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i2c_unregister_device(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187c4bf)
Location: drivers/i2c/i2c-core-base.c:838
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
Direct callers:
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/twl-core.c:twl_remove
  - drivers/mfd/max14577.c:max14577_i2c_remove
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_remove
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_remove
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/mfd/palmas.c:palmas_i2c_remove
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
**Symbols:**

```
ffffffff8187c400-ffffffff8187c45a: i2c_unregister_device.part.0 (STB_LOCAL)
ffffffff8187c460-ffffffff8187c47f: i2c_unregister_device (STB_GLOBAL)
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
