# Function: <code>copy_array</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff826b8261)
Location: arch/x86/kernel/cpu/hypervisor.c:73
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff826e1f47)
Location: arch/x86/kernel/cpu/hypervisor.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff82898880)
Location: arch/x86/kernel/cpu/hypervisor.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff828b0482)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff828b38bf)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff82cd88b8)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
**Symbols:**

```
ffffffff82cd88b8-ffffffff82cd88dc: copy_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff82fc4c8a)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
**Symbols:**

```
ffffffff82fc4c8a-ffffffff82fc4cae: copy_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff831cf46d)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
**Symbols:**

```
ffffffff831cf46d-ffffffff831cf491: copy_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff832b1825)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
```
In kernel/bpf/verifier.c (ffffffff81235a90)
Location: kernel/bpf/verifier.c:752
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff832b1825-ffffffff832b1849: copy_array (STB_LOCAL)
ffffffff81235a90-ffffffff81235b0c: copy_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff83462a6f)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
```
In kernel/bpf/verifier.c (ffffffff81278e80)
Location: kernel/bpf/verifier.c:979
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff83462a6f-ffffffff83462aa1: copy_array (STB_LOCAL)
ffffffff81278e80-ffffffff81278f1a: copy_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff83e84ffe)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
```
In kernel/bpf/verifier.c (ffffffff812cfc10)
Location: kernel/bpf/verifier.c:1168
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_func_state
  - kernel/bpf/verifier.c:copy_func_state
```
**Symbols:**

```
ffffffff812cfc10-ffffffff812cfccd: copy_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff836a853e)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
```
In kernel/bpf/verifier.c (ffffffff812f9bb0)
Location: kernel/bpf/verifier.c:1545
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_func_state
  - kernel/bpf/verifier.c:copy_func_state
```
**Symbols:**

```
ffffffff812f9bb0-ffffffff812f9c7e: copy_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void copy_array(const void *src, void *target, unsigned int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/hypervisor.c (ffffffff838d8a7e)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
```
```
In kernel/bpf/verifier.c (ffffffff81318750)
Location: kernel/bpf/verifier.c:1186
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:setup_func_entry
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_func_state
  - kernel/bpf/verifier.c:copy_func_state
```
**Symbols:**

```
ffffffff81318750-ffffffff8131881e: copy_array (STB_LOCAL)
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff828a18de)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff82899aa7)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff828b48a1)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
In arch/x86/kernel/cpu/hypervisor.c (ffffffff828b48c2)
Location: arch/x86/kernel/cpu/hypervisor.c:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
  - arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform
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
