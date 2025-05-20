# Function: <code>dma_fence_get</code>

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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff8162a4c9)
Location: include/linux/dma-fence.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ab72)
Location: include/linux/dma-fence.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162bc81)
Location: include/linux/dma-fence.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81640031)
Location: include/linux/dma-fence.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff81640307)
Location: include/linux/dma-fence.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81640bb8)
Location: include/linux/dma-fence.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff816a88d5)
Location: include/linux/dma-fence.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff816a8cb7)
Location: include/linux/dma-fence.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816a9b18)
Location: include/linux/dma-fence.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff816e4aa6)
Location: include/linux/dma-fence.h:274
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff816e4d37)
Location: include/linux/dma-fence.h:274
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e6048)
Location: include/linux/dma-fence.h:274
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8170755d)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81708006)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff81708e77)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff817093d8)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff817427bd)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff817432a6)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817437f5)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff8174440f)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744b99)
Location: include/linux/dma-fence.h:268
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff8176688d)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff817671d7)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817677f5)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176859f)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768d49)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff818270ed)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8182772c)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827e45)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81828f2e)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182ad33)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff81837b8d)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818381bc)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81838a25)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8183958e)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b8e3)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff8181a8bd)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b499)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181bce5)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c81e)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ec03)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-buf.c (ffffffff818a41fb)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_excl
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_excl
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4d5d)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a5909)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a6175)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6c5e)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a9293)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-buf.c (ffffffff819ed438)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee70b)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef82e)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819f0125)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f145e)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f3dcf)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-buf.c (ffffffff81b6a498)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6bddb)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6ce1e)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d7a5)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81b6dedb)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6f0be)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b710b1)
Location: include/linux/dma-fence.h:285
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-buf.c (ffffffff81bbd8e8)
Location: include/linux/dma-fence.h:305
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf49b)
Location: include/linux/dma-fence.h:305
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc0556)
Location: include/linux/dma-fence.h:305
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0fd5)
Location: include/linux/dma-fence.h:305
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc16d1)
Location: include/linux/dma-fence.h:305
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc298e)
Location: include/linux/dma-fence.h:305
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc48e4)
Location: include/linux/dma-fence.h:305
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5768)
Location: include/linux/dma-fence.h:305
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
In drivers/dma-buf/dma-buf.c (ffffffff81c12038)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13c1b)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14cd6)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15755)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15e5c)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c1711e)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c19094)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a148)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb206b)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_replace_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_replace_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fence_add_wait
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fence_add_wait
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (ffffffff81ccb08c)
Location: include/linux/dma-fence.h:306
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
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
In drivers/dma-buf/dma-fence.c (ffff800010966984)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010967fb4)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff8000109689b0)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffff8000109694c8)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffff800010969f5c)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (c0a3d420)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e440)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3eb9c)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (c0a3f104)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (c0a40018)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (c000000000a1e158)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f8f0)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a20588)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (c000000000a20f18)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (c000000000a22630)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffe0005d36d4)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d402a)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d4616)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d48cc)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5820)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff8171af7d)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8171b8c7)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bee5)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171cc8f)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d439)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff816f43dd)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816f4d27)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f5345)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f60ef)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f6899)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff81759d4d)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8175a697)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175acb5)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175ba5f)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c209)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
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
In drivers/dma-buf/dma-fence.c (ffffffff817752cb)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81775c57)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81776295)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81776d2f)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff817778a9)
Location: include/linux/dma-fence.h:288
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
</details>
</li>
</ul>

## Differences
