# Function: <code>mremap_to</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811c9ece)
Location: mm/mremap.c:395
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811e6300)
Location: mm/mremap.c:399
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff811f65e0)
Location: mm/mremap.c:415
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812013ab)
Location: mm/mremap.c:429
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81219d6b)
Location: mm/mremap.c:443
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8123b490)
Location: mm/mremap.c:439
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8123b490-ffffffff8123b6a9: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8124f850)
Location: mm/mremap.c:497
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8124f850-ffffffff8124fa69: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81261bb0)
Location: mm/mremap.c:498
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81261bb0-ffffffff81261ddc: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81270380)
Location: mm/mremap.c:498
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81270380-ffffffff812705ac: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812a0c10)
Location: mm/mremap.c:549
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff812a0c10-ffffffff812a0f57: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812ac400)
Location: mm/mremap.c:697
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff812ac400-ffffffff812ac745: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812b1730)
Location: mm/mremap.c:702
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff812b1730-ffffffff812b1a41: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, long unsigned int flags, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812f3300)
Location: mm/mremap.c:781
Inline: False
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff812f3300-ffffffff812f3611: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff81357040)
Location: mm/mremap.c:779
Inline: True
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff81357040-ffffffff813572e0: mremap_to.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff813d15f0)
Location: mm/mremap.c:781
Inline: True
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813d15f0-ffffffff813d1894: mremap_to.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff814061e0)
Location: mm/mremap.c:800
Inline: True
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff814061e0-ffffffff8140648d: mremap_to.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mremap.c (ffffffff814328f0)
Location: mm/mremap.c:867
Inline: True
Direct callers:
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff814328f0-ffffffff81432b9d: mremap_to.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffff800010306b3c)
Location: mm/mremap.c:498
Inline: True
Inline callers:
  - mm/mremap.c:__arm64_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c05247a4)
Location: mm/mremap.c:498
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (c0000000003d4ac0)
Location: mm/mremap.c:498
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffe000212212)
Location: mm/mremap.c:498
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff812689d0)
Location: mm/mremap.c:498
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff812689d0-ffffffff81268bfc: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff8125acc0)
Location: mm/mremap.c:498
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff8125acc0-ffffffff8125aeec: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81266770)
Location: mm/mremap.c:498
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81266770-ffffffff8126699c: mremap_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool *locked, struct vm_userfaultfd_ctx *uf, struct list_head *uf_unmap_early, struct list_head *uf_unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mremap.c (ffffffff81276110)
Location: mm/mremap.c:498
Inline: False
Direct callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
**Symbols:**

```
ffffffff81276110-ffffffff8127633c: mremap_to (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, old_len, new_addr, new_len, locked, uf, uf_unmap_early, uf_unmap</code> ➡️ <code>addr, old_len, new_addr, new_len, locked, flags, uf, uf_unmap_early, uf_unmap</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
