# Function: <code>dma_fence_is_later</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81b6de66)
Location: include/linux/dma-fence.h:472
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6ec94)
Location: include/linux/dma-fence.h:472
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
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
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc165c)
Location: include/linux/dma-fence.h:492
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2584)
Location: include/linux/dma-fence.h:492
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
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
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15de7)
Location: include/linux/dma-fence.h:493
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16d19)
Location: include/linux/dma-fence.h:493
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
