# Function: <code>i2c_acpi_find_adapter_by_handle</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170da4c)
Location: drivers/i2c/i2c-core.c:360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817241d0)
Location: drivers/i2c/i2c-core-acpi.c:317
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff817241d0-ffffffff81724204: i2c_acpi_find_adapter_by_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817955a0)
Location: drivers/i2c/i2c-core-acpi.c:317
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff817955a0-ffffffff817955d4: i2c_acpi_find_adapter_by_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8060)
Location: drivers/i2c/i2c-core-acpi.c:317
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff817d8060-ffffffff817d8092: i2c_acpi_find_adapter_by_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff1f0)
Location: drivers/i2c/i2c-core-acpi.c:340
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff817ff1f0-ffffffff817ff220: i2c_acpi_find_adapter_by_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818403c0)
Location: drivers/i2c/i2c-core-acpi.c:362
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff818403c0-ffffffff818403f0: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81871d90)
Location: drivers/i2c/i2c-core-acpi.c:383
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff81871d90-ffffffff81871dc0: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819463c7)
Location: drivers/i2c/i2c-core-acpi.c:383
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81945ea0-ffffffff81945ed0: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c317)
Location: drivers/i2c/i2c-core-acpi.c:383
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff8194bde0-ffffffff8194be10: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81930257)
Location: drivers/i2c/i2c-core-acpi.c:379
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff8192f940-ffffffff8192f970: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d3527)
Location: drivers/i2c/i2c-core-acpi.c:411
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff819d2be0-ffffffff819d2c10: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35c00)
Location: drivers/i2c/i2c-core-acpi.c:406
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81b35380-ffffffff81b353e5: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccae70)
Location: drivers/i2c/i2c-core-acpi.c:426
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81cca540-ffffffff81cca5a5: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32c10)
Location: drivers/i2c/i2c-core-acpi.c:426
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81d32290-ffffffff81d32313: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8c30)
Location: drivers/i2c/i2c-core-acpi.c:426
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
```
**Symbols:**

```
ffffffff81de8270-ffffffff81de82f3: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
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
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5598)
Location: drivers/i2c/i2c-core-acpi.c:383
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffff800010ab5598-ffff800010ab55ec: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
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
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81865f20)
Location: drivers/i2c/i2c-core-acpi.c:383
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff81865f20-ffffffff81865f50: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct i2c_adapter *i2c_acpi_find_adapter_by_handle(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818811d0)
Location: drivers/i2c/i2c-core-acpi.c:383
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff818811d0-ffffffff81881200: i2c_acpi_find_adapter_by_handle (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
