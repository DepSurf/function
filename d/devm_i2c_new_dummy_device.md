# Function: <code>devm_i2c_new_dummy_device</code>

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
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183d620)
Location: drivers/i2c/i2c-core-base.c:945
Inline: False
```
**Symbols:**

```
ffffffff8183d620-ffffffff8183d69f: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186efc0)
Location: drivers/i2c/i2c-core-base.c:950
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffff8186efc0-ffffffff8186f03f: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81942f40)
Location: drivers/i2c/i2c-core-base.c:912
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffff81942f40-ffffffff81943013: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81949320)
Location: drivers/i2c/i2c-core-base.c:1040
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffff81949320-ffffffff819493f3: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192cc50)
Location: drivers/i2c/i2c-core-base.c:1078
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffff8192cc50-ffffffff8192ccfe: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cfe20)
Location: drivers/i2c/i2c-core-base.c:1079
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffff819cfe20-ffffffff819cfece: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b31ce0)
Location: drivers/i2c/i2c-core-base.c:1081
Inline: False
```
**Symbols:**

```
ffffffff81b31ce0-ffffffff81b31dae: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc6900)
Location: drivers/i2c/i2c-core-base.c:1075
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
```
**Symbols:**

```
ffffffff81cc6900-ffffffff81cc69ce: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2e5a0)
Location: drivers/i2c/i2c-core-base.c:1119
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
```
**Symbols:**

```
ffffffff81d2e5a0-ffffffff81d2e675: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de4550)
Location: drivers/i2c/i2c-core-base.c:1127
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
```
**Symbols:**

```
ffffffff81de4550-ffffffff81de4625: devm_i2c_new_dummy_device (STB_GLOBAL)
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
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab29b8)
Location: drivers/i2c/i2c-core-base.c:950
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffff800010ab29b8-ffff800010ab2aa4: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b94020)
Location: drivers/i2c/i2c-core-base.c:950
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
c0b94020-c0b940a4: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b96360)
Location: drivers/i2c/i2c-core-base.c:950
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
c000000000b96360-c000000000b96428: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba628)
Location: drivers/i2c/i2c-core-base.c:950
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffe0006ba628-ffffffe0006ba6ac: devm_i2c_new_dummy_device (STB_GLOBAL)
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
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81863150)
Location: drivers/i2c/i2c-core-base.c:950
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffff81863150-ffffffff818631cf: devm_i2c_new_dummy_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct i2c_client *devm_i2c_new_dummy_device(struct device *dev, struct i2c_adapter *adapter, u16 address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187e3b0)
Location: drivers/i2c/i2c-core-base.c:950
Inline: False
Direct callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
**Symbols:**

```
ffffffff8187e3b0-ffffffff8187e42f: devm_i2c_new_dummy_device (STB_GLOBAL)
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
