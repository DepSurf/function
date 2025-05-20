# Function: <code>ww_mutex_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818223f0)
Location: kernel/locking/mutex.c:453
Inline: False
```
**Symbols:**

```
ffffffff818223f0-ffffffff8182242e: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8189c8a0)
Location: kernel/locking/mutex.c:453
Inline: False
```
**Symbols:**

```
ffffffff8189c8a0-ffffffff8189c8de: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d05a0)
Location: kernel/locking/mutex.c:577
Inline: False
```
**Symbols:**

```
ffffffff818d05a0-ffffffff818d05d0: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81907ae0)
Location: kernel/locking/mutex.c:629
Inline: False
```
**Symbols:**

```
ffffffff81907ae0-ffffffff81907b10: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81991bd0)
Location: kernel/locking/mutex.c:629
Inline: False
```
**Symbols:**

```
ffffffff81991bd0-ffffffff81991c00: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee240)
Location: kernel/locking/mutex.c:630
Inline: False
```
**Symbols:**

```
ffffffff819ee240-ffffffff819ee270: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a294b0)
Location: kernel/locking/mutex.c:728
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffff81a294b0-ffffffff81a294e0: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a99b40)
Location: kernel/locking/mutex.c:729
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffff81a99b40-ffffffff81a99b70: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad1490)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffff81ad1490-ffffffff81ad14c0: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bc9670)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81bc9670-ffffffff81bc96b9: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c42490)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81c42490-ffffffff81c424d9: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c34400)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81c34400-ffffffff81c34449: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d52cf0)
Location: kernel/locking/mutex.c:551
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff81d52cf0-ffffffff81d52d33: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81f23610)
Location: kernel/locking/mutex.c:558
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff81f23610-ffffffff81f23667: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff820cead0)
Location: kernel/locking/mutex.c:558
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
```
**Symbols:**

```
ffffffff820cead0-ffffffff820ceb27: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82152f70)
Location: kernel/locking/mutex.c:558
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
```
**Symbols:**

```
ffffffff82152f70-ffffffff82152fc7: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82235db0)
Location: kernel/locking/mutex.c:563
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_unlock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_unlock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_unlock_reservations
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
  - drivers/gpu/drm/drm_gem.c:drm_gem_vunmap_unlocked
  - drivers/gpu/drm/drm_gem.c:drm_gem_vmap_unlocked
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_unlock_all
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_close
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_open
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_fault
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_unpin
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_object_pin
```
**Symbols:**

```
ffffffff82235db0-ffffffff82235e07: ww_mutex_unlock (STB_GLOBAL)
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
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da2fb8)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffff800010da2fb8-ffff800010da3004: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9b62c)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
c0e9b62c-c0e9b66c: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5270)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
c000000000ee5270-c000000000ee52ac: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c6b9c)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffe0008c6b9c-ffffffe0008c6bd8: ww_mutex_unlock (STB_GLOBAL)
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
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a70300)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffff81a70300-ffffffff81a70330: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2c6f0)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffff81a2c6f0-ffffffff81a2c720: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81adc710)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffff81adc710-ffffffff81adc740: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ww_mutex_unlock(struct ww_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae8b00)
Location: kernel/locking/mutex.c:755
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unlock
```
**Symbols:**

```
ffffffff81ae8b00-ffffffff81ae8b30: ww_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
