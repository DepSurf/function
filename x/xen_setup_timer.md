# Function: <code>xen_setup_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810239e0)
Location: arch/x86/xen/time.c:408
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_cpu_notify
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff810239e0-ffffffff81023b03: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81022c80)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_cpu_notify
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff81022c80-ffffffff81022da7: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810233d0)
Location: arch/x86/xen/time.c:317
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_prepare
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff810233d0-ffffffff810234f7: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101b090)
Location: arch/x86/xen/time.c:320
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
```
**Symbols:**

```
ffffffff8101b090-ffffffff8101b1d6: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101b990)
Location: arch/x86/xen/time.c:321
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff8101b990-ffffffff8101bad6: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101c370)
Location: arch/x86/xen/time.c:321
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff8101c370-ffffffff8101c491: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101be90)
Location: arch/x86/xen/time.c:328
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff8101be90-ffffffff8101bfb1: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:328
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff8101dbdf-ffffffff8101dca9: xen_setup_timer.cold (STB_LOCAL)
ffffffff8101d9d0-ffffffff8101da29: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:328
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff8101e559-ffffffff8101e623: xen_setup_timer.cold (STB_LOCAL)
ffffffff8101e370-ffffffff8101e3c9: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:335
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
```
**Symbols:**

```
ffffffff81020ad8-ffffffff81020b9e: xen_setup_timer.cold (STB_LOCAL)
ffffffff810207f0-ffffffff8102086e: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:336
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
```
**Symbols:**

```
ffffffff81bd27c5-ffffffff81bd288b: xen_setup_timer.cold (STB_LOCAL)
ffffffff81021230-ffffffff810212ae: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:336
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
```
**Symbols:**

```
ffffffff81bc4967-ffffffff81bc4a2d: xen_setup_timer.cold (STB_LOCAL)
ffffffff810235d0-ffffffff8102364e: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:336
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff81c96fc9-ffffffff81c970ae: xen_setup_timer.cold (STB_LOCAL)
ffffffff81027810-ffffffff810278c4: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:336
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff81e463c8-ffffffff81e464c1: xen_setup_timer.cold (STB_LOCAL)
ffffffff8102bbb0-ffffffff8102bc64: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81032940)
Location: arch/x86/xen/time.c:336
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff81032940-ffffffff81032af3: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810328e0)
Location: arch/x86/xen/time.c:344
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810328e0-ffffffff81032a93: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81038bd0)
Location: arch/x86/xen/time.c:344
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff81038bd0-ffffffff81038d83: xen_setup_timer (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:328
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff8101e569-ffffffff8101e633: xen_setup_timer.cold (STB_LOCAL)
ffffffff8101e380-ffffffff8101e3d9: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:328
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff8101e519-ffffffff8101e5e3: xen_setup_timer.cold (STB_LOCAL)
ffffffff8101e330-ffffffff8101e389: xen_setup_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_setup_timer(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:328
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff8101e76d-ffffffff8101e837: xen_setup_timer.cold (STB_LOCAL)
ffffffff8101e5a0-ffffffff8101e5f9: xen_setup_timer (STB_GLOBAL)
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
