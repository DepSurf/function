# Function: <code>hv_call_deposit_pages</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81034603)
Location: arch/x86/hyperv/hv_proc.c:24
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
Direct callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
**Symbols:**

```
ffffffff81034040-ffffffff8103438b: hv_call_deposit_pages.part.0 (STB_LOCAL)
ffffffff81bc537b-ffffffff81bc538f: hv_call_deposit_pages.part.0.cold (STB_LOCAL)
ffffffff81034390-ffffffff810343b5: hv_call_deposit_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff810398a3)
Location: arch/x86/hyperv/hv_proc.c:24
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
Direct callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
**Symbols:**

```
ffffffff810392e0-ffffffff81039629: hv_call_deposit_pages.part.0 (STB_LOCAL)
ffffffff81c97f9b-ffffffff81c97faf: hv_call_deposit_pages.part.0.cold (STB_LOCAL)
ffffffff81039630-ffffffff81039655: hv_call_deposit_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81040780)
Location: arch/x86/hyperv/hv_proc.c:24
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
Direct callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
**Symbols:**

```
ffffffff81040160-ffffffff810404c8: hv_call_deposit_pages.part.0 (STB_LOCAL)
ffffffff81e47421-ffffffff81e47435: hv_call_deposit_pages.part.0.cold (STB_LOCAL)
ffffffff810404d0-ffffffff81040513: hv_call_deposit_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81049a43)
Location: arch/x86/hyperv/hv_proc.c:24
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
Direct callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
**Symbols:**

```
ffffffff810493c0-ffffffff81049754: hv_call_deposit_pages.part.0 (STB_LOCAL)
ffffffff81049770-ffffffff810497b3: hv_call_deposit_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81049c73)
Location: arch/x86/hyperv/hv_proc.c:24
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
Direct callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
**Symbols:**

```
ffffffff81049620-ffffffff81049989: hv_call_deposit_pages.part.0 (STB_LOCAL)
ffffffff820d047d-ffffffff820d04b2: hv_call_deposit_pages.part.0.cold (STB_LOCAL)
ffffffff810499a0-ffffffff810499e3: hv_call_deposit_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_proc.c (ffffffff81050f12)
Location: arch/x86/hyperv/hv_proc.c:24
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
Direct callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
**Symbols:**

```
ffffffff810509e0-ffffffff81050d08: hv_call_deposit_pages.part.0 (STB_LOCAL)
ffffffff821aaf92-ffffffff821aafc7: hv_call_deposit_pages.part.0.cold (STB_LOCAL)
ffffffff81050d20-ffffffff81050d63: hv_call_deposit_pages (STB_GLOBAL)
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
