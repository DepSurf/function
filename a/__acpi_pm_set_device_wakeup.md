# Function: <code>__acpi_pm_set_device_wakeup</code>

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
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153b980)
Location: drivers/acpi/device_pm.c:782
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff8153b980-ffffffff8153ba97: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815717c0)
Location: drivers/acpi/device_pm.c:782
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815717c0-ffffffff815718ef: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81589590)
Location: drivers/acpi/device_pm.c:783
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff81589590-ffffffff815896bf: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ba0d0)
Location: drivers/acpi/device_pm.c:827
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815ba0d0-ffffffff815ba1ff: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815db310)
Location: drivers/acpi/device_pm.c:832
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815db310-ffffffff815db43f: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81685c40)
Location: drivers/acpi/device_pm.c:832
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff81685c40-ffffffff81685dac: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010767fb0)
Location: drivers/acpi/device_pm.c:832
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffff800010767fb0-ffff8000107680ec: __acpi_pm_set_device_wakeup (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cdae0)
Location: drivers/acpi/device_pm.c:832
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815cdae0-ffffffff815cdc0f: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7660)
Location: drivers/acpi/device_pm.c:832
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815b7660-ffffffff815b778f: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cf5f0)
Location: drivers/acpi/device_pm.c:832
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815cf5f0-ffffffff815cf71f: __acpi_pm_set_device_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __acpi_pm_set_device_wakeup(struct device *dev, bool enable, int max_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e94b0)
Location: drivers/acpi/device_pm.c:832
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_set_bridge_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
```
**Symbols:**

```
ffffffff815e94b0-ffffffff815e95df: __acpi_pm_set_device_wakeup (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
