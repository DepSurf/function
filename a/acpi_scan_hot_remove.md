# Function: <code>acpi_scan_hot_remove</code>

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
In drivers/acpi/scan.c (ffffffff814815b6)
Location: drivers/acpi/scan.c:258
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff814cffda)
Location: drivers/acpi/scan.c:259
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff814f1f44)
Location: drivers/acpi/scan.c:260
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff814ff786)
Location: drivers/acpi/scan.c:251
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff81541868)
Location: drivers/acpi/scan.c:252
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff8157778b)
Location: drivers/acpi/scan.c:253
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff8158f3c2)
Location: drivers/acpi/scan.c:253
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff815c007a)
Location: drivers/acpi/scan.c:254
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff815e133a)
Location: drivers/acpi/scan.c:254
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168ad40)
Location: drivers/acpi/scan.c:253
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff8168ad40-ffffffff8168aec9: acpi_scan_hot_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a8a80)
Location: drivers/acpi/scan.c:253
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff816a8a80-ffffffff816a8c09: acpi_scan_hot_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:251
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff8168b200-ffffffff8168b3dd: acpi_scan_hot_remove (STB_LOCAL)
ffffffff81bf2a29-ffffffff81bf2a9f: acpi_scan_hot_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:248
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff81700cb0-ffffffff81700e8a: acpi_scan_hot_remove (STB_LOCAL)
ffffffff81cef463-ffffffff81cef4d9: acpi_scan_hot_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:249
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff8182e950-ffffffff8182eb3a: acpi_scan_hot_remove (STB_LOCAL)
ffffffff81eb6ec1-ffffffff81eb6f32: acpi_scan_hot_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81961450)
Location: drivers/acpi/scan.c:248
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff81961450-ffffffff819616af: acpi_scan_hot_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a7860)
Location: drivers/acpi/scan.c:247
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff819a7860-ffffffff819a7abf: acpi_scan_hot_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_scan_hot_remove(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f0250)
Location: drivers/acpi/scan.c:247
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff819f0250-ffffffff819f04af: acpi_scan_hot_remove (STB_LOCAL)
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
In drivers/acpi/scan.c (ffff80001076dbd8)
Location: drivers/acpi/scan.c:254
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff815d3689)
Location: drivers/acpi/scan.c:254
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bd249)
Location: drivers/acpi/scan.c:254
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d561a)
Location: drivers/acpi/scan.c:254
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff815ef4da)
Location: drivers/acpi/scan.c:254
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
