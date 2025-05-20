# Function: <code>xen_uninit_lock_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102bfe0)
Location: arch/x86/xen/spinlock.c:303
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
```
**Symbols:**

```
ffffffff8102bfe0-ffffffff8102c04b: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102b310)
Location: arch/x86/xen/spinlock.c:309
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
```
**Symbols:**

```
ffffffff8102b310-ffffffff8102b37b: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102ba10)
Location: arch/x86/xen/spinlock.c:106
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_prepare
```
**Symbols:**

```
ffffffff8102ba10-ffffffff8102ba7b: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff81029cb0)
Location: arch/x86/xen/spinlock.c:106
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81029cb0-ffffffff81029d1c: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff81029ee0)
Location: arch/x86/xen/spinlock.c:111
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81029ee0-ffffffff81029f4c: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102a960)
Location: arch/x86/xen/spinlock.c:109
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102a960-ffffffff8102a9cb: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102afd0)
Location: arch/x86/xen/spinlock.c:97
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102afd0-ffffffff8102b03b: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102cdb0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102cdb0-ffffffff8102ce1b: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102d680)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102d680-ffffffff8102d6eb: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102f7b0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102f7b0-ffffffff8102f81b: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff81030520)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81030520-ffffffff81030590: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff81031020)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81031020-ffffffff81031090: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81c97c3c-ffffffff81c97c51: xen_uninit_lock_cpu.cold (STB_LOCAL)
ffffffff81036250-ffffffff81036347: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81e47056-ffffffff81e4706b: xen_uninit_lock_cpu.cold (STB_LOCAL)
ffffffff8103c0c0-ffffffff8103c1c4: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff82051e96-ffffffff82051eab: xen_uninit_lock_cpu.cold (STB_LOCAL)
ffffffff810449e0-ffffffff81044af1: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff820d030b-ffffffff820d0320: xen_uninit_lock_cpu.cold (STB_LOCAL)
ffffffff81044b20-ffffffff81044c31: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff821aac78-ffffffff821aac8d: xen_uninit_lock_cpu.cold (STB_LOCAL)
ffffffff8104b050-ffffffff8104b161: xen_uninit_lock_cpu (STB_GLOBAL)
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
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102d7e0)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102d7e0-ffffffff8102d84b: xen_uninit_lock_cpu (STB_GLOBAL)
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
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102d640)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102d640-ffffffff8102d6ab: xen_uninit_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_uninit_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102e430)
Location: arch/x86/xen/spinlock.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102e430-ffffffff8102e49b: xen_uninit_lock_cpu (STB_GLOBAL)
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
