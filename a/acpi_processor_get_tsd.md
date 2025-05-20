# Function: <code>acpi_processor_get_tsd</code>

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
In drivers/acpi/processor_throttling.c (ffffffff814ae45b)
Location: drivers/acpi/processor_throttling.c:582
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff814fde1a)
Location: drivers/acpi/processor_throttling.c:582
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff81520b13)
Location: drivers/acpi/processor_throttling.c:582
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff81531f4f)
Location: drivers/acpi/processor_throttling.c:582
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff815935ed)
Location: drivers/acpi/processor_throttling.c:582
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff815ca930)
Location: drivers/acpi/processor_throttling.c:583
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff815e3f10)
Location: drivers/acpi/processor_throttling.c:583
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff81615abb)
Location: drivers/acpi/processor_throttling.c:570
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff81636fab)
Location: drivers/acpi/processor_throttling.c:570
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_tsd(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:570
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
**Symbols:**

```
ffffffff816e38c0-ffffffff816e3a3a: acpi_processor_get_tsd (STB_LOCAL)
ffffffff816e42c0-ffffffff816e4305: acpi_processor_get_tsd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_tsd(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:569
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
**Symbols:**

```
ffffffff81701520-ffffffff8170169a: acpi_processor_get_tsd (STB_LOCAL)
ffffffff81c02c4b-ffffffff81c02c90: acpi_processor_get_tsd.cold (STB_LOCAL)
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
In drivers/acpi/processor_throttling.c (ffffffff816e33d3)
Location: drivers/acpi/processor_throttling.c:566
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff8175be48)
Location: drivers/acpi/processor_throttling.c:560
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_tsd(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:560
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
**Symbols:**

```
ffffffff8188e530-ffffffff8188e6a5: acpi_processor_get_tsd (STB_LOCAL)
ffffffff81eb9575-ffffffff81eb95a7: acpi_processor_get_tsd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_get_tsd(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff819d5a60)
Location: drivers/acpi/processor_throttling.c:558
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
**Symbols:**

```
ffffffff819d5a60-ffffffff819d5bfa: acpi_processor_get_tsd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_get_tsd(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a1d3b0)
Location: drivers/acpi/processor_throttling.c:558
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
**Symbols:**

```
ffffffff81a1d3b0-ffffffff81a1d54a: acpi_processor_get_tsd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_get_tsd(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a686c0)
Location: drivers/acpi/processor_throttling.c:558
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
**Symbols:**

```
ffffffff81a686c0-ffffffff81a6885a: acpi_processor_get_tsd (STB_LOCAL)
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
In drivers/acpi/processor_throttling.c (ffffffff816063d9)
Location: drivers/acpi/processor_throttling.c:570
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff815f14a9)
Location: drivers/acpi/processor_throttling.c:570
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff8162b28b)
Location: drivers/acpi/processor_throttling.c:570
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
In drivers/acpi/processor_throttling.c (ffffffff8164512b)
Location: drivers/acpi/processor_throttling.c:570
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
