# Function: <code>dma_fence_is_signaled</code>

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
In drivers/dma-buf/dma-fence.c (ffffffff81629cc6)
Location: include/linux/dma-fence.h:325
Inline: True
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ad34)
Location: include/linux/dma-fence.h:325
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162b937)
Location: include/linux/dma-fence.h:325
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8162cbd4)
Location: include/linux/dma-fence.h:325
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
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
In drivers/dma-buf/dma-buf.c (ffffffff8163dfdf)
Location: include/linux/dma-fence.h:327
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163f64d)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/reservation.c (ffffffff81640434)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/dma-buf/sync_file.c (ffffffff8164139d)
Location: include/linux/dma-fence.h:327
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff816a6d5f)
Location: include/linux/dma-fence.h:330
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a81cd)
Location: include/linux/dma-fence.h:330
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/reservation.c (ffffffff816a944b)
Location: include/linux/dma-fence.h:330
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff816aa175)
Location: include/linux/dma-fence.h:330
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff816e2ff5)
Location: include/linux/dma-fence.h:402
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e44af)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/reservation.c (ffffffff816e54c7)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e66d1)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff81706385)
Location: include/linux/dma-fence.h:396
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817078f9)
Location: include/linux/dma-fence.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/reservation.c (ffffffff817084b5)
Location: include/linux/dma-fence.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff81709a5f)
Location: include/linux/dma-fence.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff81741472)
Location: include/linux/dma-fence.h:396
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81742b69)
Location: include/linux/dma-fence.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81743825)
Location: include/linux/dma-fence.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/reservation.c (ffffffff81744050)
Location: include/linux/dma-fence.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff81745255)
Location: include/linux/dma-fence.h:396
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff81765722)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81766b3c)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767826)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817681ae)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768c17)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff8182513a)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818271ec)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827e96)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818296f2)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182aaf7)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff81835b08)
Location: include/linux/dma-fence.h:429
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837c8c)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81838a76)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818393e3)
Location: include/linux/dma-fence.h:429
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b7b7)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff818191f8)
Location: include/linux/dma-fence.h:432
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181af6f)
Location: include/linux/dma-fence.h:432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181bd32)
Location: include/linux/dma-fence.h:432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c693)
Location: include/linux/dma-fence.h:432
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181e9d7)
Location: include/linux/dma-fence.h:432
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff818a36c7)
Location: include/linux/dma-fence.h:432
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a53ef)
Location: include/linux/dma-fence.h:432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a61c2)
Location: include/linux/dma-fence.h:432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6a5c)
Location: include/linux/dma-fence.h:432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a9067)
Location: include/linux/dma-fence.h:432
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-fence.c (ffffffff819ef245)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819f016c)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f0f58)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f2f95)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-fence.c (ffffffff81b6c785)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d7ec)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81b6de16)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6ec2b)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b70d05)
Location: include/linux/dma-fence.h:429
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-fence.c (ffffffff81bbf795)
Location: include/linux/dma-fence.h:449
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0f0c)
Location: include/linux/dma-fence.h:449
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc160c)
Location: include/linux/dma-fence.h:449
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc251b)
Location: include/linux/dma-fence.h:449
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc4535)
Location: include/linux/dma-fence.h:449
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-fence.c (ffffffff81c13f15)
Location: include/linux/dma-fence.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c1568c)
Location: include/linux/dma-fence.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15d97)
Location: include/linux/dma-fence.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16cab)
Location: include/linux/dma-fence.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c18c6d)
Location: include/linux/dma-fence.h:450
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb2232)
Location: include/linux/dma-fence.h:450
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
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
In drivers/dma-buf/dma-buf.c (ffff8000109658e4)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffff800010967314)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff8000109689c8)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffff800010969a40)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a00c)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (c0a3c540)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (c0a3dc5c)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3ebb4)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (c0a3f2d8)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (c0a40088)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (c000000000a1ccc0)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1ee7c)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a205c0)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (c000000000a21238)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (c000000000a22748)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffe0005d26ae)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d3ac0)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d462a)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d54fc)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d59f2)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff81719e12)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171b22c)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bf16)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c89e)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d307)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff816f3282)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f468c)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f5376)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5cfe)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f6767)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff81758be2)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81759ffc)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175ace6)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b66e)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c0d7)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff8177406a)
Location: include/linux/dma-fence.h:416
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817755bc)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817762c6)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81776928)
Location: include/linux/dma-fence.h:416
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
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
```
```
In drivers/dma-buf/sync_file.c (ffffffff81777777)
Location: include/linux/dma-fence.h:416
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
</details>
</li>
</ul>

## Differences
