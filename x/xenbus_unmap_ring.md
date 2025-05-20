# Function: <code>xenbus_unmap_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cb230)
Location: drivers/xen/xenbus/xenbus_client.c:886
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff814cb230-ffffffff814cb39b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151be10)
Location: drivers/xen/xenbus/xenbus_client.c:886
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8151be10-ffffffff8151bf89: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815482e0)
Location: drivers/xen/xenbus/xenbus_client.c:886
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815482e0-ffffffff81548459: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c5fd)
Location: drivers/xen/xenbus/xenbus_client.c:867
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8155c3b0-ffffffff8155c50c: xenbus_unmap_ring.part.3 (STB_LOCAL)
ffffffff8155c510-ffffffff8155c52b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c0906)
Location: drivers/xen/xenbus/xenbus_client.c:874
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815c06c0-ffffffff815c081c: xenbus_unmap_ring.part.3 (STB_LOCAL)
ffffffff815c0820-ffffffff815c083b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f9b7d)
Location: drivers/xen/xenbus/xenbus_client.c:874
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815f8b10-ffffffff815f8c6d: xenbus_unmap_ring.part.4 (STB_LOCAL)
ffffffff815f8c70-ffffffff815f8c8b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614c3d)
Location: drivers/xen/xenbus/xenbus_client.c:872
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81613bc0-ffffffff81613d1d: xenbus_unmap_ring.part.4 (STB_LOCAL)
ffffffff81613d20-ffffffff81613d3b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8164893f)
Location: drivers/xen/xenbus/xenbus_client.c:872
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81647910-ffffffff81647a60: xenbus_unmap_ring.part.0 (STB_LOCAL)
ffffffff81647a60-ffffffff81647a7b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166addf)
Location: drivers/xen/xenbus/xenbus_client.c:872
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81669db0-ffffffff81669f00: xenbus_unmap_ring.part.0 (STB_LOCAL)
ffffffff81669f00-ffffffff81669f1b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ad5f)
Location: drivers/xen/xenbus/xenbus_client.c:567
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff8171a0a0-ffffffff8171a1dd: xenbus_unmap_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737ecf)
Location: drivers/xen/xenbus/xenbus_client.c:570
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff817371e0-ffffffff8173731d: xenbus_unmap_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ba3f)
Location: drivers/xen/xenbus/xenbus_client.c:570
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff8171ace0-ffffffff8171ae23: xenbus_unmap_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a66f)
Location: drivers/xen/xenbus/xenbus_client.c:567
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81799560-ffffffff817997fb: xenbus_unmap_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3480)
Location: drivers/xen/xenbus/xenbus_client.c:609
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff818d3480-ffffffff818d373d: xenbus_unmap_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a25620)
Location: drivers/xen/xenbus/xenbus_client.c:612
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81a25620-ffffffff81a258dd: xenbus_unmap_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6ebd0)
Location: drivers/xen/xenbus/xenbus_client.c:612
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81a6ebd0-ffffffff81a6ee8d: xenbus_unmap_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac0b90)
Location: drivers/xen/xenbus/xenbus_client.c:623
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81ac0b90-ffffffff81ac0e4d: xenbus_unmap_ring (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108356b4)
Location: drivers/xen/xenbus/xenbus_client.c:872
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffff800010834648-ffff8000108347c0: xenbus_unmap_ring.part.0 (STB_LOCAL)
ffff8000108347c0-ffff80001083481c: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630c4f)
Location: drivers/xen/xenbus/xenbus_client.c:872
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8162fc20-ffffffff8162fd70: xenbus_unmap_ring.part.0 (STB_LOCAL)
ffffffff8162fd70-ffffffff8162fd8b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165ec1f)
Location: drivers/xen/xenbus/xenbus_client.c:872
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8165dbf0-ffffffff8165dd40: xenbus_unmap_ring.part.0 (STB_LOCAL)
ffffffff8165dd40-ffffffff8165dd5b: xenbus_unmap_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_unmap_ring(struct xenbus_device *dev, grant_handle_t *handles, unsigned int nr_handles, long unsigned int *vaddrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8167863a)
Location: drivers/xen/xenbus/xenbus_client.c:872
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff816783c0-ffffffff81678510: xenbus_unmap_ring.part.0 (STB_LOCAL)
ffffffff81678510-ffffffff8167852b: xenbus_unmap_ring (STB_GLOBAL)
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
