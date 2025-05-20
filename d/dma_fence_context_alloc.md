# Function: <code>dma_fence_context_alloc</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816294c0)
Location: drivers/dma-buf/dma-fence.c:47
Inline: True
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff816294c0-ffffffff816294dc: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163f090)
Location: drivers/dma-buf/dma-fence.c:49
Inline: True
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8163f090-ffffffff8163f0ac: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a77e0)
Location: drivers/dma-buf/dma-fence.c:48
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff816a77e0-ffffffff816a77fe: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e37e0)
Location: drivers/dma-buf/dma-fence.c:48
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff816e37e0-ffffffff816e37fe: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81706b80)
Location: drivers/dma-buf/dma-fence.c:113
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81706b80-ffffffff81706b9e: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence.c (0)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81742f6d-ffffffff81742f80: dma_fence_context_alloc.cold (STB_LOCAL)
ffffffff81741e50-ffffffff81741e72: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81765ea0)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81765ea0-ffffffff81765ebe: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818267f0)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
**Symbols:**

```
ffffffff818267f0-ffffffff8182680e: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81837310)
Location: drivers/dma-buf/dma-fence.c:152
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
**Symbols:**

```
ffffffff81837310-ffffffff8183732e: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181a4c0)
Location: drivers/dma-buf/dma-fence.c:177
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8181a4c0-ffffffff8181a4de: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a4970)
Location: drivers/dma-buf/dma-fence.c:177
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff818a4970-ffffffff818a498e: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819ee130)
Location: drivers/dma-buf/dma-fence.c:178
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff819ee130-ffffffff819ee154: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6b530)
Location: drivers/dma-buf/dma-fence.c:186
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81b6b530-ffffffff81b6b554: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbe990)
Location: drivers/dma-buf/dma-fence.c:187
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
**Symbols:**

```
ffffffff81bbe990-ffffffff81bbe9b4: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c130e0)
Location: drivers/dma-buf/dma-fence.c:187
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder
```
**Symbols:**

```
ffffffff81c130e0-ffffffff81c13104: dma_fence_context_alloc (STB_GLOBAL)
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
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff800010966738)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffff800010966738-ffff8000109667a8: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3ce58)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
c0a3ce58-c0a3ced0: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1d8e0)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
c000000000a1d8e0-c000000000a1d928: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2dd0)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffe0005d2dd0-ffffffe0005d2e06: dma_fence_context_alloc (STB_GLOBAL)
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
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171a590)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8171a590-ffffffff8171a5ae: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f39f0)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff816f39f0-ffffffff816f3a0e: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81759360)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81759360-ffffffff8175937e: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81774840)
Location: drivers/dma-buf/dma-fence.c:106
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81774840-ffffffff8177485e: dma_fence_context_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
