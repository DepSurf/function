# Function: <code>free_vmap_area_noflush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cd1c0)
Location: mm/vmalloc.c:681
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:remove_vm_area
```
**Symbols:**

```
ffffffff811cd1c0-ffffffff811cd25e: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ea210)
Location: mm/vmalloc.c:699
Inline: True
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff811ea210-ffffffff811ea2bd: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fb330)
Location: mm/vmalloc.c:689
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff811fb330-ffffffff811fb3bc: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81206070)
Location: mm/vmalloc.c:740
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81206070-ffffffff812060fc: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121ed90)
Location: mm/vmalloc.c:738
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_vmap_block
```
**Symbols:**

```
ffffffff8121ed90-ffffffff8121ee1c: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81241660)
Location: mm/vmalloc.c:718
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81241660-ffffffff812416ec: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255d60)
Location: mm/vmalloc.c:718
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81255d60-ffffffff81255dec: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81268eb0)
Location: mm/vmalloc.c:1323
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81268eb0-ffffffff81268f44: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81277d90)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81277d90-ffffffff81277e7f: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a8c70)
Location: mm/vmalloc.c:1428
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_vmap_block
```
**Symbols:**

```
ffffffff812a8c70-ffffffff812a8d5f: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b3eb0)
Location: mm/vmalloc.c:1422
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812b3eb0-ffffffff812b41bb: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b9590)
Location: mm/vmalloc.c:1692
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812b9590-ffffffff812b9898: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fbb30)
Location: mm/vmalloc.c:1744
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_vmap_block
```
**Symbols:**

```
ffffffff812fbb30-ffffffff812fbe38: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81360b60)
Location: mm/vmalloc.c:1764
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81360b60-ffffffff81360ea0: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813dc4c0)
Location: mm/vmalloc.c:1822
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff813dc4c0-ffffffff813dc864: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81410df0)
Location: mm/vmalloc.c:1817
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_vmap_block
```
**Symbols:**

```
ffffffff81410df0-ffffffff81411177: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143d5e0)
Location: mm/vmalloc.c:1817
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_vmap_block
```
**Symbols:**

```
ffffffff8143d5e0-ffffffff8143d967: free_vmap_area_noflush (STB_LOCAL)
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
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030e2d0)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffff80001030e2d0-ffff80001030e44c: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0529d50)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:free_unmap_vmap_area
```
**Symbols:**

```
c0529d50-c0529e7c: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003df020)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_vmap_block
```
**Symbols:**

```
c0000000003df020-c0000000003df1d8: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000216d84)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffe000216d84-ffffffe000216ea2: free_vmap_area_noflush (STB_LOCAL)
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
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812703e0)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812703e0-ffffffff812704cf: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262350)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81262350-ffffffff8126243f: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e180)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8126e180-ffffffff8126e26f: free_vmap_area_noflush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_vmap_area_noflush(struct vmap_area *va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127db40)
Location: mm/vmalloc.c:1327
Inline: False
Direct callers:
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff8127db40-ffffffff8127dc2d: free_vmap_area_noflush (STB_LOCAL)
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
