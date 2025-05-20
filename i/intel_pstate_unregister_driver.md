# Function: <code>intel_pstate_unregister_driver</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c440)
Location: drivers/cpufreq/intel_pstate.c:2310
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff8176c440-ffffffff8176c4fc: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2290)
Location: drivers/cpufreq/intel_pstate.c:2062
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff817e2290-ffffffff817e22c1: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b070)
Location: drivers/cpufreq/intel_pstate.c:2295
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff8182b070-ffffffff8182b0a1: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81856fe0)
Location: drivers/cpufreq/intel_pstate.c:2370
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff81856fe0-ffffffff81857011: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8189a730)
Location: drivers/cpufreq/intel_pstate.c:2399
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff8189a730-ffffffff8189a767: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818cc8e0)
Location: drivers/cpufreq/intel_pstate.c:2505
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff818cc8e0-ffffffff818cc917: intel_pstate_unregister_driver (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff8199f355)
Location: drivers/cpufreq/intel_pstate.c:2513
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818704e0)
Location: drivers/cpufreq/intel_pstate.c:2505
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff818704e0-ffffffff81870517: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81839a60)
Location: drivers/cpufreq/intel_pstate.c:2505
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff81839a60-ffffffff81839a97: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1d90)
Location: drivers/cpufreq/intel_pstate.c:2505
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff818c1d90-ffffffff818c1dc7: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int intel_pstate_unregister_driver();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff818de0a0)
Location: drivers/cpufreq/intel_pstate.c:2505
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
  - drivers/cpufreq/intel_pstate.c:store_status
```
**Symbols:**

```
ffffffff818de0a0-ffffffff818de0d7: intel_pstate_unregister_driver (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
