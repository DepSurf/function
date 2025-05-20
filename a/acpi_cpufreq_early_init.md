# Function: <code>acpi_cpufreq_early_init</code>

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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81fb3e5f)
Location: drivers/cpufreq/acpi-cpufreq.c:578
Inline: True
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81fe0984)
Location: drivers/cpufreq/acpi-cpufreq.c:587
Inline: True
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8201e5ee)
Location: drivers/cpufreq/acpi-cpufreq.c:568
Inline: True
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82101197)
Location: drivers/cpufreq/acpi-cpufreq.c:568
Inline: True
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8270a895)
Location: drivers/cpufreq/acpi-cpufreq.c:568
Inline: True
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82734a7b)
Location: drivers/cpufreq/acpi-cpufreq.c:568
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828ee942)
Location: drivers/cpufreq/acpi-cpufreq.c:573
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82909dda)
Location: drivers/cpufreq/acpi-cpufreq.c:555
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff829137d1)
Location: drivers/cpufreq/acpi-cpufreq.c:555
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_cpufreq_early_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82d26326)
Location: drivers/cpufreq/acpi-cpufreq.c:558
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff82d26326-ffffffff82d26405: acpi_cpufreq_early_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_cpufreq_early_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83014930)
Location: drivers/cpufreq/acpi-cpufreq.c:559
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff83014930-ffffffff83014a0f: acpi_cpufreq_early_init (STB_LOCAL)
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8321fa26)
Location: drivers/cpufreq/acpi-cpufreq.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff833091d8)
Location: drivers/cpufreq/acpi-cpufreq.c:559
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff834c2859)
Location: drivers/cpufreq/acpi-cpufreq.c:560
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_cpufreq_early_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83f02410)
Location: drivers/cpufreq/acpi-cpufreq.c:556
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff83f02410-ffffffff83f0256b: acpi_cpufreq_early_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_cpufreq_early_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83728300)
Location: drivers/cpufreq/acpi-cpufreq.c:557
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
```
**Symbols:**

```
ffffffff83728300-ffffffff8372845b: acpi_cpufreq_early_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_cpufreq_early_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8395c290)
Location: drivers/cpufreq/acpi-cpufreq.c:557
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_probe
```
**Symbols:**

```
ffffffff8395c290-ffffffff8395c3eb: acpi_cpufreq_early_init (STB_LOCAL)
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828f95e5)
Location: drivers/cpufreq/acpi-cpufreq.c:555
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828f10ce)
Location: drivers/cpufreq/acpi-cpufreq.c:555
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8290de1d)
Location: drivers/cpufreq/acpi-cpufreq.c:555
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82914833)
Location: drivers/cpufreq/acpi-cpufreq.c:555
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
