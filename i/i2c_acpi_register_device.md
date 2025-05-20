# Function: <code>i2c_acpi_register_device</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void i2c_acpi_register_device(struct i2c_adapter *adapter, struct acpi_device *adev, struct i2c_board_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170d8f0)
Location: drivers/i2c/i2c-core.c:229
Inline: True
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff8170d8f0-ffffffff8170d951: i2c_acpi_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void i2c_acpi_register_device(struct i2c_adapter *adapter, struct acpi_device *adev, struct i2c_board_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724400)
Location: drivers/i2c/i2c-core-acpi.c:175
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81724400-ffffffff81724461: i2c_acpi_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void i2c_acpi_register_device(struct i2c_adapter *adapter, struct acpi_device *adev, struct i2c_board_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795760)
Location: drivers/i2c/i2c-core-acpi.c:175
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81795760-ffffffff817957c1: i2c_acpi_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void i2c_acpi_register_device(struct i2c_adapter *adapter, struct acpi_device *adev, struct i2c_board_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8220)
Location: drivers/i2c/i2c-core-acpi.c:175
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff817d8220-ffffffff817d8281: i2c_acpi_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void i2c_acpi_register_device(struct i2c_adapter *adapter, struct acpi_device *adev, struct i2c_board_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff4e0)
Location: drivers/i2c/i2c-core-acpi.c:198
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff817ff4e0-ffffffff817ff541: i2c_acpi_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818408f3)
Location: drivers/i2c/i2c-core-acpi.c:220
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81872253)
Location: drivers/i2c/i2c-core-acpi.c:221
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819464d8)
Location: drivers/i2c/i2c-core-acpi.c:221
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81946c1e-ffffffff81946c53: i2c_acpi_register_device.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c42b)
Location: drivers/i2c/i2c-core-acpi.c:221
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81c24dca-ffffffff81c24dff: i2c_acpi_register_device.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8193036b)
Location: drivers/i2c/i2c-core-acpi.c:221
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d363d)
Location: drivers/i2c/i2c-core-acpi.c:253
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35d3a)
Location: drivers/i2c/i2c-core-acpi.c:257
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccafb7)
Location: drivers/i2c/i2c-core-acpi.c:277
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32d76)
Location: drivers/i2c/i2c-core-acpi.c:277
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8d96)
Location: drivers/i2c/i2c-core-acpi.c:277
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5b8c)
Location: drivers/i2c/i2c-core-acpi.c:221
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818663e3)
Location: drivers/i2c/i2c-core-acpi.c:221
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881693)
Location: drivers/i2c/i2c-core-acpi.c:221
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
