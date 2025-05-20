# Function: <code>acpi_device_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8148143e)
Location: drivers/acpi/scan.c:395
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff8148143e-ffffffff8148183c: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cfe6a)
Location: drivers/acpi/scan.c:396
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff814cfe6a-ffffffff814d0251: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f1dd4)
Location: drivers/acpi/scan.c:397
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff814f1dd4-ffffffff814f21bb: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ff610)
Location: drivers/acpi/scan.c:387
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff814ff610-ffffffff814ffa5f: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815416f0)
Location: drivers/acpi/scan.c:388
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815416f0-ffffffff81541b9b: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815775c0)
Location: drivers/acpi/scan.c:389
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815775c0-ffffffff81577a62: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158f1f0)
Location: drivers/acpi/scan.c:389
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff8158f1f0-ffffffff8158f6a2: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:390
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815c0659-ffffffff815c0743: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff815bff20-ffffffff815c0306: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:390
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815e1919-ffffffff815e1a03: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff815e11e0-ffffffff815e15c6: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:389
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff8168c69c-ffffffff8168c726: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff8168c0f0-ffffffff8168c2b9: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:389
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff81c01248-ffffffff81c012d2: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff816aa160-ffffffff816aa33e: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:386
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff81bf2bc0-ffffffff81bf2c62: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff8168c9f0-ffffffff8168cbbf: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:383
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff81cef597-ffffffff81cef639: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff81702240-ffffffff8170240f: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:384
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff81eb7002-ffffffff81eb70b6: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff8182ff40-ffffffff81830149: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81963060)
Location: drivers/acpi/scan.c:377
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff81963060-ffffffff8196334d: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a9500)
Location: drivers/acpi/scan.c:376
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff819a9500-ffffffff819a97f3: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f2000)
Location: drivers/acpi/scan.c:376
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff819f2000-ffffffff819f22f3: acpi_device_hotplug (STB_GLOBAL)
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
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076da60)
Location: drivers/acpi/scan.c:390
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffff80001076da60-ffff80001076decc: acpi_device_hotplug (STB_GLOBAL)
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
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:390
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815d3be9-ffffffff815d3ccd: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff815d3510-ffffffff815d3899: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:390
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815bd7a9-ffffffff815bd88d: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff815bd0d0-ffffffff815bd459: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:390
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815d5bf9-ffffffff815d5ce3: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff815d54c0-ffffffff815d58a6: acpi_device_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_device_hotplug(struct acpi_device *adev, u32 src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:390
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff815efab9-ffffffff815efba3: acpi_device_hotplug.cold (STB_LOCAL)
ffffffff815ef380-ffffffff815ef766: acpi_device_hotplug (STB_GLOBAL)
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
