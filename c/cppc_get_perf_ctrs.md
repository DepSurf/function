# Function: <code>cppc_get_perf_ctrs</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81525fbf)
Location: drivers/acpi/cppc_acpi.c:1028
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
```
**Symbols:**

```
ffffffff81525fbf-ffffffff81526214: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81538e00)
Location: drivers/acpi/cppc_acpi.c:1036
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff81538e00-ffffffff81539087: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8159a6d0)
Location: drivers/acpi/cppc_acpi.c:1093
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff8159a6d0-ffffffff8159a9af: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815d2260)
Location: drivers/acpi/cppc_acpi.c:1141
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff815d2260-ffffffff815d256e: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815eba10)
Location: drivers/acpi/cppc_acpi.c:1192
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff815eba10-ffffffff815ebd1e: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8161d7d0)
Location: drivers/acpi/cppc_acpi.c:1188
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff8161d7d0-ffffffff8161dad7: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8163f280)
Location: drivers/acpi/cppc_acpi.c:1190
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff8163f280-ffffffff8163f587: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816ebb30)
Location: drivers/acpi/cppc_acpi.c:1172
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff816ebb30-ffffffff816ebe4a: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81709190)
Location: drivers/acpi/cppc_acpi.c:1158
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff81709190-ffffffff817094aa: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816ea7b0)
Location: drivers/acpi/cppc_acpi.c:1150
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff816ea7b0-ffffffff816eaac3: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff817645e0)
Location: drivers/acpi/cppc_acpi.c:1172
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff817645e0-ffffffff81764963: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81898730)
Location: drivers/acpi/cppc_acpi.c:1250
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff81898730-ffffffff81898ae1: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff819e0a80)
Location: drivers/acpi/cppc_acpi.c:1295
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff819e0a80-ffffffff819e0e31: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a28a40)
Location: drivers/acpi/cppc_acpi.c:1309
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff81a28a40-ffffffff81a28df1: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a73c10)
Location: drivers/acpi/cppc_acpi.c:1312
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff81a73c10-ffffffff81a73fc1: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107aa3a8)
Location: drivers/acpi/cppc_acpi.c:1190
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffff8000107aa3a8-ffff8000107aa6c0: cppc_get_perf_ctrs (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8160acb0)
Location: drivers/acpi/cppc_acpi.c:1190
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff8160acb0-ffffffff8160afb7: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815fc8f0)
Location: drivers/acpi/cppc_acpi.c:1190
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff815fc8f0-ffffffff815fcbf7: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816330c0)
Location: drivers/acpi/cppc_acpi.c:1190
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff816330c0-ffffffff816333c7: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cppc_get_perf_ctrs(int cpunum, struct cppc_perf_fb_ctrs *perf_fb_ctrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8164d3f0)
Location: drivers/acpi/cppc_acpi.c:1190
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:show_feedback_ctrs
  - drivers/acpi/cppc_acpi.c:show_wraparound_time
  - drivers/acpi/cppc_acpi.c:show_reference_perf
```
**Symbols:**

```
ffffffff8164d3f0-ffffffff8164d6f7: cppc_get_perf_ctrs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
