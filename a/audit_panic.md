# Function: <code>audit_panic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81120b90)
Location: kernel/audit.c:199
Inline: True
Direct callers:
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_secctx
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81120b90-ffffffff81120bea: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81128ae0)
Location: kernel/audit.c:197
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81128ae0-ffffffff81128b3a: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81132740)
Location: kernel/audit.c:203
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81132740-ffffffff8113279a: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133ec0)
Location: kernel/audit.c:270
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_secctx
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81133ec0-ffffffff81133f10: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140c80)
Location: kernel/audit.c:270
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81140c80-ffffffff81140cd0: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:313
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8115244d-ffffffff81152470: audit_panic.cold.23 (STB_LOCAL)
ffffffff8114f650-ffffffff8114f689: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8115c348)
Location: kernel/audit.c:309
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8115f0f5-ffffffff8115f118: audit_panic.cold.23 (STB_LOCAL)
ffffffff8115c330-ffffffff8115c369: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81168a19)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8116b6e7-ffffffff8116b70a: audit_panic.cold (STB_LOCAL)
ffffffff81168a00-ffffffff81168a3b: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811748b9)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff811775c7-ffffffff811775ea: audit_panic.cold (STB_LOCAL)
ffffffff811748a0-ffffffff811748db: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81186929)
Location: kernel/audit.c:297
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8118a23b-ffffffff8118a25e: audit_panic.cold (STB_LOCAL)
ffffffff81186910-ffffffff8118694d: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81183c39)
Location: kernel/audit.c:302
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81be48c1-ffffffff81be48e4: audit_panic.cold (STB_LOCAL)
ffffffff81183c20-ffffffff81183c5d: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81184b69)
Location: kernel/audit.c:302
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81bd6722-ffffffff81bd6745: audit_panic.cold (STB_LOCAL)
ffffffff81184b50-ffffffff81184b8d: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811ace89)
Location: kernel/audit.c:302
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81cb345c-ffffffff81cb347f: audit_panic.cold (STB_LOCAL)
ffffffff811ace70-ffffffff811acead: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81e642a1)
Location: kernel/audit.c:304
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81e6428d-ffffffff81e642b0: audit_panic.cold (STB_LOCAL)
ffffffff811deaa0-ffffffff811deae6: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812246a0)
Location: kernel/audit.c:304
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff812246a0-ffffffff8122470b: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ac70)
Location: kernel/audit.c:304
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8123ac70-ffffffff8123acdb: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81254b30)
Location: kernel/audit.c:303
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_log_subject_context
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_lost
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81254b30-ffffffff81254b9b: audit_panic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e9388)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffff8000101e9388-ffff8000101e93f8: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c04292e4)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
c04292e4-c0429350: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025a130)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
c00000000025a130-c00000000025a1d4: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015e190)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffe00015e190-ffffffe00015e1fc: audit_panic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116ced9)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8116fbe7-ffffffff8116fc0a: audit_panic.cold (STB_LOCAL)
ffffffff8116cec0-ffffffff8116cefb: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81160079)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff81162d87-ffffffff81162daa: audit_panic.cold (STB_LOCAL)
ffffffff81160060-ffffffff8116009b: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116aca9)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8116d9b7-ffffffff8116d9da: audit_panic.cold (STB_LOCAL)
ffffffff8116ac90-ffffffff8116accb: audit_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_panic(const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81178499)
Location: kernel/audit.c:296
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_net_init
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/audit_watch.c:audit_watch_init
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_fsnotify_init
  - kernel/audit_tree.c:audit_tree_init
```
**Symbols:**

```
ffffffff8117b1a7-ffffffff8117b1ca: audit_panic.cold (STB_LOCAL)
ffffffff81178480-ffffffff811784bb: audit_panic (STB_GLOBAL)
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
