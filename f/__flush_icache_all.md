# Function: <code>__flush_icache_all</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/alternative.c (ffff80001009b590)
Location: arch/arm64/include/asm/cacheflush.h:148
Inline: True
Inline callers:
  - arch/arm64/kernel/alternative.c:__apply_alternatives
```
```
In arch/arm64/mm/flush.c (ffff8000100adc3c)
Location: arch/arm64/include/asm/cacheflush.h:148
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:sync_icache_aliases
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb130)
Location: arch/arm64/include/asm/cacheflush.h:148
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In arch/arm64/kvm/hyp/tlb.c (ffff800010daf10c)
Location: arch/arm64/include/asm/cacheflush.h:148
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_vmid_ipa
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/flush.c (c031ee34)
Location: arch/arm/include/asm/cacheflush.h:205
Inline: True
Inline callers:
  - arch/arm/mm/flush.c:__flush_anon_page
  - arch/arm/mm/flush.c:__sync_icache_dcache
  - arch/arm/mm/flush.c:flush_cache_range
```
```
In arch/arm/mm/context.c (c032276c)
Location: arch/arm/include/asm/cacheflush.h:205
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
</details>
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
