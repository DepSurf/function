# Function: <code>zap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811be790)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811be790-ffffffff811be8b7: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d9910)
Location: mm/memory.c:1387
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811d9910-ffffffff811d9a48: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size, struct zap_details *details);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e8d20)
Location: mm/memory.c:1383
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811e8d20-ffffffff811e8e58: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f3f80)
Location: mm/memory.c:1505
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811f3f80-ffffffff811f40b6: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120bc40)
Location: mm/memory.c:1596
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff8120bc40-ffffffff8120bd93: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122c810)
Location: mm/memory.c:1608
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff8122c810-ffffffff8122c960: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123faf0)
Location: mm/memory.c:1351
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff8123faf0-ffffffff8123fc5e: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81251c10)
Location: mm/memory.c:1321
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81251c10-ffffffff81251d81: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812601c0)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812601c0-ffffffff8126033c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81290790)
Location: mm/memory.c:1354
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81290790-ffffffff8129090c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129b220)
Location: mm/memory.c:1528
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff8129b220-ffffffff8129b39c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0540)
Location: mm/memory.c:1546
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff812a0540-ffffffff812a06b0: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e14d0)
Location: mm/memory.c:1641
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff812e14d0-ffffffff812e1640: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81341fe0)
Location: mm/memory.c:1735
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - mm/madvise.c:madvise_vma_behavior
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff81341fe0-ffffffff8134217c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b9ed0)
Location: mm/memory.c:1694
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff813b9ed0-ffffffff813ba0cd: zap_page_range (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f74f0)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
```
**Symbols:**

```
ffff8000102f74f0-ffff8000102f7650: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05194cc)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c05194cc-c051964c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c0230)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
c0000000003c0230-c0000000003c0404: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207b38)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
**Symbols:**

```
ffffffe000207b38-ffffffe000207c62: zap_page_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258810)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81258810-ffffffff8125898c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124acd0)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff8124acd0-ffffffff8124ae4c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812565b0)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff812565b0-ffffffff8125672c: zap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zap_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81266050)
Location: mm/memory.c:1326
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - mm/madvise.c:__do_sys_madvise
```
**Symbols:**

```
ffffffff81266050-ffffffff812661c1: zap_page_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct zap_details *details</code>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
