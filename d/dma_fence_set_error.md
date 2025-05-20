# Function: <code>dma_fence_set_error</code>

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
In drivers/dma-buf/sw_sync.c (ffffffff816aa9fe)
Location: include/linux/dma-fence.h:434
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffff816e6fab)
Location: include/linux/dma-fence.h:506
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8170a26b)
Location: include/linux/dma-fence.h:500
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81745ab2)
Location: include/linux/dma-fence.h:509
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81769ccc)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8182baac)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8183cc6c)
Location: include/linux/dma-fence.h:542
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8182008c)
Location: include/linux/dma-fence.h:545
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffff818aa74c)
Location: include/linux/dma-fence.h:545
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff819f485c)
Location: include/linux/dma-fence.h:542
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81b71d7c)
Location: include/linux/dma-fence.h:542
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81bc54cc)
Location: include/linux/dma-fence.h:562
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffff81c1a02c)
Location: include/linux/dma-fence.h:578
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
```
In drivers/gpu/drm/drm_writeback.c (ffffffff81cb8a10)
Location: include/linux/dma-fence.h:578
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion
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
In drivers/dma-buf/sw_sync.c (ffff80001096b288)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (c0a411c8)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (c000000000a23b30)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
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
In drivers/dma-buf/sw_sync.c (ffffffe0005d65e6)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8171e3bc)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816f781c)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8175d18c)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8177883c)
Location: include/linux/dma-fence.h:529
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
```
</details>
</li>
</ul>

## Differences
