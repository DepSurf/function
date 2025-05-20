# Function: <code>mce_start</code>

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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045c5e)
Location: arch/x86/kernel/cpu/mcheck/mce.c:802
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045848)
Location: arch/x86/kernel/cpu/mcheck/mce.c:866
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104748e)
Location: arch/x86/kernel/cpu/mcheck/mce.c:939
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047017)
Location: arch/x86/kernel/cpu/mcheck/mce.c:899
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104aac3)
Location: arch/x86/kernel/cpu/mcheck/mce.c:909
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104d42d)
Location: arch/x86/kernel/cpu/mcheck/mce.c:917
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104aaf5)
Location: arch/x86/kernel/cpu/mce/core.c:921
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104db8e)
Location: arch/x86/kernel/cpu/mce/core.c:952
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e532)
Location: arch/x86/kernel/cpu/mce/core.c:952
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051e70)
Location: arch/x86/kernel/cpu/mce/core.c:928
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff81051e70-ffffffff81051fa2: mce_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050f90)
Location: arch/x86/kernel/cpu/mce/core.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff81050f90-ffffffff810510c2: mce_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052cc0)
Location: arch/x86/kernel/cpu/mce/core.c:1004
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff81052cc0-ffffffff81052e04: mce_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b1c0)
Location: arch/x86/kernel/cpu/mce/core.c:1016
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff8105b1c0-ffffffff8105b304: mce_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f159f0)
Location: arch/x86/kernel/cpu/mce/core.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff81f159f0-ffffffff81f15b2d: mce_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd120)
Location: arch/x86/kernel/cpu/mce/core.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff820bd120-ffffffff820bd25d: mce_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213eb30)
Location: arch/x86/kernel/cpu/mce/core.c:1040
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff8213eb30-ffffffff8213ec6d: mce_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mce_start(int *no_way_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220b50)
Location: arch/x86/kernel/cpu/mce/core.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
**Symbols:**

```
ffffffff82220b50-ffffffff82220c8d: mce_start (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e692)
Location: arch/x86/kernel/cpu/mce/core.c:952
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103db62)
Location: arch/x86/kernel/cpu/mce/core.c:952
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e4e2)
Location: arch/x86/kernel/cpu/mce/core.c:952
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f922)
Location: arch/x86/kernel/cpu/mce/core.c:952
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
