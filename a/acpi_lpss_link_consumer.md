# Function: <code>acpi_lpss_link_consumer</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81580e57)
Location: drivers/acpi/acpi_lpss.c:527
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
In drivers/acpi/acpi_lpss.c (ffffffff81598a4b)
Location: drivers/acpi/acpi_lpss.c:565
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
In drivers/acpi/acpi_lpss.c (ffffffff815ca25b)
Location: drivers/acpi/acpi_lpss.c:562
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
In drivers/acpi/acpi_lpss.c (ffffffff815eb36c)
Location: drivers/acpi/acpi_lpss.c:585
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_lpss_link_consumer(struct device *dev1, const struct lpss_device_links *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81696960)
Location: drivers/acpi/acpi_lpss.c:563
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff81696960-ffffffff81696aa5: acpi_lpss_link_consumer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_lpss_link_consumer(struct device *dev1, const struct lpss_device_links *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b3c90)
Location: drivers/acpi/acpi_lpss.c:570
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff816b3c90-ffffffff816b3dd5: acpi_lpss_link_consumer (STB_LOCAL)
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
In drivers/acpi/acpi_lpss.c (ffffffff81695e45)
Location: drivers/acpi/acpi_lpss.c:571
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
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
In drivers/acpi/acpi_lpss.c (ffffffff8170bbc8)
Location: drivers/acpi/acpi_lpss.c:572
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
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
In drivers/acpi/acpi_lpss.c (ffffffff8183a1d7)
Location: drivers/acpi/acpi_lpss.c:594
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
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
In drivers/acpi/acpi_lpss.c (ffffffff8196f877)
Location: drivers/acpi/acpi_lpss.c:586
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
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
In drivers/acpi/acpi_lpss.c (ffffffff819b5e27)
Location: drivers/acpi/acpi_lpss.c:601
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
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
In drivers/acpi/acpi_lpss.c (ffffffff81a004a5)
Location: drivers/acpi/acpi_lpss.c:566
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c5d8c)
Location: drivers/acpi/acpi_lpss.c:585
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
In drivers/acpi/acpi_lpss.c (ffffffff815df64c)
Location: drivers/acpi/acpi_lpss.c:585
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
In drivers/acpi/acpi_lpss.c (ffffffff815f950c)
Location: drivers/acpi/acpi_lpss.c:585
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
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
