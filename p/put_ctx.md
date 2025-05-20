# Function: <code>put_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b2d0)
Location: kernel/events/core.c:884
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_disable
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:orphans_remove_work
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff8117b2d0-ffffffff8117b322: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118cba0)
Location: kernel/events/core.c:1129
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8118cba0-ffffffff8118cbf7: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119c1e0)
Location: kernel/events/core.c:1137
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8119c1e0-ffffffff8119c237: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a3af0)
Location: kernel/events/core.c:1129
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811a3af0-ffffffff811a3b4a: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7cc0)
Location: kernel/events/core.c:1168
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811b7cc0-ffffffff811b7d18: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d7700)
Location: kernel/events/core.c:1191
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811d7700-ffffffff811d7756: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e7fe0)
Location: kernel/events/core.c:1191
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811e7fe0-ffffffff811e8036: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201f80)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81201f80-ffffffff81201fe3: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ee30)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8120ee30-ffffffff8120ee93: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234440)
Location: kernel/events/core.c:1254
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81234440-ffffffff812344e3: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ed70)
Location: kernel/events/core.c:1272
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8123ed70-ffffffff8123ee13: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242fa0)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81242fa0-ffffffff81243043: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127d7f0)
Location: kernel/events/core.c:1301
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8127d7f0-ffffffff8127d893: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d1e10)
Location: kernel/events/core.c:1210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff812d1e10-ffffffff812d1edc: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133ac10)
Location: kernel/events/core.c:1183
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8133ac10-ffffffff8133acdc: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136baf0)
Location: kernel/events/core.c:1183
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8136baf0-ffffffff8136bbbc: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81394cb0)
Location: kernel/events/core.c:1194
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_pmu_install_event
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81394cb0-ffffffff81394d7c: put_ctx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff800010293d50)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffff800010293d50-ffff800010293dcc: put_ctx.part.0 (STB_LOCAL)
ffff800010293dd0-ffff800010293e04: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c4d3c)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
c04c4d3c-c04c4dac: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003438b0)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
c0000000003438b0-c000000000343974: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4efc)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffe0001c4efc-ffffffe0001c4f6e: put_ctx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207450)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81207450-ffffffff812074b3: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa2f0)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811fa2f0-ffffffff811fa353: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81205220)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81205220-ffffffff81205283: put_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81214080)
Location: kernel/events/core.c:1192
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81214080-ffffffff812140e3: put_ctx (STB_LOCAL)
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
