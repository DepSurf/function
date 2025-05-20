# Function: <code>find_vmap_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cc6b0)
Location: mm/vmalloc.c:708
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_32_user
```
**Symbols:**

```
ffffffff811cc6b0-ffffffff811cc70c: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e9720)
Location: mm/vmalloc.c:732
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff811e9720-ffffffff811e977c: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811faa60)
Location: mm/vmalloc.c:713
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff811faa60-ffffffff811faabc: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812055d0)
Location: mm/vmalloc.c:764
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812055d0-ffffffff8120562c: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121e580)
Location: mm/vmalloc.c:762
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8121e580-ffffffff8121e5dc: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81241420)
Location: mm/vmalloc.c:745
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81241420-ffffffff8124147c: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255b10)
Location: mm/vmalloc.c:745
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81255b10-ffffffff81255b6a: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81267e70)
Location: mm/vmalloc.c:1350
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81267e70-ffffffff81267eca: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812767c0)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812767c0-ffffffff8127681a: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a842b)
Location: mm/vmalloc.c:1459
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b3697)
Location: mm/vmalloc.c:1459
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bdc3f)
Location: mm/vmalloc.c:1729
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8130040f)
Location: mm/vmalloc.c:1781
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81367781)
Location: mm/vmalloc.c:1801
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
Direct callers:
  - mm/usercopy.c:check_heap_object
```
**Symbols:**

```
ffffffff813660b0-ffffffff81366112: find_vmap_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e3701)
Location: mm/vmalloc.c:1863
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
Direct callers:
  - mm/usercopy.c:check_heap_object
```
**Symbols:**

```
ffffffff813e1c70-ffffffff813e1cd2: find_vmap_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814181fc)
Location: mm/vmalloc.c:1857
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
Direct callers:
  - mm/usercopy.c:check_heap_object
```
**Symbols:**

```
ffffffff814169b0-ffffffff81416a12: find_vmap_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81444d4c)
Location: mm/vmalloc.c:1857
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
Direct callers:
  - mm/usercopy.c:check_heap_object
```
**Symbols:**

```
ffffffff81443480-ffffffff814434e2: find_vmap_area (STB_GLOBAL)
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
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030cbe8)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffff80001030cbe8-ffff80001030ccd8: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0527b80)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
c0527b80-c0527c00: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dd3b0)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
c0000000003dd3b0-c0000000003dd4c0: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000215c5c)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffe000215c5c-ffffffe000215cf6: find_vmap_area (STB_LOCAL)
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
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126ee10)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8126ee10-ffffffff8126ee6a: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81260d80)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81260d80-ffffffff81260dda: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126cbb0)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8126cbb0-ffffffff8126cc0a: find_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vmap_area *find_vmap_area(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127b550)
Location: mm/vmalloc.c:1358
Inline: False
Direct callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8127b550-ffffffff8127b5b0: find_vmap_area (STB_LOCAL)
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
