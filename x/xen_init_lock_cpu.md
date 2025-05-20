# Function: <code>xen_init_lock_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102bf00)
Location: arch/x86/xen/spinlock.c:275
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff8102bf00-ffffffff8102bfdd: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102b230)
Location: arch/x86/xen/spinlock.c:281
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff8102b230-ffffffff8102b30d: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff8102b930)
Location: arch/x86/xen/spinlock.c:78
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102b930-ffffffff8102ba0d: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff81029bd0)
Location: arch/x86/xen/spinlock.c:78
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81029bd0-ffffffff81029ca3: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/spinlock.c (ffffffff81029df0)
Location: arch/x86/xen/spinlock.c:80
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81029df0-ffffffff81029edb: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:78
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102a9cb-ffffffff8102a9e1: xen_init_lock_cpu.cold.1 (STB_LOCAL)
ffffffff8102a880-ffffffff8102a95e: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102b03b-ffffffff8102b051: xen_init_lock_cpu.cold.4 (STB_LOCAL)
ffffffff8102aef0-ffffffff8102afce: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102ce33-ffffffff8102ce50: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8102ccf0-ffffffff8102cda9: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102d703-ffffffff8102d720: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8102d5c0-ffffffff8102d679: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102f833-ffffffff8102f850: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8102f6f0-ffffffff8102f7a9: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81bd2d73-ffffffff81bd2d90: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff81030460-ffffffff81030519: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81bc50c2-ffffffff81bc50df: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff81030f60-ffffffff81031019: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81c97c11-ffffffff81c97c3c: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff81036100-ffffffff81036248: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81e4702b-ffffffff81e47056: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8103bf60-ffffffff8103c0bc: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff82051e81-ffffffff82051e96: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff81044850-ffffffff810449ce: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff820d02f6-ffffffff820d030b: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff81044990-ffffffff81044b0e: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff821aac63-ffffffff821aac78: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8104aec0-ffffffff8104b03e: xen_init_lock_cpu (STB_GLOBAL)
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
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102d863-ffffffff8102d880: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8102d720-ffffffff8102d7d9: xen_init_lock_cpu (STB_GLOBAL)
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
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102d6c3-ffffffff8102d6e0: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8102d580-ffffffff8102d639: xen_init_lock_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_init_lock_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/xen/spinlock.c:66
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_online
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102e4b3-ffffffff8102e4d0: xen_init_lock_cpu.cold (STB_LOCAL)
ffffffff8102e370-ffffffff8102e429: xen_init_lock_cpu (STB_GLOBAL)
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
