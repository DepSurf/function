# Function: <code>__xa_store</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18b20)
Location: lib/xarray.c:1351
Inline: False
Direct callers:
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81a18b20-ffffffff81a18c43: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88830)
Location: lib/xarray.c:1369
Inline: False
Direct callers:
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81a88830-ffffffff81a88953: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abfad0)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81abfad0-ffffffff81abfbf3: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fc080)
Location: lib/xarray.c:1382
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff815fc080-ffffffff815fc1a3: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620ca0)
Location: lib/xarray.c:1532
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81620ca0-ffffffff81620dc3: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604680)
Location: lib/xarray.c:1533
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81604680-ffffffff816047a3: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81672f70)
Location: lib/xarray.c:1533
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81672f70-ffffffff81673093: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178d570)
Location: lib/xarray.c:1540
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - security/apparmor/secid.c:aa_secid_update
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff8178d570-ffffffff8178d69b: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204abd0)
Location: lib/xarray.c:1540
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - security/apparmor/secid.c:aa_secid_update
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff8204abd0-ffffffff8204acfb: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c94d0)
Location: lib/xarray.c:1538
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - security/apparmor/secid.c:aa_secid_update
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:__devlink_region_snapshot_create
  - net/devlink/leftover.c:__devlink_snapshot_id_decrement
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff820c94d0-ffffffff820c95f9: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3e50)
Location: lib/xarray.c:1538
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - security/apparmor/secid.c:aa_secid_update
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:__devlink_region_snapshot_create
  - net/devlink/region.c:__devlink_snapshot_id_decrement
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff821a3e50-ffffffff821a3f79: __xa_store (STB_GLOBAL)
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
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b3c8)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffff800010d9b3c8-ffff800010d9b4f0: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97a7c)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - lib/xarray.c:xa_store
```
**Symbols:**

```
c0e97a7c-c0e97bec: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee15e0)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
c000000000ee15e0-c000000000ee1788: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c36ea)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffe0008c36ea-ffffffe0008c37e2: __xa_store (STB_GLOBAL)
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
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5e920)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81a5e920-ffffffff81a5ea43: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1b9f0)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81a1b9f0-ffffffff81a1bb13: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acad10)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81acad10-ffffffff81acae33: __xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad7320)
Location: lib/xarray.c:1380
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - lib/xarray.c:xa_store
```
**Symbols:**

```
ffffffff81ad7320-ffffffff81ad7443: __xa_store (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
