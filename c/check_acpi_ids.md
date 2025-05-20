# Function: <code>check_acpi_ids</code>

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
In drivers/xen/xen-acpi-processor.c (ffffffff814d64b7)
Location: drivers/xen/xen-acpi-processor.c:385
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff81527252)
Location: drivers/xen/xen-acpi-processor.c:385
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff815537ae)
Location: drivers/xen/xen-acpi-processor.c:385
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff81568135)
Location: drivers/xen/xen-acpi-processor.c:385
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff815cc2e6)
Location: drivers/xen/xen-acpi-processor.c:385
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff81604b18)
Location: drivers/xen/xen-acpi-processor.c:394
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff8161fbf8)
Location: drivers/xen/xen-acpi-processor.c:400
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff816531cb)
Location: drivers/xen/xen-acpi-processor.c:391
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff81675773)
Location: drivers/xen/xen-acpi-processor.c:391
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81726175)
Location: drivers/xen/xen-acpi-processor.c:391
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81726175-ffffffff81726330: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81c062d2)
Location: drivers/xen/xen-acpi-processor.c:391
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81c062d2-ffffffff81c0648d: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81bf7f64)
Location: drivers/xen/xen-acpi-processor.c:392
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81bf7f64-ffffffff81bf8127: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81cf709c)
Location: drivers/xen/xen-acpi-processor.c:392
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81cf709c-ffffffff81cf725f: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81ebf181)
Location: drivers/xen/xen-acpi-processor.c:392
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81ebf181-ffffffff81ebf35a: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81a33070)
Location: drivers/xen/xen-acpi-processor.c:392
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81a33070-ffffffff81a3326f: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7c960)
Location: drivers/xen/xen-acpi-processor.c:392
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81a7c960-ffffffff81a7cb5f: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_acpi_ids(struct acpi_processor *pr_backup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-acpi-processor.c (ffffffff81acee10)
Location: drivers/xen/xen-acpi-processor.c:392
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81acee10-ffffffff81acf00f: check_acpi_ids (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In drivers/xen/xen-acpi-processor.c (ffffffff8163b463)
Location: drivers/xen/xen-acpi-processor.c:391
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff816695b3)
Location: drivers/xen/xen-acpi-processor.c:391
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In drivers/xen/xen-acpi-processor.c (ffffffff81683b73)
Location: drivers/xen/xen-acpi-processor.c:391
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
