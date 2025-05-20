# Function: <code>intel_pstate_has_acpi_ppc</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff81fb47aa)
Location: drivers/cpufreq/intel_pstate.c:1274
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff81fe149c)
Location: drivers/cpufreq/intel_pstate.c:1667
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
In drivers/cpufreq/intel_pstate.c (ffffffff8201f1aa)
Location: drivers/cpufreq/intel_pstate.c:2386
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
In drivers/cpufreq/intel_pstate.c (ffffffff82101c79)
Location: drivers/cpufreq/intel_pstate.c:2449
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
In drivers/cpufreq/intel_pstate.c (ffffffff8270b2e9)
Location: drivers/cpufreq/intel_pstate.c:2177
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2422
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2497
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2532
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2638
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool intel_pstate_has_acpi_ppc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff82d26e07)
Location: drivers/cpufreq/intel_pstate.c:2652
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff82d26e07-ffffffff82d26e84: intel_pstate_has_acpi_ppc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool intel_pstate_has_acpi_ppc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff83015412)
Location: drivers/cpufreq/intel_pstate.c:2952
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff83015412-ffffffff8301548f: intel_pstate_has_acpi_ppc (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2932
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:3124
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:3292
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:3256
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:3282
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:3298
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2638
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2638
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2638
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (0)
Location: drivers/cpufreq/intel_pstate.c:2638
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
