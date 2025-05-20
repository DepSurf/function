# Function: <code>copy_cpu_funcs</code>

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
In drivers/cpufreq/intel_pstate.c (ffffffff81fb48b1)
Location: drivers/cpufreq/intel_pstate.c:1231
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff81fe11f2)
Location: drivers/cpufreq/intel_pstate.c:1623
Inline: False
```
**Symbols:**

```
ffffffff81fe11f2-ffffffff81fe124f: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8201ee91)
Location: drivers/cpufreq/intel_pstate.c:2341
Inline: False
```
**Symbols:**

```
ffffffff8201ee91-ffffffff8201ef02: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff82101a0a)
Location: drivers/cpufreq/intel_pstate.c:2403
Inline: False
```
**Symbols:**

```
ffffffff82101a0a-ffffffff82101a9c: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8270b102)
Location: drivers/cpufreq/intel_pstate.c:2134
Inline: False
```
**Symbols:**

```
ffffffff8270b102-ffffffff8270b164: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff827352f9)
Location: drivers/cpufreq/intel_pstate.c:2367
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff827352f9-ffffffff8273535b: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff828ef225)
Location: drivers/cpufreq/intel_pstate.c:2442
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff828ef225-ffffffff828ef287: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8290a720)
Location: drivers/cpufreq/intel_pstate.c:2471
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8290a720-ffffffff8290a782: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff82914117)
Location: drivers/cpufreq/intel_pstate.c:2577
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff82914117-ffffffff82914179: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff82d26ccb)
Location: drivers/cpufreq/intel_pstate.c:2591
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff82d26ccb-ffffffff82d26d2d: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff830152d6)
Location: drivers/cpufreq/intel_pstate.c:2891
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff830152d6-ffffffff83015338: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8322034a)
Location: drivers/cpufreq/intel_pstate.c:2871
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8322034a-ffffffff832203ac: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff83309b0e)
Location: drivers/cpufreq/intel_pstate.c:3063
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff83309b0e-ffffffff83309b70: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff834c330d)
Location: drivers/cpufreq/intel_pstate.c:3231
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff834c330d-ffffffff834c3380: copy_cpu_funcs (STB_LOCAL)
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
In drivers/cpufreq/intel_pstate.c (ffffffff83f03682)
Location: drivers/cpufreq/intel_pstate.c:3195
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff837295f2)
Location: drivers/cpufreq/intel_pstate.c:3221
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
In drivers/cpufreq/intel_pstate.c (ffffffff8395d582)
Location: drivers/cpufreq/intel_pstate.c:3237
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
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
<summary>In <code>aws</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff828f9851)
Location: drivers/cpufreq/intel_pstate.c:2577
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff828f9851-ffffffff828f98b3: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff828f1a14)
Location: drivers/cpufreq/intel_pstate.c:2577
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff828f1a14-ffffffff828f1a76: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff8290e763)
Location: drivers/cpufreq/intel_pstate.c:2577
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8290e763-ffffffff8290e7c5: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_cpu_funcs(struct pstate_funcs *funcs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/intel_pstate.c (ffffffff82915179)
Location: drivers/cpufreq/intel_pstate.c:2577
Inline: False
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff82915179-ffffffff829151db: copy_cpu_funcs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
