# Function: <code>acpi_processor_check_duplicates</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff8200b04e)
Location: drivers/acpi/acpi_processor.c:653
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_processor_check_duplicates();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff820ec865)
Location: drivers/acpi/acpi_processor.c:673
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
```
**Symbols:**

```
ffffffff820ec865-ffffffff820ec8a8: acpi_processor_check_duplicates (STB_GLOBAL)
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
In drivers/acpi/acpi_processor.c (ffffffff826f5752)
Location: drivers/acpi/acpi_processor.c:674
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff8271f732)
Location: drivers/acpi/acpi_processor.c:674
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff828d76c8)
Location: drivers/acpi/acpi_processor.c:675
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff828f1545)
Location: drivers/acpi/acpi_processor.c:672
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff828fa6b4)
Location: drivers/acpi/acpi_processor.c:676
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff82d1169a)
Location: drivers/acpi/acpi_processor.c:676
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff82fff16d)
Location: drivers/acpi/acpi_processor.c:675
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff8320a1c5)
Location: drivers/acpi/acpi_processor.c:658
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff832f25f8)
Location: drivers/acpi/acpi_processor.c:658
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff834aa5aa)
Location: drivers/acpi/acpi_processor.c:658
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff83ee24e5)
Location: drivers/acpi/acpi_processor.c:658
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff83707eca)
Location: drivers/acpi/acpi_processor.c:695
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff8393b3ba)
Location: drivers/acpi/acpi_processor.c:738
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffff80001147d5b0)
Location: drivers/acpi/acpi_processor.c:676
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff828e3380)
Location: drivers/acpi/acpi_processor.c:676
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff828db3ef)
Location: drivers/acpi/acpi_processor.c:676
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff828f62b0)
Location: drivers/acpi/acpi_processor.c:676
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
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
In drivers/acpi/acpi_processor.c (ffffffff828fb708)
Location: drivers/acpi/acpi_processor.c:676
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
