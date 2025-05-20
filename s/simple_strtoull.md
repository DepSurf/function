# Function: <code>simple_strtoull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff813f26a0)
Location: lib/vsprintf.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - drivers/xen/xen-balloon.c:store_target_kb
```
**Symbols:**

```
ffffffff813f26a0-ffffffff813f270d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81439340)
Location: lib/vsprintf.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - drivers/xen/xen-balloon.c:store_target_kb
```
**Symbols:**

```
ffffffff81439340-ffffffff814393ad: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81456320)
Location: lib/vsprintf.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
```
**Symbols:**

```
ffffffff81456320-ffffffff8145638d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f7c00)
Location: lib/vsprintf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff818f7c00-ffffffff818f7c6d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197e680)
Location: lib/vsprintf.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff8197e680-ffffffff8197e6ed: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dabb0)
Location: lib/vsprintf.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff819dabb0-ffffffff819dac1d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a12e50)
Location: lib/vsprintf.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a12e50-ffffffff81a12ebd: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a822b0)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a822b0-ffffffff81a8231d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ab94c0)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81ab94c0-ffffffff81ab952d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f71f5)
Location: lib/vsprintf.c:64
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - lib/cmdline.c:memparse
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/scsi/scsi_sysfs.c:scsi_scan
```
**Symbols:**

```
ffffffff815f4140-ffffffff815f41ad: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161b608)
Location: lib/vsprintf.c:64
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - lib/cmdline.c:memparse
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_option
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/scsi/scsi_sysfs.c:scsi_scan
  - drivers/scsi/scsi_sysfs.c:scsi_scan
```
**Symbols:**

```
ffffffff816187b0-ffffffff8161881d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd0f6)
Location: lib/vsprintf.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - lib/cmdline.c:memparse
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_option
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
```
**Symbols:**

```
ffffffff815fd030-ffffffff815fd0cb: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166acc0)
Location: lib/vsprintf.c:90
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - lib/cmdline.c:memparse
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_option
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:target_kb_store
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
```
**Symbols:**

```
ffffffff8166acc0-ffffffff8166ad5b: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81783540)
Location: lib/vsprintf.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - lib/cmdline.c:memparse
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_option
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:target_kb_store
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
```
**Symbols:**

```
ffffffff81783540-ffffffff81783561: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82040550)
Location: lib/vsprintf.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/page_alloc.c:cmdline_parse_movablecore
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:target_kb_store
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - lib/cmdline.c:memparse
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_option
```
**Symbols:**

```
ffffffff82040550-ffffffff82040571: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820bea50)
Location: lib/vsprintf.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/mm_init.c:cmdline_parse_movablecore
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:target_kb_store
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - lib/cmdline.c:memparse
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_option
```
**Symbols:**

```
ffffffff820bea50-ffffffff820bea71: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff821992d0)
Location: lib/vsprintf.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - mm/mm_init.c:cmdline_parse_movablecore
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/xen/xen-balloon.c:target_kb_store
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - drivers/scsi/scsi_sysfs.c:store_scan
  - lib/cmdline.c:memparse
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_option
```
**Symbols:**

```
ffffffff821992d0-ffffffff821992ec: simple_strtoull (STB_GLOBAL)
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
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d93b78)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffff800010d93b78-ffff800010d93bf4: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e8fe24)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
c0e8fe24-c0e8fea0: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed8120)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas-proc.c:parse_number
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
c000000000ed8120-c000000000ed81bc: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bdbc6)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffe0008bdbc6-ffffffe0008bdc1a: simple_strtoull (STB_GLOBAL)
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
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a58310)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a58310-ffffffff81a5837d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a153f0)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a153f0-ffffffff81a1545d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac4700)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81ac4700-ffffffff81ac476d: simple_strtoull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad0bd0)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/early_printk.c:early_serial_init
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - kernel/debug/kdb/kdb_main.c:kdbgetu64arg
  - mm/page_alloc.c:cmdline_parse_core
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - drivers/xen/xen-balloon.c:store_target_kb
  - drivers/tty/serial/serial_core.c:uart_parse_earlycon
  - lib/cmdline.c:memparse
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81ad0bd0-ffffffff81ad0c3d: simple_strtoull (STB_GLOBAL)
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
