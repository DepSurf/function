# Function: <code>intel_pstate_sysfs_expose_params</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff81fb49f2)
Location: drivers/cpufreq/intel_pstate.c:513
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
In drivers/cpufreq/intel_pstate.c (ffffffff81fe15fe)
Location: drivers/cpufreq/intel_pstate.c:793
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
In drivers/cpufreq/intel_pstate.c (ffffffff8201f328)
Location: drivers/cpufreq/intel_pstate.c:1196
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
In drivers/cpufreq/intel_pstate.c (ffffffff82101dde)
Location: drivers/cpufreq/intel_pstate.c:1226
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
In drivers/cpufreq/intel_pstate.c (ffffffff8270b42e)
Location: drivers/cpufreq/intel_pstate.c:1041
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
In drivers/cpufreq/intel_pstate.c (ffffffff8273570c)
Location: drivers/cpufreq/intel_pstate.c:1097
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
In drivers/cpufreq/intel_pstate.c (ffffffff828ef638)
Location: drivers/cpufreq/intel_pstate.c:1160
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
In drivers/cpufreq/intel_pstate.c (ffffffff8290abc3)
Location: drivers/cpufreq/intel_pstate.c:1197
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
In drivers/cpufreq/intel_pstate.c (ffffffff829145ba)
Location: drivers/cpufreq/intel_pstate.c:1243
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
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff82d26fc0)
Location: drivers/cpufreq/intel_pstate.c:1250
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff82d26fc0-ffffffff82d2705c: intel_pstate_sysfs_expose_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff830155cb)
Location: drivers/cpufreq/intel_pstate.c:1381
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff830155cb-ffffffff8301567e: intel_pstate_sysfs_expose_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff832205eb)
Location: drivers/cpufreq/intel_pstate.c:1381
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff832205eb-ffffffff8322069e: intel_pstate_sysfs_expose_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff83309f0d)
Location: drivers/cpufreq/intel_pstate.c:1479
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff83309f0d-ffffffff8330a01e: intel_pstate_sysfs_expose_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff834c371e)
Location: drivers/cpufreq/intel_pstate.c:1513
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff834c371e-ffffffff834c383b: intel_pstate_sysfs_expose_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff83f03370)
Location: drivers/cpufreq/intel_pstate.c:1488
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff83f03370-ffffffff83f034d1: intel_pstate_sysfs_expose_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff837293f0)
Location: drivers/cpufreq/intel_pstate.c:1508
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff837293f0-ffffffff8372956d: intel_pstate_sysfs_expose_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pstate_sysfs_expose_params();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8395d380)
Location: drivers/cpufreq/intel_pstate.c:1532
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8395d380-ffffffff8395d4fd: intel_pstate_sysfs_expose_params (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff828f9cf4)
Location: drivers/cpufreq/intel_pstate.c:1243
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
In drivers/cpufreq/intel_pstate.c (ffffffff828f1ed3)
Location: drivers/cpufreq/intel_pstate.c:1243
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
In drivers/cpufreq/intel_pstate.c (ffffffff8290ec06)
Location: drivers/cpufreq/intel_pstate.c:1243
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
In drivers/cpufreq/intel_pstate.c (ffffffff8291561c)
Location: drivers/cpufreq/intel_pstate.c:1243
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
