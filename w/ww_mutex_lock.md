# Function: <code>ww_mutex_lock</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81907950)
Location: kernel/locking/mutex.c:1190
Inline: True
```
**Symbols:**

```
ffffffff81907950-ffffffff8190798e: ww_mutex_lock.part.4 (STB_LOCAL)
ffffffff81908870-ffffffff819088d9: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81991a40)
Location: kernel/locking/mutex.c:1190
Inline: True
```
**Symbols:**

```
ffffffff81991a40-ffffffff81991a7e: ww_mutex_lock.part.4 (STB_LOCAL)
ffffffff81992910-ffffffff8199297c: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee270)
Location: kernel/locking/mutex.c:1214
Inline: True
```
**Symbols:**

```
ffffffff819ee270-ffffffff819ee2cd: ww_mutex_lock.part.7 (STB_LOCAL)
ffffffff819ee950-ffffffff819ee993: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a294e0)
Location: kernel/locking/mutex.c:1392
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81a294e0-ffffffff81a2953d: ww_mutex_lock.part.12 (STB_LOCAL)
ffffffff81a29cb0-ffffffff81a29cf3: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a9a380)
Location: kernel/locking/mutex.c:1402
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81a9a380-ffffffff81a9a40d: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad1cd0)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81ad1cd0-ffffffff81ad1d5d: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bc9f00)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81bc9f00-ffffffff81bc9f8b: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c42d50)
Location: kernel/locking/mutex.c:1431
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:destroy_regulator
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81c42d50-ffffffff81c42ddb: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c353b0)
Location: kernel/locking/mutex.c:1429
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
**Symbols:**

```
ffffffff81c353b0-ffffffff81c3543b: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d53bb0)
Location: kernel/locking/mutex.c:1041
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff81d53bb0-ffffffff81d53c3b: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81f24270)
Location: kernel/locking/mutex.c:1097
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
**Symbols:**

```
ffffffff81f24270-ffffffff81f24307: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff820cf780)
Location: kernel/locking/mutex.c:1097
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
```
**Symbols:**

```
ffffffff820cf780-ffffffff820cf817: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff821544f0)
Location: kernel/locking/mutex.c:1097
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
```
**Symbols:**

```
ffffffff821544f0-ffffffff82154587: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82237330)
Location: kernel/locking/mutex.c:1102
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
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
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/gpu/drm/drm_gem.c:drm_gem_vunmap_unlocked
  - drivers/gpu/drm/drm_gem.c:drm_gem_vmap_unlocked
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_backoff
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_close
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_open
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_fault
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_unpin
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free
```
**Symbols:**

```
ffffffff82237330-ffffffff822373c7: ww_mutex_lock (STB_GLOBAL)
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
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da40e8)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffff800010da40e8-ffff800010da41ec: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9c0dc)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
c0e9c0dc-c0e9c1ac: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee69f0)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
c000000000ee69f0-c000000000ee6b14: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c76ac)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffe0008c76ac-ffffffe0008c777e: ww_mutex_lock (STB_GLOBAL)
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
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a70b40)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81a70b40-ffffffff81a70bcd: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2cf30)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81a2cf30-ffffffff81a2cfbd: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81adcf50)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81adcf50-ffffffff81adcfdd: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae9a80)
Location: kernel/locking/mutex.c:1428
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81ae9a80-ffffffff81ae9b03: ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
