# Function: <code>hv_call_add_logical_proc</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_call_add_logical_proc(int node, u32 lp_index, u32 apic_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff810343c0)
Location: arch/x86/hyperv/hv_proc.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff810343c0-ffffffff81034556: hv_call_add_logical_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hv_call_add_logical_proc(int node, u32 lp_index, u32 apic_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81039660)
Location: arch/x86/hyperv/hv_proc.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81039660-ffffffff810397f6: hv_call_add_logical_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hv_call_add_logical_proc(int node, u32 lp_index, u32 apic_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81040520)
Location: arch/x86/hyperv/hv_proc.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81040520-ffffffff810406cc: hv_call_add_logical_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_call_add_logical_proc(int node, u32 lp_index, u32 apic_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff810497d0)
Location: arch/x86/hyperv/hv_proc.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff810497d0-ffffffff8104997a: hv_call_add_logical_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_call_add_logical_proc(int node, u32 lp_index, u32 apic_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81049a00)
Location: arch/x86/hyperv/hv_proc.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81049a00-ffffffff81049baa: hv_call_add_logical_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_call_add_logical_proc(int node, u32 lp_index, u32 apic_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81050d80)
Location: arch/x86/hyperv/hv_proc.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81050d80-ffffffff81050e89: hv_call_add_logical_proc (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
