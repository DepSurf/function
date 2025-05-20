# Function: <code>processor_physically_present</code>

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
In drivers/acpi/processor_pdc.c (ffffffff81fa1fc7)
Location: drivers/acpi/processor_pdc.c:21
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff81fcdfdf)
Location: drivers/acpi/processor_pdc.c:21
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff8200b265)
Location: drivers/acpi/processor_pdc.c:21
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff820ec98b)
Location: drivers/acpi/processor_pdc.c:21
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff826f5862)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff8271f86a)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff828d7800)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff828f167a)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff828fa7e9)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool processor_physically_present(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_pdc.c (ffffffff82d117a7)
Location: drivers/acpi/processor_pdc.c:22
Inline: False
Direct callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
```
**Symbols:**

```
ffffffff82d117a7-ffffffff82d1186e: processor_physically_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool processor_physically_present(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_pdc.c (ffffffff82fff27a)
Location: drivers/acpi/processor_pdc.c:22
Inline: False
Direct callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
```
**Symbols:**

```
ffffffff82fff27a-ffffffff82fff341: processor_physically_present (STB_LOCAL)
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
In drivers/acpi/processor_pdc.c (ffffffff8320a300)
Location: drivers/acpi/processor_pdc.c:19
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff832f2733)
Location: drivers/acpi/processor_pdc.c:19
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff834aa704)
Location: drivers/acpi/processor_pdc.c:19
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff83ee2674)
Location: drivers/acpi/processor_pdc.c:19
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff83708094)
Location: drivers/acpi/processor_pdc.c:21
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool processor_physically_present(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff8393b050)
Location: drivers/acpi/acpi_processor.c:499
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_osc
  - drivers/acpi/processor_pdc.c:early_init_pdc
```
**Symbols:**

```
ffffffff8393b050-ffffffff8393b15d: processor_physically_present (STB_GLOBAL)
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
In drivers/acpi/processor_pdc.c (ffffffff828e34b5)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff828db524)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff828f63e5)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
In drivers/acpi/processor_pdc.c (ffffffff828fb83d)
Location: drivers/acpi/processor_pdc.c:22
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:early_init_pdc
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
