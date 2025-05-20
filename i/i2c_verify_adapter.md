# Function: <code>i2c_verify_adapter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81677fc0)
Location: drivers/i2c/i2c-core.c:1334
Inline: False
```
**Symbols:**

```
ffffffff81677fc0-ffffffff81677fe0: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816d9dc7)
Location: drivers/i2c/i2c-core.c:1502
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_match_adapter
```
**Symbols:**

```
ffffffff816d8860-ffffffff816d8880: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81709f87)
Location: drivers/i2c/i2c-core.c:1638
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_match_adapter
```
**Symbols:**

```
ffffffff81708960-ffffffff81708980: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8171e550)
Location: drivers/i2c/i2c-core-base.c:1084
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter
```
**Symbols:**

```
ffffffff8171e550-ffffffff8171e56d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8178f7f0)
Location: drivers/i2c/i2c-core-base.c:1101
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
```
**Symbols:**

```
ffffffff8178f7f0-ffffffff8178f80d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d2110)
Location: drivers/i2c/i2c-core-base.c:1080
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
```
**Symbols:**

```
ffffffff817d2110-ffffffff817d212d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817f9270)
Location: drivers/i2c/i2c-core-base.c:1092
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
```
**Symbols:**

```
ffffffff817f9270-ffffffff817f928d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81839f80)
Location: drivers/i2c/i2c-core-base.c:1181
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
```
**Symbols:**

```
ffffffff81839f80-ffffffff81839f9d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186b8f0)
Location: drivers/i2c/i2c-core-base.c:1186
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
```
**Symbols:**

```
ffffffff8186b8f0-ffffffff8186b90d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8193f5f0)
Location: drivers/i2c/i2c-core-base.c:1148
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff8193f5f0-ffffffff8193f60d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819457a0)
Location: drivers/i2c/i2c-core-base.c:1276
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff819457a0-ffffffff819457bd: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81928f70)
Location: drivers/i2c/i2c-core-base.c:1310
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81928f70-ffffffff81928f8d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cc0c0)
Location: drivers/i2c/i2c-core-base.c:1311
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff819cc0c0-ffffffff819cc0dd: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b2d8e0)
Location: drivers/i2c/i2c-core-base.c:1313
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81b2d8e0-ffffffff81b2d909: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc1a20)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81cc1a20-ffffffff81cc1a49: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a4be)
Location: drivers/i2c/i2c-core-base.c:1351
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81d29430-ffffffff81d29459: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de037e)
Location: drivers/i2c/i2c-core-base.c:1361
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81ddf2f0-ffffffff81ddf319: i2c_verify_adapter (STB_GLOBAL)
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
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010aae760)
Location: drivers/i2c/i2c-core-base.c:1186
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
```
**Symbols:**

```
ffff800010aae760-ffff800010aae7a0: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b900ac)
Location: drivers/i2c/i2c-core-base.c:1186
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
```
**Symbols:**

```
c0b900ac-c0b900dc: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b908e0)
Location: drivers/i2c/i2c-core-base.c:1186
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
```
**Symbols:**

```
c000000000b908e0-c000000000b90918: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b6c98)
Location: drivers/i2c/i2c-core-base.c:1186
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
```
**Symbols:**

```
ffffffe0006b6c98-ffffffe0006b6ccc: i2c_verify_adapter (STB_GLOBAL)
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
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8185fa80)
Location: drivers/i2c/i2c-core-base.c:1186
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
```
**Symbols:**

```
ffffffff8185fa80-ffffffff8185fa9d: i2c_verify_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct i2c_adapter *i2c_verify_adapter(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187ac90)
Location: drivers/i2c/i2c-core-base.c:1186
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
```
**Symbols:**

```
ffffffff8187ac90-ffffffff8187acad: i2c_verify_adapter (STB_GLOBAL)
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
