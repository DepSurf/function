# Function: <code>dax_finish_sync_fault</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cd8c0)
Location: fs/dax.c:1575
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff812cd8c0-ffffffff812cdb3b: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f8040)
Location: fs/dax.c:1797
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff812f8040-ffffffff812f828c: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130e8d0)
Location: fs/dax.c:1696
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff8130e8d0-ffffffff8130eb8e: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81335020)
Location: fs/dax.c:1710
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81335020-ffffffff813352fd: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81348c00)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81348c00-ffffffff81348ee1: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138f140)
Location: fs/dax.c:1704
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff8138f140-ffffffff8138f1d5: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a07d0)
Location: fs/dax.c:1719
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff813a07d0-ffffffff813a0865: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a6f10)
Location: fs/dax.c:1731
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff813a6f10-ffffffff813a6fa5: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1703
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff81cc6090-ffffffff81cc60b1: dax_finish_sync_fault.cold (STB_LOCAL)
ffffffff813f6dd0-ffffffff813f6e63: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1663
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff81e782d2-ffffffff81e782f2: dax_finish_sync_fault.cold (STB_LOCAL)
ffffffff814699e0-ffffffff81469a82: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1947
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff8206a1e9-ffffffff8206a209: dax_finish_sync_fault.cold (STB_LOCAL)
ffffffff814fa7c0-ffffffff814fa85f: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1989
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff820ea1c3-ffffffff820ea1e2: dax_finish_sync_fault.cold (STB_LOCAL)
ffffffff81531c20-ffffffff81531cab: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, unsigned int order, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1973
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
**Symbols:**

```
ffffffff821c6c65-ffffffff821c6c7d: dax_finish_sync_fault.cold (STB_LOCAL)
ffffffff81566b10-ffffffff81566b98: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff8000104090a8)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffff8000104090a8-ffff8000104093d8: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000515470)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
c000000000515470-c0000000005158b4: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b3422)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffe0002b3422-ffffffe0002b36ce: dax_finish_sync_fault (STB_GLOBAL)
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
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813411e0)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff813411e0-ffffffff813414c1: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81331bb0)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81331bb0-ffffffff81331e85: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133ecb0)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff8133ecb0-ffffffff8133ef91: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t dax_finish_sync_fault(struct vm_fault *vmf, enum page_entry_size pe_size, pfn_t pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81351090)
Location: fs/dax.c:1714
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_huge_fault
```
**Symbols:**

```
ffffffff81351090-ffffffff81351398: dax_finish_sync_fault (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_entry_size pe_size</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
