# Function: <code>acpi_pss_perf_init</code>

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
In drivers/acpi/processor_driver.c (ffffffff814ac139)
Location: drivers/acpi/processor_driver.c:163
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff814fb473)
Location: drivers/acpi/processor_driver.c:164
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff8151e110)
Location: drivers/acpi/processor_driver.c:155
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff8152f32f)
Location: drivers/acpi/processor_driver.c:155
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff8159002f)
Location: drivers/acpi/processor_driver.c:155
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff815c741f)
Location: drivers/acpi/processor_driver.c:155
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff815e09df)
Location: drivers/acpi/processor_driver.c:155
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff81612561)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff81633a11)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_pss_perf_init(struct acpi_processor *pr, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:142
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff816e0690-ffffffff816e0762: acpi_pss_perf_init (STB_LOCAL)
ffffffff816e0c44-ffffffff816e0c9e: acpi_pss_perf_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_pss_perf_init(struct acpi_processor *pr, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:142
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff816fe4b0-ffffffff816fe582: acpi_pss_perf_init (STB_LOCAL)
ffffffff81c029f8-ffffffff81c02a52: acpi_pss_perf_init.cold (STB_LOCAL)
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
In drivers/acpi/processor_driver.c (ffffffff816e03d1)
Location: drivers/acpi/processor_driver.c:138
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff81758631)
Location: drivers/acpi/processor_driver.c:138
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff8188bc0b)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff819d2877)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff81a19e97)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff81a65197)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:203
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff81603561)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff815ee611)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff81627cf1)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
In drivers/acpi/processor_driver.c (ffffffff81641ba1)
Location: drivers/acpi/processor_driver.c:142
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
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
</ul>
