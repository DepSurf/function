# Function: <code>free_vmap_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ccc80)
Location: mm/vmalloc.c:876
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff811ccc80-ffffffff811cccf3: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e9d40)
Location: mm/vmalloc.c:900
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff811e9d40-ffffffff811e9db9: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fb3c0)
Location: mm/vmalloc.c:871
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff811fb3c0-ffffffff811fb439: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81206100)
Location: mm/vmalloc.c:922
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff81206100-ffffffff81206179: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121ee20)
Location: mm/vmalloc.c:920
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff8121ee20-ffffffff8121ee99: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812416f0)
Location: mm/vmalloc.c:903
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff812416f0-ffffffff81241769: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255df0)
Location: mm/vmalloc.c:903
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff81255df0-ffffffff81255e69: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81268f50)
Location: mm/vmalloc.c:1506
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff81268f50-ffffffff81268fce: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81277e80)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff81277e80-ffffffff81277efe: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a8d60)
Location: mm/vmalloc.c:1615
Inline: False
Direct callers:
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:purge_fragmented_blocks
```
**Symbols:**

```
ffffffff812a8d60-ffffffff812a8dde: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b41c0)
Location: mm/vmalloc.c:1608
Inline: True
Direct callers:
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:purge_fragmented_blocks
```
**Symbols:**

```
ffffffff812b41c0-ffffffff812b421d: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b98a0)
Location: mm/vmalloc.c:1878
Inline: True
Direct callers:
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:purge_fragmented_blocks
```
**Symbols:**

```
ffffffff812b98a0-ffffffff812b98fd: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fbe40)
Location: mm/vmalloc.c:1930
Inline: False
Direct callers:
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:purge_fragmented_blocks
```
**Symbols:**

```
ffffffff812fbe40-ffffffff812fbe9d: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81360ea0)
Location: mm/vmalloc.c:1949
Inline: True
Direct callers:
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff81360ea0-ffffffff81360f09: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813dc880)
Location: mm/vmalloc.c:2011
Inline: True
Direct callers:
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff813dc880-ffffffff813dc8e9: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81411250)
Location: mm/vmalloc.c:2078
Inline: False
Direct callers:
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
```
**Symbols:**

```
ffffffff81411250-ffffffff8141137d: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143da40)
Location: mm/vmalloc.c:2078
Inline: False
Direct callers:
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
```
**Symbols:**

```
ffffffff8143da40-ffffffff8143db6d: free_vmap_block (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030e450)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffff80001030e450-ffff80001030e52c: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0529e7c)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
c0529e7c-c0529f1c: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003df1e0)
Location: mm/vmalloc.c:1514
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
c0000000003df1e0-c0000000003df2d0: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000216ea2)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffe000216ea2-ffffffe000216f5c: free_vmap_block (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812704d0)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff812704d0-ffffffff8127054e: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262440)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff81262440-ffffffff812624be: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e270)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff8126e270-ffffffff8126e2ee: free_vmap_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_block(struct vmap_block *vb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127dc30)
Location: mm/vmalloc.c:1514
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
**Symbols:**

```
ffffffff8127dc30-ffffffff8127dcac: free_vmap_block (STB_LOCAL)
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
