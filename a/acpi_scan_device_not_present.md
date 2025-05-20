# Function: <code>acpi_scan_device_not_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147fbdd)
Location: drivers/acpi/scan.c:305
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/scan.c:acpi_device_hotplug
```
**Symbols:**

```
ffffffff8147fbdd-ffffffff8147fc18: acpi_scan_device_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ce46b)
Location: drivers/acpi/scan.c:306
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff814ce46b-ffffffff814ce4a6: acpi_scan_device_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f033f)
Location: drivers/acpi/scan.c:307
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff814f033f-ffffffff814f037a: acpi_scan_device_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fd3e0)
Location: drivers/acpi/scan.c:297
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff814fd3e0-ffffffff814fd41c: acpi_scan_device_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8153f120)
Location: drivers/acpi/scan.c:298
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff8153f120-ffffffff8153f15c: acpi_scan_device_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81575070)
Location: drivers/acpi/scan.c:299
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff81575070-ffffffff815750ac: acpi_scan_device_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158ce70)
Location: drivers/acpi/scan.c:299
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff8158ce70-ffffffff8158ceac: acpi_scan_device_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:300
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff815bdc30-ffffffff815bdc5a: acpi_scan_device_not_present (STB_LOCAL)
ffffffff815c04e9-ffffffff815c0506: acpi_scan_device_not_present.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:300
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff815deef0-ffffffff815def1a: acpi_scan_device_not_present (STB_LOCAL)
ffffffff815e17a9-ffffffff815e17c6: acpi_scan_device_not_present.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168c295)
Location: drivers/acpi/scan.c:299
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816aa314)
Location: drivers/acpi/scan.c:299
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
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
In drivers/acpi/scan.c (ffffffff8168cb9a)
Location: drivers/acpi/scan.c:296
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
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
In drivers/acpi/scan.c (ffffffff817023ea)
Location: drivers/acpi/scan.c:293
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
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
In drivers/acpi/scan.c (ffffffff8183010f)
Location: drivers/acpi/scan.c:294
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
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
In drivers/acpi/scan.c (ffffffff8196327d)
Location: drivers/acpi/scan.c:293
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/scan.c (ffffffff819a9724)
Location: drivers/acpi/scan.c:292
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
</details>
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
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076b520)
Location: drivers/acpi/scan.c:300
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffff80001076b520-ffff80001076b57c: acpi_scan_device_not_present (STB_LOCAL)
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
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:300
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff815d13d0-ffffffff815d13fa: acpi_scan_device_not_present (STB_LOCAL)
ffffffff815d3a79-ffffffff815d3a96: acpi_scan_device_not_present.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:300
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff815baf90-ffffffff815bafba: acpi_scan_device_not_present (STB_LOCAL)
ffffffff815bd639-ffffffff815bd656: acpi_scan_device_not_present.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:300
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff815d31d0-ffffffff815d31fa: acpi_scan_device_not_present (STB_LOCAL)
ffffffff815d5a89-ffffffff815d5aa6: acpi_scan_device_not_present.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_scan_device_not_present(struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:300
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
**Symbols:**

```
ffffffff815ed090-ffffffff815ed0ba: acpi_scan_device_not_present (STB_LOCAL)
ffffffff815ef949-ffffffff815ef966: acpi_scan_device_not_present.cold (STB_LOCAL)
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
