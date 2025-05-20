# Function: <code>dma_fence_init</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, unsigned int seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81628f70)
Location: drivers/dma-buf/dma-fence.c:530
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81628f70-ffffffff81629026: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, unsigned int seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163ebd0)
Location: drivers/dma-buf/dma-fence.c:559
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8163ebd0-ffffffff8163ec98: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, unsigned int seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a79d0)
Location: drivers/dma-buf/dma-fence.c:558
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816a79d0-ffffffff816a7a9d: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, unsigned int seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e3ab0)
Location: drivers/dma-buf/dma-fence.c:559
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816e3ab0-ffffffff816e3b7d: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, unsigned int seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81706d60)
Location: drivers/dma-buf/dma-fence.c:651
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81706d60-ffffffff81706e17: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81741ec0)
Location: drivers/dma-buf/dma-fence.c:661
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81741ec0-ffffffff81741f78: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff817667a0)
Location: drivers/dma-buf/dma-fence.c:646
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff817667a0-ffffffff81766858: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81827000)
Location: drivers/dma-buf/dma-fence.c:638
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
**Symbols:**

```
ffffffff81827000-ffffffff818270b8: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81837ac0)
Location: drivers/dma-buf/dma-fence.c:848
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
**Symbols:**

```
ffffffff81837ac0-ffffffff81837b52: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181a6f0)
Location: drivers/dma-buf/dma-fence.c:929
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
**Symbols:**

```
ffffffff8181a6f0-ffffffff8181a782: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a49d0)
Location: drivers/dma-buf/dma-fence.c:929
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
**Symbols:**

```
ffffffff818a49d0-ffffffff818a4a5b: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819ee5e0)
Location: drivers/dma-buf/dma-fence.c:943
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
**Symbols:**

```
ffffffff819ee5e0-ffffffff819ee6d5: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6ba80)
Location: drivers/dma-buf/dma-fence.c:947
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
**Symbols:**

```
ffffffff81b6ba80-ffffffff81b6bb75: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf30f)
Location: drivers/dma-buf/dma-fence.c:1007
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
**Symbols:**

```
ffffffff81bbefa0-ffffffff81bbf095: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c13a8e)
Location: drivers/dma-buf/dma-fence.c:1008
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/gpu/drm/drm_crtc.c:drm_crtc_create_fence
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_get_out_fence
```
**Symbols:**

```
ffffffff81c136f0-ffffffff81c137e5: dma_fence_init (STB_GLOBAL)
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
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff8000109663b8)
Location: drivers/dma-buf/dma-fence.c:646
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffff8000109663b8-ffff8000109664b8: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3d2d8)
Location: drivers/dma-buf/dma-fence.c:646
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
c0a3d2d8-c0a3d3d4: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1dfc0)
Location: drivers/dma-buf/dma-fence.c:646
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
c000000000a1dfc0-c000000000a1e0e0: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d35a0)
Location: drivers/dma-buf/dma-fence.c:646
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffe0005d35a0-ffffffe0005d366a: dma_fence_init (STB_GLOBAL)
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
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171ae90)
Location: drivers/dma-buf/dma-fence.c:646
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8171ae90-ffffffff8171af48: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f42f0)
Location: drivers/dma-buf/dma-fence.c:646
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816f42f0-ffffffff816f43a8: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81759c60)
Location: drivers/dma-buf/dma-fence.c:646
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81759c60-ffffffff81759d18: dma_fence_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dma_fence_init(struct dma_fence *fence, const struct dma_fence_ops *ops, spinlock_t *lock, u64 context, u64 seqno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff817751d0)
Location: drivers/dma-buf/dma-fence.c:646
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff817751d0-ffffffff8177529a: dma_fence_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int seqno</code> ➡️ <code>u64 seqno</code>
</li>
</ul>
</details>
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
