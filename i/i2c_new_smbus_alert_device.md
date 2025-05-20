# Function: <code>i2c_new_smbus_alert_device</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819441d0)
Location: drivers/i2c/i2c-core-smbus.c:690
Inline: False
```
**Symbols:**

```
ffffffff819441d0-ffffffff81944240: i2c_new_smbus_alert_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194a250)
Location: drivers/i2c/i2c-core-smbus.c:690
Inline: False
```
**Symbols:**

```
ffffffff8194a250-ffffffff8194a2c0: i2c_new_smbus_alert_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192db20)
Location: drivers/i2c/i2c-core-smbus.c:684
Inline: False
```
**Symbols:**

```
ffffffff8192db20-ffffffff8192db90: i2c_new_smbus_alert_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d0d30)
Location: drivers/i2c/i2c-core-smbus.c:692
Inline: False
```
**Symbols:**

```
ffffffff819d0d30-ffffffff819d0da0: i2c_new_smbus_alert_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34c8d)
Location: drivers/i2c/i2c-core-smbus.c:693
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
**Symbols:**

```
ffffffff81b33180-ffffffff81b33213: i2c_new_smbus_alert_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9d6d)
Location: drivers/i2c/i2c-core-smbus.c:693
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
**Symbols:**

```
ffffffff81cc76d0-ffffffff81cc7763: i2c_new_smbus_alert_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d31abd)
Location: drivers/i2c/i2c-core-smbus.c:693
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
**Symbols:**

```
ffffffff81d2f400-ffffffff81d2f493: i2c_new_smbus_alert_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_smbus_alert_device(struct i2c_adapter *adapter, struct i2c_smbus_alert_setup *setup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de7a9d)
Location: drivers/i2c/i2c-core-smbus.c:693
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
**Symbols:**

```
ffffffff81de53b0-ffffffff81de5443: i2c_new_smbus_alert_device (STB_GLOBAL)
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
