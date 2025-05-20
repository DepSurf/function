# Function: <code>acpi_serdev_add_device</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81609c90)
Location: drivers/tty/serdev/core.c:450
Inline: False
```
**Symbols:**

```
ffffffff81609c90-ffffffff81609d99: acpi_serdev_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816434b0)
Location: drivers/tty/serdev/core.c:493
Inline: False
```
**Symbols:**

```
ffffffff816434b0-ffffffff816435b6: acpi_serdev_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816617f0)
Location: drivers/tty/serdev/core.c:585
Inline: False
```
**Symbols:**

```
ffffffff816617f0-ffffffff816618f6: acpi_serdev_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:585
Inline: False
```
**Symbols:**

```
ffffffff81697320-ffffffff816973e6: acpi_serdev_add_device (STB_LOCAL)
ffffffff81697484-ffffffff816974d2: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:591
Inline: False
```
**Symbols:**

```
ffffffff816b9ed0-ffffffff816b9fb2: acpi_serdev_add_device (STB_LOCAL)
ffffffff816ba021-ffffffff816ba06f: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:684
Inline: False
```
**Symbols:**

```
ffffffff8176e2d0-ffffffff8176e39b: acpi_serdev_add_device (STB_LOCAL)
ffffffff8176e474-ffffffff8176e4c3: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:684
Inline: False
```
**Symbols:**

```
ffffffff81788ca0-ffffffff81788d71: acpi_serdev_add_device (STB_LOCAL)
ffffffff81c08472-ffffffff81c084c1: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:684
Inline: False
```
**Symbols:**

```
ffffffff8176c490-ffffffff8176c666: acpi_serdev_add_device (STB_LOCAL)
ffffffff81bfa037-ffffffff81bfa086: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:704
Inline: False
```
**Symbols:**

```
ffffffff817f1bd0-ffffffff817f1db5: acpi_serdev_add_device (STB_LOCAL)
ffffffff81cfa8e7-ffffffff81cfa94b: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:704
Inline: False
```
**Symbols:**

```
ffffffff81932320-ffffffff819324ea: acpi_serdev_add_device (STB_LOCAL)
ffffffff81ec2b66-ffffffff81ec2bc8: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:704
Inline: False
```
**Symbols:**

```
ffffffff81a90e00-ffffffff81a9100b: acpi_serdev_add_device (STB_LOCAL)
ffffffff8209648b-ffffffff820964a0: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:715
Inline: False
```
**Symbols:**

```
ffffffff81adc610-ffffffff81adc81a: acpi_serdev_add_device (STB_LOCAL)
ffffffff821173d3-ffffffff821173e8: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:708
Inline: False
```
**Symbols:**

```
ffffffff81b2f930-ffffffff81b2fb18: acpi_serdev_add_device (STB_LOCAL)
ffffffff821f5138-ffffffff821f514d: acpi_serdev_add_device.cold (STB_LOCAL)
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
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a9878)
Location: drivers/tty/serdev/core.c:591
Inline: False
```
**Symbols:**

```
ffff8000108a9878-ffff8000108a99bc: acpi_serdev_add_device (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:591
Inline: False
```
**Symbols:**

```
ffffffff8167f930-ffffffff8167fa12: acpi_serdev_add_device (STB_LOCAL)
ffffffff8167fa81-ffffffff8167facf: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:591
Inline: False
```
**Symbols:**

```
ffffffff816add10-ffffffff816addf2: acpi_serdev_add_device (STB_LOCAL)
ffffffff816ade61-ffffffff816adeaf: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_serdev_add_device(acpi_handle handle, u32 level, void *data, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:591
Inline: False
```
**Symbols:**

```
ffffffff816c8170-ffffffff816c8252: acpi_serdev_add_device (STB_LOCAL)
ffffffff816c82c1-ffffffff816c830f: acpi_serdev_add_device.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
