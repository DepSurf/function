# Function: <code>xen_vmcore_pfn_is_ram</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_vmcore_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_hvm.c (ffffffff8102c859)
Location: arch/x86/xen/mmu_hvm.c:18
Inline: True
```
**Symbols:**

```
ffffffff8102c7f0-ffffffff8102c88f: xen_vmcore_pfn_is_ram (STB_LOCAL)
ffffffff81e46624-ffffffff81e46638: xen_vmcore_pfn_is_ram.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_vmcore_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_hvm.c (ffffffff81033929)
Location: arch/x86/xen/mmu_hvm.c:18
Inline: True
```
**Symbols:**

```
ffffffff810338c0-ffffffff8103395f: xen_vmcore_pfn_is_ram (STB_LOCAL)
ffffffff820518a6-ffffffff820518ba: xen_vmcore_pfn_is_ram.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_vmcore_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_hvm.c (ffffffff810338b9)
Location: arch/x86/xen/mmu_hvm.c:18
Inline: True
```
**Symbols:**

```
ffffffff81033850-ffffffff810338ef: xen_vmcore_pfn_is_ram (STB_LOCAL)
ffffffff820cfd92-ffffffff820cfda6: xen_vmcore_pfn_is_ram.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xen_vmcore_pfn_is_ram(struct vmcore_cb *cb, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_hvm.c (ffffffff81039bb9)
Location: arch/x86/xen/mmu_hvm.c:18
Inline: True
```
**Symbols:**

```
ffffffff81039b50-ffffffff81039bef: xen_vmcore_pfn_is_ram (STB_LOCAL)
ffffffff821aa700-ffffffff821aa714: xen_vmcore_pfn_is_ram.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
