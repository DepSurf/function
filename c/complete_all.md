# Function: <code>complete_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810c3b10)
Location: kernel/sched/completion.c:49
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff810c3b10-ffffffff810c3b59: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810c7800)
Location: kernel/sched/completion.c:49
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff810c7800-ffffffff810c7849: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810cd6c0)
Location: kernel/sched/completion.c:49
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810cd6c0-ffffffff810cd709: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ca0f0)
Location: kernel/sched/completion.c:51
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ca0f0-ffffffff810ca139: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810d1900)
Location: kernel/sched/completion.c:60
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810d1900-ffffffff810d1949: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810d9ec0)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_parkme
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810d9ec0-ffffffff810d9f09: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810e3a10)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810e3a10-ffffffff810e3a59: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ea620)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ea620-ffffffff810ea667: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810f5ff0)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810f5ff0-ffffffff810f6037: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ff880)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ff880-ffffffff810ff8c0: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810fe390)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810fe390-ffffffff810fe3d0: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81100770)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff81100770-ffffffff811007b0: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff8111c7d0)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff8111c7d0-ffffffff8111c810: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81140d30)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff81140d30-ffffffff81140dc4: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116bbb0)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff8116bbb0-ffffffff8116bc44: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117c630)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff8117c630-ffffffff8117c6c4: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a430)
Location: kernel/sched/completion.c:67
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_cleanup_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_cleanup_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_flip_done
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff8118a430-ffffffff8118a4cb: complete_all (STB_GLOBAL)
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
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffff8000101599b8)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffff8000101599b8-ffff800010159a74: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c03a6acc)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
c03a6acc-c03a6b1c: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c0000000001adde0)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
c0000000001adde0-c0000000001ade68: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffe0000ff720)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffe0000ff720-ffffffe0000ff776: complete_all (STB_GLOBAL)
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
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ef3f0)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ef3f0-ffffffff810ef437: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810df460)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff810df460-ffffffff810df4a7: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ec520)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810ec520-ffffffff810ec567: complete_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void complete_all(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810f7560)
Location: kernel/sched/completion.c:57
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algboss.c:cryptomgr_probe
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_pm_remove
  - drivers/base/power/main.c:device_pm_sleep_init
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_request_done
```
**Symbols:**

```
ffffffff810f7560-ffffffff810f75a7: complete_all (STB_GLOBAL)
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
