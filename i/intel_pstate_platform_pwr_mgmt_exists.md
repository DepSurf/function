# Function: <code>intel_pstate_platform_pwr_mgmt_exists</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff81fb46f0)
Location: drivers/cpufreq/intel_pstate.c:1321
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
In drivers/cpufreq/intel_pstate.c (ffffffff81fe13ed)
Location: drivers/cpufreq/intel_pstate.c:1714
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
In drivers/cpufreq/intel_pstate.c (ffffffff8201f0fb)
Location: drivers/cpufreq/intel_pstate.c:2433
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
In drivers/cpufreq/intel_pstate.c (ffffffff82101bac)
Location: drivers/cpufreq/intel_pstate.c:2496
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
In drivers/cpufreq/intel_pstate.c (ffffffff8270b274)
Location: drivers/cpufreq/intel_pstate.c:2217
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
In drivers/cpufreq/intel_pstate.c (ffffffff8273552c)
Location: drivers/cpufreq/intel_pstate.c:2462
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
In drivers/cpufreq/intel_pstate.c (ffffffff828ef458)
Location: drivers/cpufreq/intel_pstate.c:2537
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
In drivers/cpufreq/intel_pstate.c (ffffffff8290a97c)
Location: drivers/cpufreq/intel_pstate.c:2573
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
In drivers/cpufreq/intel_pstate.c (ffffffff82914373)
Location: drivers/cpufreq/intel_pstate.c:2679
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
bool intel_pstate_platform_pwr_mgmt_exists();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff82d26e84)
Location: drivers/cpufreq/intel_pstate.c:2695
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff82d26e84-ffffffff82d26fc0: intel_pstate_platform_pwr_mgmt_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool intel_pstate_platform_pwr_mgmt_exists();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8301548f)
Location: drivers/cpufreq/intel_pstate.c:2995
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8301548f-ffffffff830155cb: intel_pstate_platform_pwr_mgmt_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool intel_pstate_platform_pwr_mgmt_exists();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff832203ac)
Location: drivers/cpufreq/intel_pstate.c:2975
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff832203ac-ffffffff832205eb: intel_pstate_platform_pwr_mgmt_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool intel_pstate_platform_pwr_mgmt_exists();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff83309b70)
Location: drivers/cpufreq/intel_pstate.c:3167
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff83309b70-ffffffff83309e03: intel_pstate_platform_pwr_mgmt_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool intel_pstate_platform_pwr_mgmt_exists();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff834c3380)
Location: drivers/cpufreq/intel_pstate.c:3335
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff834c3380-ffffffff834c3606: intel_pstate_platform_pwr_mgmt_exists (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff83f0377d)
Location: drivers/cpufreq/intel_pstate.c:3299
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
In drivers/cpufreq/intel_pstate.c (ffffffff837296ed)
Location: drivers/cpufreq/intel_pstate.c:3325
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
In drivers/cpufreq/intel_pstate.c (ffffffff8395d67d)
Location: drivers/cpufreq/intel_pstate.c:3341
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
In drivers/cpufreq/intel_pstate.c (ffffffff828f9aad)
Location: drivers/cpufreq/intel_pstate.c:2679
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
In drivers/cpufreq/intel_pstate.c (ffffffff828f1c70)
Location: drivers/cpufreq/intel_pstate.c:2679
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
In drivers/cpufreq/intel_pstate.c (ffffffff8290e9bf)
Location: drivers/cpufreq/intel_pstate.c:2679
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
In drivers/cpufreq/intel_pstate.c (ffffffff829153d5)
Location: drivers/cpufreq/intel_pstate.c:2679
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
