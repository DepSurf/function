# Function: <code>vsnprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff813f5210)
Location: lib/vsprintf.c:1837
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/kmod.c:__request_module
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:kthread_create_on_node
  - kernel/printk/printk.c:dump_stack_set_arch_desc
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/dcache.c:dynamic_dname
  - fs/seq_file.c:seq_vprintf
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/common.c:tomoyo_addprintf
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_supervisor
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:snprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:sprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - net/netfilter/nf_log.c:nf_log_packet
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_buf_add
```
**Symbols:**

```
ffffffff813f5210-ffffffff813f5733: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143bdf0)
Location: lib/vsprintf.c:1974
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/kmod.c:__request_module
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:kthread_create_on_node
  - kernel/printk/printk.c:dump_stack_set_arch_desc
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/dcache.c:dynamic_dname
  - fs/seq_file.c:seq_vprintf
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - lib/vsprintf.c:pointer
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
```
**Symbols:**

```
ffffffff8143bdf0-ffffffff8143c2e2: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81458dd0)
Location: lib/vsprintf.c:2002
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/kmod.c:__request_module
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/printk/printk.c:dump_stack_set_arch_desc
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/dcache.c:dynamic_dname
  - fs/seq_file.c:seq_vprintf
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - lib/vsprintf.c:pointer
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
```
**Symbols:**

```
ffffffff81458dd0-ffffffff814592c2: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818fa7c0)
Location: lib/vsprintf.c:2142
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/kmod.c:__request_module
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/printk/printk.c:dump_stack_set_arch_desc
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/dcache.c:dynamic_dname
  - fs/seq_file.c:seq_vprintf
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818fa7c0-ffffffff818fac8d: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81981400)
Location: lib/vsprintf.c:2240
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:dump_stack_set_arch_desc
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/dcache.c:dynamic_dname
  - fs/seq_file.c:seq_vprintf
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81981400-ffffffff819818d9: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dd420)
Location: lib/vsprintf.c:2226
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819dd420-ffffffff819dd8bf: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a159a0)
Location: lib/vsprintf.c:2354
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a159a0-ffffffff81a15eba: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a854b0)
Location: lib/vsprintf.c:2461
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff81a854b0-ffffffff81a8598f: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abc730)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff81abc730-ffffffff81abcc0f: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f8750)
Location: lib/vsprintf.c:2578
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
```
**Symbols:**

```
ffffffff815f8750-ffffffff815f8c2f: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161ce10)
Location: lib/vsprintf.c:2577
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:vprintk_store
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/trace/bpf_trace.c:bpf_do_trace_printk
  - kernel/bpf/btf.c:btf_snprintf_show
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
```
**Symbols:**

```
ffffffff8161ce10-ffffffff8161d2ef: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff816006b0)
Location: lib/vsprintf.c:2708
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:vprintk_store
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/bpf/btf.c:btf_snprintf_show
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/ethtool/ioctl.c:ethtool_sprintf
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
```
**Symbols:**

```
ffffffff816006b0-ffffffff81600bf3: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166e610)
Location: lib/vsprintf.c:2727
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:vprintk_store
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/trace/trace_boot.c:append_printf
  - kernel/bpf/btf.c:btf_snprintf_show
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/ethtool/ioctl.c:ethtool_sprintf
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
```
**Symbols:**

```
ffffffff8166e610-ffffffff8166eb53: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81788890)
Location: lib/vsprintf.c:2712
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:vprintk_store
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/trace/trace_boot.c:append_printf
  - kernel/bpf/btf.c:btf_snprintf_show
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/ethtool/ioctl.c:ethtool_sprintf
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
```
**Symbols:**

```
ffffffff81788890-ffffffff81788dc9: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82045bc0)
Location: lib/vsprintf.c:2726
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/printk/printk.c:vprintk_store
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/trace/trace_boot.c:append_printf
  - kernel/bpf/btf.c:btf_snprintf_show
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_get_offsets_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/ethtool/ioctl.c:ethtool_sprintf
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff82045bc0-ffffffff820460ee: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c41e0)
Location: lib/vsprintf.c:2747
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/printk/printk.c:vprintk_store
  - kernel/module/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/trace/trace_boot.c:append_printf
  - kernel/bpf/btf.c:btf_snprintf_show
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_get_offsets_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/ethtool/ioctl.c:ethtool_sprintf
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff820c41e0-ffffffff820c4746: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219eb60)
Location: lib/vsprintf.c:2754
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/printk/printk.c:vprintk_store
  - kernel/module/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/trace/trace_boot.c:append_printf
  - kernel/bpf/btf.c:btf_snprintf_show
  - mm/backing-dev.c:bdi_register_va
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_printf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_get_offsets_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/leds/led-triggers.c:led_trigger_snprintf
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/ethtool/ioctl.c:ethtool_sprintf
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_printf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff8219eb60-ffffffff8219f0c6: vsnprintf (STB_GLOBAL)
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
int vsnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d96a00)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffff800010d96a00-ffff800010d9711c: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e942a4)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:early_print
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_log
  - drivers/usb/musb/musb_trace.c:trace_event_raw_event_musb_log
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - sound/soc/soc-dapm.c:pop_dbg
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
c0e942a4-c0e946a8: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000edce00)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - arch/powerpc/kernel/udbg.c:udbg_printf
  - arch/powerpc/xmon/nonstdio.c:xmon_printf
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
c000000000edce00-c000000000edd2f4: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008c0b82)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffe0008c0b82-ffffffe0008c0e90: vsnprintf (STB_GLOBAL)
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
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5b580)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff81a5b580-ffffffff81a5ba5f: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a18660)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff81a18660-ffffffff81a18b3f: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac7970)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff81ac7970-ffffffff81ac7e4f: vsnprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vsnprintf(char *buf, size_t size, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad3e50)
Location: lib/vsprintf.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:alloc_workqueue
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kmod.c:__request_module
  - kernel/audit.c:audit_log_vformat
  - kernel/audit.c:audit_log_vformat
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - mm/slub.c:slab_err
  - fs/seq_file.c:seq_vprintf
  - fs/d_path.c:dynamic_dname
  - fs/coredump.c:cn_vprintf
  - fs/configfs/item.c:config_item_set_name
  - security/tomoyo/audit.c:tomoyo_write_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_addprintf
  - lib/kasprintf.c:kvasprintf
  - lib/kasprintf.c:kvasprintf
  - drivers/pnp/interface.c:pnp_printf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/tty/hvc/hvc_xen.c:xen_raw_printk
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
  - drivers/usb/host/xhci-trace.c:trace_event_raw_event_xhci_log_msg
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_find_carveout_by_name
  - net/netfilter/nf_log.c:nf_log_buf_add
  - net/netfilter/nf_log.c:nf_log_trace
  - net/netfilter/nf_log.c:nf_log_packet
  - lib/dump_stack.c:dump_stack_set_arch_desc
  - lib/kobject_uevent.c:add_uevent_var
  - lib/seq_buf.c:seq_buf_vprintf
  - lib/vsprintf.c:sprintf
  - lib/vsprintf.c:vsprintf
  - lib/vsprintf.c:scnprintf
  - lib/vsprintf.c:snprintf
```
**Symbols:**

```
ffffffff81ad3e50-ffffffff81ad432f: vsnprintf (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
