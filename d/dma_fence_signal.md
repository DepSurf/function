# Function: <code>dma_fence_signal</code>

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
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81629740)
Location: drivers/dma-buf/dma-fence.c:109
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
```
**Symbols:**

```
ffffffff81629740-ffffffff81629851: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163f150)
Location: drivers/dma-buf/dma-fence.c:109
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff8163f150-ffffffff8163f255: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a7e80)
Location: drivers/dma-buf/dma-fence.c:108
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff816a7e80-ffffffff816a7f95: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e4160)
Location: drivers/dma-buf/dma-fence.c:108
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff816e4160-ffffffff816e4276: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff817075a0)
Location: drivers/dma-buf/dma-fence.c:180
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff817075a0-ffffffff817076b6: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81742800)
Location: drivers/dma-buf/dma-fence.c:173
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81742800-ffffffff81742906: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81765fc0)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81765fc0-ffffffff81766009: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81827217)
Location: drivers/dma-buf/dma-fence.c:169
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81826950-ffffffff81826999: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81837cb7)
Location: drivers/dma-buf/dma-fence.c:370
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81837460-ffffffff818374a9: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181af9a)
Location: drivers/dma-buf/dma-fence.c:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff8181a690-ffffffff8181a6e1: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a541a)
Location: drivers/dma-buf/dma-fence.c:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff818a4bd0-ffffffff818a4c21: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819ef2e6)
Location: drivers/dma-buf/dma-fence.c:452
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff819ee580-ffffffff819ee5d9: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c826)
Location: drivers/dma-buf/dma-fence.c:460
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81b6ba10-ffffffff81b6ba69: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf836)
Location: drivers/dma-buf/dma-fence.c:461
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81bbef30-ffffffff81bbef89: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c13fb6)
Location: drivers/dma-buf/dma-fence.c:461
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_poll
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion
```
**Symbols:**

```
ffffffff81c13680-ffffffff81c136d9: dma_fence_signal (STB_GLOBAL)
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
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff800010966bb0)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffff800010966bb0-ffff800010966c60: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3d03c)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
c0a3d03c-c0a3d090: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1dbe0)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
c000000000a1dbe0-c000000000a1dc5c: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2ef2)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffe0005d2ef2-ffffffe0005d2f44: dma_fence_signal (STB_GLOBAL)
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
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171a6b0)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff8171a6b0-ffffffff8171a6f9: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f3b10)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff816f3b10-ffffffff816f3b59: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81759480)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81759480-ffffffff817594c9: dma_fence_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_fence_signal(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81774980)
Location: drivers/dma-buf/dma-fence.c:169
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
**Symbols:**

```
ffffffff81774980-ffffffff817749c9: dma_fence_signal (STB_GLOBAL)
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
