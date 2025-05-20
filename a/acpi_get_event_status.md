# Function: <code>acpi_get_event_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff814931fe)
Location: drivers/acpi/acpica/evxfevnt.c:325
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
**Symbols:**

```
ffffffff814931fe-ffffffff814932bf: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff814e1ffb)
Location: drivers/acpi/acpica/evxfevnt.c:325
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
**Symbols:**

```
ffffffff814e1ffb-ffffffff814e20b8: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff8150493a)
Location: drivers/acpi/acpica/evxfevnt.c:325
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff8150493a-ffffffff815049f7: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff81514ee3)
Location: drivers/acpi/acpica/evxfevnt.c:343
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81514ee3-ffffffff81514f9e: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff8155ec42)
Location: drivers/acpi/acpica/evxfevnt.c:343
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff8155ec42-ffffffff8155edcd: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff81595827)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81595827-ffffffff815959b2: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff815adf35)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff815adf35-ffffffff815ae0bb: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff815df75c)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff815df75c-ffffffff815df8dc: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff81600a9f)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81600a9f-ffffffff81600c1f: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff816acf7d)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff816acf7d-ffffffff816ad0fd: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff816ca8bc)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff816ca8bc-ffffffff816caa3c: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff816ac89d)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff816ac89d-ffffffff816aca1c: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff817235d4)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff817235d4-ffffffff8172378f: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff81853c4f)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81853c4f-ffffffff81853e27: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff8198e3b0)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff8198e3b0-ffffffff8198e5d3: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff819d4e40)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff819d4e40-ffffffff819d5063: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff81a1fad0)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sysfs.c:get_status
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81a1fad0-ffffffff81a1fcf3: acpi_get_event_status (STB_GLOBAL)
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
In drivers/acpi/sysfs.c (0)
Location: include/acpi/acpixf.h:695
Inline: True
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff815e8c6d)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff815e8c6d-ffffffff815e8d22: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff815d4295)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff815d4295-ffffffff815d434a: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff815f4d7f)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff815f4d7f-ffffffff815f4eff: acpi_get_event_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status *event_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfevnt.c (ffffffff8160ec2f)
Location: drivers/acpi/acpica/evxfevnt.c:309
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff8160ec2f-ffffffff8160edaf: acpi_get_event_status (STB_GLOBAL)
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
