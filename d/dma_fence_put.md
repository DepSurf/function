# Function: <code>dma_fence_put</code>

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
In drivers/dma-buf/dma-buf.c (ffffffff81628852)
Location: include/linux/dma-fence.h:192
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8162a426)
Location: include/linux/dma-fence.h:192
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/reservation.c (ffffffff8162acda)
Location: include/linux/dma-fence.h:192
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162b3fe)
Location: include/linux/dma-fence.h:192
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_free
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c488)
Location: include/linux/dma-fence.h:192
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff8163e4b5)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8163ffc9)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/reservation.c (ffffffff81640440)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81640b2a)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641a72)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff816a7468)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816a8859)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/reservation.c (ffffffff816a9457)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816a995d)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aad11)
Location: include/linux/dma-fence.h:194
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff816e353c)
Location: include/linux/dma-fence.h:262
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816e4bc9)
Location: include/linux/dma-fence.h:262
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/reservation.c (ffffffff816e54f6)
Location: include/linux/dma-fence.h:262
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e5e6d)
Location: include/linux/dma-fence.h:262
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e7202)
Location: include/linux/dma-fence.h:262
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff817068bc)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81707f39)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/reservation.c (ffffffff817084ed)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff8170928d)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a592)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81741a18)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff817431d9)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817436a9)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/reservation.c (ffffffff81744085)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744a40)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745e85)
Location: include/linux/dma-fence.h:256
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81765b9d)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81767149)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767678)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817681e7)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768cb0)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81769eb4)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81825e66)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81827666)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827a50)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8182973d)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182ab90)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182c0b9)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
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
In drivers/dma-buf/dma-buf.c (ffffffff81836862)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818380f6)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818384d0)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81839428)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b850)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183d119)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
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
In drivers/dma-buf/dma-buf.c (ffffffff81819a2a)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b3e3)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b7ad)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c6d4)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ea70)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818202df)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff818a429f)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_excl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a5853)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5c3d)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6a9b)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a9100)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa9af)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff819ed469)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef6bc)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efb94)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f10c6)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f306d)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f5052)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81b6a6e9)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6cc8c)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d1d4)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6eaa6)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b70dbd)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b72512)
Location: include/linux/dma-fence.h:273
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81bbdb39)
Location: include/linux/dma-fence.h:293
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc03cb)
Location: include/linux/dma-fence.h:293
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0900)
Location: include/linux/dma-fence.h:293
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2396)
Location: include/linux/dma-fence.h:293
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc45ed)
Location: include/linux/dma-fence.h:293
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5f16)
Location: include/linux/dma-fence.h:293
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
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
In drivers/dma-buf/dma-buf.c (ffffffff81c12289)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14b4b)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15080)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16b26)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_set_deadline
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_singleton
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c18d6d)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1aa20)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7d305)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c9730b)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
  - drivers/gpu/drm/drm_file.c:drm_event_cancel_free
  - drivers/gpu/drm/drm_file.c:drm_event_cancel_free
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb20a7)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func
  - drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_free
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_free
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
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
In drivers/gpu/drm/drm_writeback.c (ffffffff81cb897b)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_cleanup_job
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_cleanup_job
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc32d8)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (ffffffff81cc5ba8)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (ffffffff81ccb1a9)
Location: include/linux/dma-fence.h:294
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
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
In drivers/dma-buf/dma-buf.c (ffff800010965d7c)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010967eec)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff800010968788)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffff800010969a80)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffff800010969d48)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096ba5c)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (c0a3cae8)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e2c4)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3e7b4)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (c0a3f320)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (c0a3fe58)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (c0a413ec)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (c000000000a1d4c0)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f7d8)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fe70)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (c000000000a21274)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (c000000000a224d4)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (c000000000a24204)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffe0005d2a56)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d3d70)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d4180)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d551c)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5760)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d692a)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff8171a28d)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8171b839)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bd68)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c8d7)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d3a0)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e5a4)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff816f36f7)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816f4c99)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f51c8)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5d37)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f6800)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f79ee)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff8175905d)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8175a609)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175ab38)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b6a7)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c170)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175d374)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81774629)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81775bc9)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81776118)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81776961)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffff81777810)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778a09)
Location: include/linux/dma-fence.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
</details>
</li>
</ul>

## Differences
