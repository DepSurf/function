# Function: <code>hash__tlbiel_all</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hash__tlbiel_all(unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/hash_native.c (c000000000094550)
Location: arch/powerpc/mm/book3s64/hash_native.c:118
Inline: False
Direct callers:
  - arch/powerpc/kernel/mce_power.c:mce_handle_error
  - arch/powerpc/kernel/mce_power.c:mce_handle_error
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu_secondary
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__early_init_mmu_secondary
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__early_init_mmu
  - arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_realmode_machine_check
  - arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_realmode_machine_check
```
**Symbols:**

```
c000000000094550-c000000000094674: hash__tlbiel_all (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
