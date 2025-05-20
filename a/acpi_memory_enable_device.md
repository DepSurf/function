# Function: <code>acpi_memory_enable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff814b1247)
Location: drivers/acpi/acpi_memhotplug.c:203
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff81500a5b)
Location: drivers/acpi/acpi_memhotplug.c:203
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff8152385a)
Location: drivers/acpi/acpi_memhotplug.c:203
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff815359d4)
Location: drivers/acpi/acpi_memhotplug.c:203
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff81597284)
Location: drivers/acpi/acpi_memhotplug.c:203
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff815ce722)
Location: drivers/acpi/acpi_memhotplug.c:203
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff815e7e12)
Location: drivers/acpi/acpi_memhotplug.c:203
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
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
In drivers/acpi/acpi_memhotplug.c (ffffffff81619aca)
Location: drivers/acpi/acpi_memhotplug.c:182
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
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
In drivers/acpi/acpi_memhotplug.c (ffffffff8163b4fa)
Location: drivers/acpi/acpi_memhotplug.c:182
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_memory_enable_device(struct acpi_memory_device *mem_device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (0)
Location: drivers/acpi/acpi_memhotplug.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff816e8280-ffffffff816e836d: acpi_memory_enable_device (STB_LOCAL)
ffffffff816e87d7-ffffffff816e87ff: acpi_memory_enable_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_memory_enable_device(struct acpi_memory_device *mem_device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (0)
Location: drivers/acpi/acpi_memhotplug.c:169
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff81705b70-ffffffff81705c5c: acpi_memory_enable_device (STB_LOCAL)
ffffffff81c03090-ffffffff81c030b0: acpi_memory_enable_device.cold (STB_LOCAL)
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
In drivers/acpi/acpi_memhotplug.c (ffffffff816e7510)
Location: drivers/acpi/acpi_memhotplug.c:169
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_memory_enable_device(struct acpi_memory_device *mem_device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (0)
Location: drivers/acpi/acpi_memhotplug.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff81760800-ffffffff81760954: acpi_memory_enable_device (STB_LOCAL)
ffffffff81cf1d32-ffffffff81cf1d74: acpi_memory_enable_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_memory_enable_device(struct acpi_memory_device *mem_device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (0)
Location: drivers/acpi/acpi_memhotplug.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff81894240-ffffffff81894399: acpi_memory_enable_device (STB_LOCAL)
ffffffff81eb9ce6-ffffffff81eb9d21: acpi_memory_enable_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_memory_enable_device(struct acpi_memory_device *mem_device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff819dbd90)
Location: drivers/acpi/acpi_memhotplug.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff819dbd90-ffffffff819dbf1c: acpi_memory_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_memory_enable_device(struct acpi_memory_device *mem_device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff81a23a50)
Location: drivers/acpi/acpi_memhotplug.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff81a23a50-ffffffff81a23bdc: acpi_memory_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_memory_enable_device(struct acpi_memory_device *mem_device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff81a6e810)
Location: drivers/acpi/acpi_memhotplug.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff81a6e810-ffffffff81a6e98c: acpi_memory_enable_device (STB_LOCAL)
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
In drivers/acpi/acpi_memhotplug.c (ffff8000107a6944)
Location: drivers/acpi/acpi_memhotplug.c:182
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (ffffffff8160885a)
Location: drivers/acpi/acpi_memhotplug.c:182
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
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
In drivers/acpi/acpi_memhotplug.c (ffffffff8162f33a)
Location: drivers/acpi/acpi_memhotplug.c:182
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
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
In drivers/acpi/acpi_memhotplug.c (ffffffff8164967a)
Location: drivers/acpi/acpi_memhotplug.c:182
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
