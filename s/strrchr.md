# Function: <code>strrchr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1a20)
Location: lib/string.c:403
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff813f1a20-ffffffff813f1a3a: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814383e0)
Location: lib/string.c:403
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff814383e0-ffffffff814383fa: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814553d0)
Location: lib/string.c:403
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff814553d0-ffffffff814553ea: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f6e90)
Location: lib/string.c:403
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/security.c:security_setprocattr
  - security/security.c:security_add_hooks
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff818f6e90-ffffffff818f6eaa: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197d890)
Location: lib/string.c:404
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/security.c:security_add_hooks
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff8197d890-ffffffff8197d8aa: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9d90)
Location: lib/string.c:404
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/security.c:security_add_hooks
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff819d9d90-ffffffff819d9da5: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a11fb0)
Location: lib/string.c:405
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/security.c:security_add_hooks
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a11fb0-ffffffff81a11fc5: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81470)
Location: lib/string.c:441
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/security.c:security_add_hooks
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a81470-ffffffff81a81489: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8540)
Location: lib/string.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81ab8540-ffffffff81ab8559: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3180)
Location: lib/string.c:484
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_transition_type
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_init_queue
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff815f3180-ffffffff815f3199: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617830)
Location: lib/string.c:481
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_transition_type
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/auxiliary.c:auxiliary_match_id
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_init_queue
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81617830-ffffffff81617849: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815faeb0)
Location: lib/string.c:481
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/auxiliary.c:auxiliary_match_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff815faeb0-ffffffff815faec9: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668760)
Location: lib/string.c:482
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/auxiliary.c:auxiliary_match_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81668760-ffffffff81668779: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81781dc0)
Location: lib/string.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/auxiliary.c:auxiliary_match_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81781dc0-ffffffff81781de2: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203eb70)
Location: lib/string.c:378
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/auxiliary.c:auxiliary_match_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff8203eb70-ffffffff8203eb92: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bd080)
Location: lib/string.c:378
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/auxiliary.c:auxiliary_match_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff820bd080-ffffffff820bd0a2: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82197980)
Location: lib/string.c:363
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:begin_new_exec
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_change
  - drivers/pci/pci.c:pci_dev_str_match_path
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/auxiliary.c:auxiliary_match_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff82197980-ffffffff821979a2: strrchr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - lib/fdt_ro.c:fdt_get_name
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_node_name_prefix
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/of_reserved_mem.c:of_reserved_mem_lookup
  - drivers/of/resolver.c:adjust_local_phandle_references
  - drivers/of/resolver.c:adjust_local_phandle_references
  - lib/fdt_ro.c:fdt_get_name
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
```
**Symbols:**

```
ffff800010d8344c-ffff800010d83474: strrchr (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/clk/ti/adpll.c:ti_adpll_setup_clock
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/firmware/dmi_scan.c:dmi_get_date
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_node_name_prefix
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/platform.c:of_device_make_bus_id
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/of_reserved_mem.c:of_reserved_mem_lookup
  - drivers/of/resolver.c:adjust_local_phandle_references
  - drivers/of/resolver.c:adjust_local_phandle_references
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - lib/fdt_ro.c:fdt_get_name
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
```
**Symbols:**

```
c0e7e920-c0e7e940: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed68c0)
Location: lib/string.c:443
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/of_helpers.c:pseries_of_derive_parent
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_node_name_prefix
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/of_reserved_mem.c:of_reserved_mem_lookup
  - drivers/of/resolver.c:adjust_local_phandle_references
  - drivers/of/resolver.c:adjust_local_phandle_references
  - lib/fdt_ro.c:fdt_get_name
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
```
**Symbols:**

```
c000000000ed68c0-c000000000ed68f4: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bca90)
Location: lib/string.c:443
Inline: False
Direct callers:
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/of/base.c:__of_find_node_by_path
  - drivers/of/base.c:of_node_name_prefix
  - drivers/of/base.c:of_node_name_eq
  - drivers/of/platform.c:of_device_alloc
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - drivers/of/fdt.c:of_scan_flat_dt_subnodes
  - drivers/of/fdt.c:of_scan_flat_dt
  - drivers/of/of_reserved_mem.c:of_reserved_mem_lookup
  - drivers/of/resolver.c:adjust_local_phandle_references
  - drivers/of/resolver.c:adjust_local_phandle_references
  - lib/fdt_ro.c:fdt_get_name
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
```
**Symbols:**

```
ffffffe0008bca90-ffffffe0008bcab2: strrchr (STB_GLOBAL)
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
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57390)
Location: lib/string.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a57390-ffffffff81a573a9: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14470)
Location: lib/string.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/usb/core/file.c:usb_register_dev
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81a14470-ffffffff81a14489: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3780)
Location: lib/string.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81ac3780-ffffffff81ac3799: strrchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strrchr(const char *s, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfc50)
Location: lib/string.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - mm/memory.c:print_vma_addr
  - fs/exec.c:setup_new_exec
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/pci/pci.c:pci_dev_str_match
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/firmware/dmi_scan.c:dmi_get_date
```
**Symbols:**

```
ffffffff81acfc50-ffffffff81acfc69: strrchr (STB_GLOBAL)
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
