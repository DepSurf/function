# Function: <code>xen_teardown_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810239a0)
Location: arch/x86/xen/time.c:396
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
**Symbols:**

```
ffffffff810239a0-ffffffff810239de: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81022c40)
Location: arch/x86/xen/time.c:305
Inline: True
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
```
**Symbols:**

```
ffffffff81022c40-ffffffff81022c7e: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81023390)
Location: arch/x86/xen/time.c:305
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_dead
  - arch/x86/xen/time.c:xen_setup_timer
```
**Symbols:**

```
ffffffff81023390-ffffffff810233ce: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101b1a8)
Location: arch/x86/xen/time.c:309
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101b050-ffffffff8101b08a: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101baa8)
Location: arch/x86/xen/time.c:310
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101b950-ffffffff8101b988: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101c330)
Location: arch/x86/xen/time.c:310
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101c330-ffffffff8101c368: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101be50)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101be50-ffffffff8101be88: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101d990)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101d990-ffffffff8101d9c9: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e330)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101e330-ffffffff8101e369: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81020842)
Location: arch/x86/xen/time.c:324
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff810207b0-ffffffff810207ec: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81021282)
Location: arch/x86/xen/time.c:325
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff810211f0-ffffffff8102122c: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81023622)
Location: arch/x86/xen/time.c:325
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81023590-ffffffff810235cc: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102786d)
Location: arch/x86/xen/time.c:325
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff810277b0-ffffffff81027803: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102bc0d)
Location: arch/x86/xen/time.c:325
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102bb50-ffffffff8102bbab: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81032a83)
Location: arch/x86/xen/time.c:325
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff810328d0-ffffffff8103292b: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81032a23)
Location: arch/x86/xen/time.c:333
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81032870-ffffffff810328cb: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81038d13)
Location: arch/x86/xen/time.c:333
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_setup_timer
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81038b60-ffffffff81038bbb: xen_teardown_timer (STB_GLOBAL)
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
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e340)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101e340-ffffffff8101e379: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e2f0)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101e2f0-ffffffff8101e329: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_teardown_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e560)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8101e560-ffffffff8101e599: xen_teardown_timer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
