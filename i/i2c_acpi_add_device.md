# Function: <code>i2c_acpi_add_device</code>

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
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170d960)
Location: drivers/i2c/i2c-core.c:244
Inline: False
```
**Symbols:**

```
ffffffff8170d960-ffffffff8170d9d2: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724470)
Location: drivers/i2c/i2c-core-acpi.c:190
Inline: False
```
**Symbols:**

```
ffffffff81724470-ffffffff817244e2: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817957d0)
Location: drivers/i2c/i2c-core-acpi.c:190
Inline: False
```
**Symbols:**

```
ffffffff817957d0-ffffffff81795842: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8290)
Location: drivers/i2c/i2c-core-acpi.c:190
Inline: False
```
**Symbols:**

```
ffffffff817d8290-ffffffff817d8302: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff550)
Location: drivers/i2c/i2c-core-acpi.c:213
Inline: False
```
**Symbols:**

```
ffffffff817ff550-ffffffff817ff5c2: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:235
Inline: False
```
**Symbols:**

```
ffffffff81840890-ffffffff8184091d: i2c_acpi_add_device (STB_LOCAL)
ffffffff8184114c-ffffffff81841181: i2c_acpi_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:236
Inline: False
```
**Symbols:**

```
ffffffff818721f0-ffffffff8187227d: i2c_acpi_add_device (STB_LOCAL)
ffffffff81872ac5-ffffffff81872afa: i2c_acpi_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:236
Inline: False
```
**Symbols:**

```
ffffffff81946280-ffffffff81946310: i2c_acpi_add_device (STB_LOCAL)
ffffffff81946c7c-ffffffff81946c8c: i2c_acpi_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:236
Inline: False
```
**Symbols:**

```
ffffffff8194c1c0-ffffffff8194c253: i2c_acpi_add_device (STB_LOCAL)
ffffffff81c24e28-ffffffff81c24e38: i2c_acpi_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8192fb70)
Location: drivers/i2c/i2c-core-acpi.c:232
Inline: False
```
**Symbols:**

```
ffffffff8192fb70-ffffffff8192fc03: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d2e40)
Location: drivers/i2c/i2c-core-acpi.c:264
Inline: False
```
**Symbols:**

```
ffffffff819d2e40-ffffffff819d2ed3: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35430)
Location: drivers/i2c/i2c-core-acpi.c:275
Inline: False
```
**Symbols:**

```
ffffffff81b35430-ffffffff81b354e7: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cca610)
Location: drivers/i2c/i2c-core-acpi.c:295
Inline: False
```
**Symbols:**

```
ffffffff81cca610-ffffffff81cca6c4: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32380)
Location: drivers/i2c/i2c-core-acpi.c:295
Inline: False
```
**Symbols:**

```
ffffffff81d32380-ffffffff81d32434: i2c_acpi_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8360)
Location: drivers/i2c/i2c-core-acpi.c:295
Inline: False
```
**Symbols:**

```
ffffffff81de8360-ffffffff81de8414: i2c_acpi_add_device (STB_LOCAL)
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
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5b08)
Location: drivers/i2c/i2c-core-acpi.c:236
Inline: False
```
**Symbols:**

```
ffff800010ab5b08-ffff800010ab5be8: i2c_acpi_add_device (STB_LOCAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:236
Inline: False
```
**Symbols:**

```
ffffffff81866380-ffffffff8186640d: i2c_acpi_add_device (STB_LOCAL)
ffffffff81866c55-ffffffff81866c8a: i2c_acpi_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:236
Inline: False
```
**Symbols:**

```
ffffffff81881630-ffffffff818816bd: i2c_acpi_add_device (STB_LOCAL)
ffffffff81881f05-ffffffff81881f3a: i2c_acpi_add_device.cold (STB_LOCAL)
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
