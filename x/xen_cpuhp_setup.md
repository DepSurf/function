# Function: <code>xen_cpuhp_setup</code>

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
int xen_cpuhp_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81082976)
Location: arch/x86/xen/enlighten.c:1527
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81082976-ffffffff810829e9: xen_cpuhp_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81019860)
Location: arch/x86/xen/enlighten.c:90
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81019860-ffffffff810198db: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101a140)
Location: arch/x86/xen/enlighten.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101a140-ffffffff8101a1bb: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ab20)
Location: arch/x86/xen/enlighten.c:102
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101ab20-ffffffff8101ab9b: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b2f0)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101b2f0-ffffffff8101b36b: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ce10)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101ce10-ffffffff8101ce88: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d790)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101d790-ffffffff8101d808: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101fc00)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101fc00-ffffffff8101fc7e: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff810206a0)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff810206a0-ffffffff8102071e: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81022a40)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81022a40-ffffffff81022ab8: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff810268e0)
Location: arch/x86/xen/enlighten.c:108
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff810268e0-ffffffff81026958: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8102aa80)
Location: arch/x86/xen/enlighten.c:78
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8102aa80-ffffffff8102ab1c: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff810316a0)
Location: arch/x86/xen/enlighten.c:78
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff810316a0-ffffffff8103173c: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff810316a0)
Location: arch/x86/xen/enlighten.c:78
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff810316a0-ffffffff8103173c: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81037990)
Location: arch/x86/xen/enlighten.c:81
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81037990-ffffffff81037a2c: xen_cpuhp_setup (STB_GLOBAL)
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
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d790)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101d790-ffffffff8101d808: xen_cpuhp_setup (STB_GLOBAL)
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
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d750)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101d750-ffffffff8101d7c8: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_cpuhp_setup(int (*cpu_up_prepare_cb)(unsigned int), int (*cpu_dead_cb)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101d9a0)
Location: arch/x86/xen/enlighten.c:104
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8101d9a0-ffffffff8101da18: xen_cpuhp_setup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*cpu_up_prepare_cb)(unsigned int)</code>
</li>
<li>
<b>Param added. </b>
<code>int (*cpu_dead_cb)(unsigned int)</code>
</li>
</ul>
</details>
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
