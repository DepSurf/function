# Function: <code>dma_fence_get_rcu_safe</code>

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
In drivers/dma-buf/reservation.c (ffffffff816a8d9d)
Location: include/linux/dma-fence.h:245
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
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
In drivers/dma-buf/reservation.c (ffffffff816e5370)
Location: include/linux/dma-fence.h:313
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
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
In drivers/dma-buf/reservation.c (ffffffff81708ddf)
Location: include/linux/dma-fence.h:307
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff817434c7)
Location: include/linux/dma-fence.h:307
Inline: True
```
```
In drivers/dma-buf/reservation.c (ffffffff81744764)
Location: include/linux/dma-fence.h:307
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767469)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176894c)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827b26)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818288ab)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff8183859b)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8183a016)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b87b)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181d256)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5d0b)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a76a6)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efc80)
Location: include/linux/dma-fence.h:324
Inline: True
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d2d0)
Location: include/linux/dma-fence.h:324
Inline: True
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0a00)
Location: include/linux/dma-fence.h:344
Inline: True
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15180)
Location: include/linux/dma-fence.h:345
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1fd2)
Location: include/linux/dma-fence.h:345
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
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
In drivers/dma-buf/dma-fence-chain.c (ffff800010968508)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (c0a3e85c)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (c000000000a20000)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (c000000000a21ed4)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d439e)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4ef4)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bb59)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171d03c)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4fb9)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f649c)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a929)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175be0c)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775eee)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817774a2)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
</details>
</li>
</ul>

## Differences
