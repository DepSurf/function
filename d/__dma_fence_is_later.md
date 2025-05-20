# Function: <code>__dma_fence_is_later</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816aa8f9)
Location: include/linux/dma-fence.h:351
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816e6ea5)
Location: include/linux/dma-fence.h:423
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8170a165)
Location: include/linux/dma-fence.h:417
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817433c4)
Location: include/linux/dma-fence.h:418
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744d1f)
Location: include/linux/dma-fence.h:418
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817459f3)
Location: include/linux/dma-fence.h:418
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767361)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768ed2)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81769b6f)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827903)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182af3a)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bd3a)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818383ab)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183bbea)
Location: include/linux/dma-fence.h:451
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183cdaa)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b688)
Location: include/linux/dma-fence.h:454
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ee04)
Location: include/linux/dma-fence.h:454
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818201ca)
Location: include/linux/dma-fence.h:454
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5ad2)
Location: include/linux/dma-fence.h:454
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a94dd)
Location: include/linux/dma-fence.h:454
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa88c)
Location: include/linux/dma-fence.h:454
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819ef9b8)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f37a9)
Location: include/linux/dma-fence.h:451
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4787)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6cfd8)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81b6de72)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6eca0)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71bb7)
Location: include/linux/dma-fence.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0708)
Location: include/linux/dma-fence.h:471
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc1668)
Location: include/linux/dma-fence.h:471
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2590)
Location: include/linux/dma-fence.h:471
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc57e7)
Location: include/linux/dma-fence.h:471
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c14e88)
Location: include/linux/dma-fence.h:472
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15df3)
Location: include/linux/dma-fence.h:472
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16d25)
Location: include/linux/dma-fence.h:472
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a1c7)
Location: include/linux/dma-fence.h:472
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffff8000109683d4)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a280)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b3d0)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (c0a3e64c)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (c0a402d0)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (c0a4103c)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fbdc)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (c000000000a22bbc)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (c000000000a23e40)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d42cc)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5b92)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d66ec)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171ba51)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d5c2)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e25f)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4eb1)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f6a22)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f757f)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a821)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c392)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175d02f)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775de1)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sync_file.c (ffffffff81777a32)
Location: include/linux/dma-fence.h:438
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8177845f)
Location: include/linux/dma-fence.h:438
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
</details>
</li>
</ul>

## Differences
