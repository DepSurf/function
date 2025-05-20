# Function: <code>i2c_acpi_get_info</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170a510)
Location: drivers/i2c/i2c-core.c:173
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff8170a510-ffffffff8170a6c1: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81723ee0)
Location: drivers/i2c/i2c-core-acpi.c:117
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81723ee0-ffffffff8172409d: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795350)
Location: drivers/i2c/i2c-core-acpi.c:117
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81795350-ffffffff81795506: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d7e20)
Location: drivers/i2c/i2c-core-acpi.c:117
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff817d7e20-ffffffff817d7fc4: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817fefb0)
Location: drivers/i2c/i2c-core-acpi.c:140
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff817fefb0-ffffffff817ff157: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818401d0)
Location: drivers/i2c/i2c-core-acpi.c:176
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff818401d0-ffffffff8184032e: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81871b20)
Location: drivers/i2c/i2c-core-acpi.c:177
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81871b20-ffffffff81871c67: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81945c30)
Location: drivers/i2c/i2c-core-acpi.c:177
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81945c30-ffffffff81945d77: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194bb70)
Location: drivers/i2c/i2c-core-acpi.c:177
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff8194bb70-ffffffff8194bcbd: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8192f6d0)
Location: drivers/i2c/i2c-core-acpi.c:177
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff8192f6d0-ffffffff8192f81d: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d2970)
Location: drivers/i2c/i2c-core-acpi.c:209
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff819d2970-ffffffff819d2abd: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35130)
Location: drivers/i2c/i2c-core-acpi.c:212
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81b35130-ffffffff81b3527d: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cca2c0)
Location: drivers/i2c/i2c-core-acpi.c:232
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81cca2c0-ffffffff81cca407: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32010)
Location: drivers/i2c/i2c-core-acpi.c:232
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81d32010-ffffffff81d32156: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de7ff0)
Location: drivers/i2c/i2c-core-acpi.c:232
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81de7ff0-ffffffff81de8136: i2c_acpi_get_info (STB_LOCAL)
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
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab52c8)
Location: drivers/i2c/i2c-core-acpi.c:177
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffff800010ab52c8-ffff800010ab540c: i2c_acpi_get_info (STB_LOCAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81865cb0)
Location: drivers/i2c/i2c-core-acpi.c:177
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81865cb0-ffffffff81865df7: i2c_acpi_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int i2c_acpi_get_info(struct acpi_device *adev, struct i2c_board_info *info, struct i2c_adapter *adapter, acpi_handle *adapter_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81880f60)
Location: drivers/i2c/i2c-core-acpi.c:177
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81880f60-ffffffff818810a7: i2c_acpi_get_info (STB_LOCAL)
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
