# Function: <code>flush_tlb_local</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a99e)
Location: arch/x86/mm/tlb.c:1159
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/platform/uv/tlb_uv.c:bau_process_message
```
**Symbols:**

```
ffffffff8108ba20-ffffffff8108ba32: flush_tlb_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ac0e)
Location: arch/x86/mm/tlb.c:1095
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8108ba70-ffffffff8108ba82: flush_tlb_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b72e)
Location: arch/x86/mm/tlb.c:1139
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8108c660-ffffffff8108c672: flush_tlb_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109ad0e)
Location: arch/x86/mm/tlb.c:1198
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8109bea0-ffffffff8109beb2: flush_tlb_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae0b7)
Location: arch/x86/mm/tlb.c:1168
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff810af410-ffffffff810af43b: flush_tlb_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8357)
Location: arch/x86/mm/tlb.c:1192
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff810c9860-ffffffff810c988b: flush_tlb_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cba90)
Location: arch/x86/mm/tlb.c:1213
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff810ccee0-ffffffff810ccf0b: flush_tlb_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_local();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d4120)
Location: arch/x86/mm/tlb.c:1222
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff810d55b0-ffffffff810d55db: flush_tlb_local (STB_GLOBAL)
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
