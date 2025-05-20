# Function: <code>xen_exchange_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e070)
Location: arch/x86/xen/mmu.c:2585
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101e070-ffffffff8101e10e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d460)
Location: arch/x86/xen/mmu.c:2575
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101d460-ffffffff8101d4fe: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101db80)
Location: arch/x86/xen/mmu.c:2575
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101db80-ffffffff8101dc1e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8101fe10)
Location: arch/x86/xen/mmu_pv.c:2576
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101fe10-ffffffff8101febe: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020a70)
Location: arch/x86/xen/mmu_pv.c:2517
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81020a70-ffffffff81020b1e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021560)
Location: arch/x86/xen/mmu_pv.c:2553
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81021560-ffffffff81021609: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020dd0)
Location: arch/x86/xen/mmu_pv.c:2561
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81020dd0-ffffffff81020e79: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810228b0)
Location: arch/x86/xen/mmu_pv.c:2549
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810228b0-ffffffff8102294e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810231f0)
Location: arch/x86/xen/mmu_pv.c:2549
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810231f0-ffffffff8102328e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025aa0)
Location: arch/x86/xen/mmu_pv.c:2549
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81025aa0-ffffffff81025b3e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810261c0)
Location: arch/x86/xen/mmu_pv.c:2231
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810261c0-ffffffff8102625e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810280e0)
Location: arch/x86/xen/mmu_pv.c:2230
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810280e0-ffffffff8102817e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2233
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8102c720-ffffffff8102c7e0: xen_exchange_memory (STB_LOCAL)
ffffffff81c976d0-ffffffff81c9770d: xen_exchange_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2259
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810314d0-ffffffff810315b2: xen_exchange_memory (STB_LOCAL)
ffffffff81e46b2e-ffffffff81e46b6b: xen_exchange_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2259
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81038c90-ffffffff81038d72: xen_exchange_memory (STB_LOCAL)
ffffffff82051adf-ffffffff82051b1c: xen_exchange_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2267
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81038bc0-ffffffff81038ca2: xen_exchange_memory (STB_LOCAL)
ffffffff820cffca-ffffffff820d0007: xen_exchange_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2284
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8103efd0-ffffffff8103f0b2: xen_exchange_memory (STB_LOCAL)
ffffffff821aa937-ffffffff821aa974: xen_exchange_memory.cold (STB_LOCAL)
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
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023350)
Location: arch/x86/xen/mmu_pv.c:2549
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81023350-ffffffff810233ee: xen_exchange_memory (STB_LOCAL)
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
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810231b0)
Location: arch/x86/xen/mmu_pv.c:2549
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810231b0-ffffffff8102324e: xen_exchange_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_exchange_memory(long unsigned int extents_in, unsigned int order_in, long unsigned int *pfns_in, long unsigned int extents_out, unsigned int order_out, long unsigned int *mfns_out, unsigned int address_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023630)
Location: arch/x86/xen/mmu_pv.c:2549
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81023630-ffffffff810236ce: xen_exchange_memory (STB_LOCAL)
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
