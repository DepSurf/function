# Function: <code>hv_call_create_vp</code>

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
int hv_call_create_vp(int node, u64 partition_id, u32 vp_index, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81034560)
Location: arch/x86/hyperv/hv_proc.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81034560-ffffffff810346e6: hv_call_create_vp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hv_call_create_vp(int node, u64 partition_id, u32 vp_index, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81039800)
Location: arch/x86/hyperv/hv_proc.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81039800-ffffffff81039986: hv_call_create_vp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hv_call_create_vp(int node, u64 partition_id, u32 vp_index, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff810406d0)
Location: arch/x86/hyperv/hv_proc.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff810406d0-ffffffff8104086f: hv_call_create_vp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_call_create_vp(int node, u64 partition_id, u32 vp_index, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81049990)
Location: arch/x86/hyperv/hv_proc.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81049990-ffffffff81049b2f: hv_call_create_vp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_call_create_vp(int node, u64 partition_id, u32 vp_index, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81049bc0)
Location: arch/x86/hyperv/hv_proc.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81049bc0-ffffffff81049d5f: hv_call_create_vp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_call_create_vp(int node, u64 partition_id, u32 vp_index, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81050ea0)
Location: arch/x86/hyperv/hv_proc.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81050ea0-ffffffff81050fcb: hv_call_create_vp (STB_GLOBAL)
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
