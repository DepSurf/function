# Function: <code>acpi_lpss_d3_to_d0_delay</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814d63e4)
Location: drivers/acpi/acpi_lpss.c:618
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
```
**Symbols:**

```
ffffffff814d63e4-ffffffff814d6401: acpi_lpss_d3_to_d0_delay.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff814f8a44)
Location: drivers/acpi/acpi_lpss.c:629
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
```
**Symbols:**

```
ffffffff814f8a44-ffffffff814f8a61: acpi_lpss_d3_to_d0_delay.isra.5 (STB_LOCAL)
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
In drivers/acpi/acpi_lpss.c (ffffffff81507e56)
Location: drivers/acpi/acpi_lpss.c:674
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff8154a253)
Location: drivers/acpi/acpi_lpss.c:675
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff81580466)
Location: drivers/acpi/acpi_lpss.c:821
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff81598376)
Location: drivers/acpi/acpi_lpss.c:854
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff815c9504)
Location: drivers/acpi/acpi_lpss.c:851
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff815ea724)
Location: drivers/acpi/acpi_lpss.c:876
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff816965cc)
Location: drivers/acpi/acpi_lpss.c:854
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff816b371c)
Location: drivers/acpi/acpi_lpss.c:861
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff8169599c)
Location: drivers/acpi/acpi_lpss.c:862
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff8170b6cc)
Location: drivers/acpi/acpi_lpss.c:863
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff81839c4f)
Location: drivers/acpi/acpi_lpss.c:885
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff8196f26f)
Location: drivers/acpi/acpi_lpss.c:874
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff819b57fb)
Location: drivers/acpi/acpi_lpss.c:889
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff819ffbfb)
Location: drivers/acpi/acpi_lpss.c:853
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff815c5194)
Location: drivers/acpi/acpi_lpss.c:876
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff815dea04)
Location: drivers/acpi/acpi_lpss.c:876
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
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
In drivers/acpi/acpi_lpss.c (ffffffff815f88c4)
Location: drivers/acpi/acpi_lpss.c:876
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
```
</details>
</li>
</ul>

## Differences
