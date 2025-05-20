# Function: <code>play_dead_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81052740)
Location: arch/x86/kernel/smpboot.c:1532
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
**Symbols:**

```
ffffffff81052740-ffffffff8105277f: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81052850)
Location: arch/x86/kernel/smpboot.c:1559
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81052850-ffffffff8105288f: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81055160)
Location: arch/x86/kernel/smpboot.c:1587
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81055160-ffffffff81055193: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054a80)
Location: arch/x86/kernel/smpboot.c:1593
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81054a80-ffffffff81054a9c: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810588b0)
Location: arch/x86/kernel/smpboot.c:1506
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81058840-ffffffff8105885c: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105b515)
Location: arch/x86/kernel/smpboot.c:1562
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8105b4b0-ffffffff8105b4cc: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81061195)
Location: arch/x86/kernel/smpboot.c:1563
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81061130-ffffffff8106114c: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064855)
Location: arch/x86/kernel/smpboot.c:1628
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810647e0-ffffffff810647fc: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064ed5)
Location: arch/x86/kernel/smpboot.c:1628
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81064e60-ffffffff81064e7c: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b605)
Location: arch/x86/kernel/smpboot.c:1655
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8106b590-ffffffff8106b5ac: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106d2a5)
Location: arch/x86/kernel/smpboot.c:1649
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/sev-es.c:sev_es_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8106d200-ffffffff8106d21c: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106dd15)
Location: arch/x86/kernel/smpboot.c:1650
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8106dca0-ffffffff8106dcbc: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81079525)
Location: arch/x86/kernel/smpboot.c:1657
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810794b0-ffffffff810794cc: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81088330)
Location: arch/x86/kernel/smpboot.c:1722
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81088330-ffffffff81088351: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bdd0)
Location: arch/x86/kernel/smpboot.c:1722
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8109bdd0-ffffffff8109bdf9: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109ed10)
Location: arch/x86/kernel/smpboot.c:1612
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff8109ed10-ffffffff8109ed39: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a6140)
Location: arch/x86/kernel/smpboot.c:1478
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810a6140-ffffffff810a6169: play_dead_common (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810649c5)
Location: arch/x86/kernel/smpboot.c:1628
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81064950-ffffffff8106496c: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054ca5)
Location: arch/x86/kernel/smpboot.c:1628
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81054c40-ffffffff81054c56: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064e75)
Location: arch/x86/kernel/smpboot.c:1628
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff81064e00-ffffffff81064e1c: play_dead_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void play_dead_common();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81066455)
Location: arch/x86/kernel/smpboot.c:1628
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/power/cpu.c:resume_play_dead
```
**Symbols:**

```
ffffffff810663e0-ffffffff810663fc: play_dead_common (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
