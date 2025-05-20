# Function: <code>proc_dostring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81087cf0)
Location: kernel/sysctl.c:1904
Inline: False
Direct callers:
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81087cf0-ffffffff81087f1c: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108ab70)
Location: kernel/sysctl.c:2024
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff8108ab70-ffffffff8108ada7: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108fac0)
Location: kernel/sysctl.c:2009
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff8108fac0-ffffffff8108fcf7: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108cbb0)
Location: kernel/sysctl.c:2033
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff8108cbb0-ffffffff8108cdc5: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81093820)
Location: kernel/sysctl.c:2025
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81093820-ffffffff81093a35: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81097270)
Location: kernel/sysctl.c:2030
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81097270-ffffffff81097492: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8109f5f0)
Location: kernel/sysctl.c:2078
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff8109f5f0-ffffffff8109f812: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a3cc0)
Location: kernel/sysctl.c:2128
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810a3cc0-ffffffff810a3ed4: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aa290)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810aa290-ffffffff810aa4bc: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b1f00)
Location: kernel/sysctl.c:359
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810b1f00-ffffffff810b1f5c: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ad730)
Location: kernel/sysctl.c:358
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810ad730-ffffffff810ad78c: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ae940)
Location: kernel/sysctl.c:370
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810ae940-ffffffff810ae99c: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c0630)
Location: kernel/sysctl.c:379
Inline: True
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810c0630-ffffffff810c068c: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d8040)
Location: kernel/sysctl.c:259
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/coredump.c:proc_dostring_coredump
  - drivers/char/random.c:proc_do_uuid
  - drivers/cdrom/cdrom.c:cdrom_sysctl_info
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810d8040-ffffffff810d80b0: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f7ba0)
Location: kernel/sysctl.c:261
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/coredump.c:proc_dostring_coredump
  - drivers/char/random.c:proc_do_uuid
  - drivers/cdrom/cdrom.c:cdrom_sysctl_info
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810f7ba0-ffffffff810f7c10: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81103fa0)
Location: kernel/sysctl.c:260
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - fs/coredump.c:proc_dostring_coredump
  - drivers/char/random.c:proc_do_uuid
  - drivers/cdrom/cdrom.c:cdrom_sysctl_info
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81103fa0-ffffffff81104010: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110d8f0)
Location: kernel/sysctl.c:260
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - fs/coredump.c:proc_dostring_coredump
  - drivers/char/random.c:proc_do_uuid
  - drivers/cdrom/cdrom.c:cdrom_sysctl_info
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff8110d8f0-ffffffff8110d960: proc_dostring (STB_GLOBAL)
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
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010104d00)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffff800010104d00-ffff800010104d74: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035e9a8)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
c035e9a8-c035ea08: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014a810)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
c00000000014a810-c00000000014a89c: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000c9302)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffe0000c9302-ffffffe0000c94ce: proc_dostring (STB_GLOBAL)
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
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a3bb0)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810a3bb0-ffffffff810a3ddc: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81092590)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff81092590-ffffffff810927bc: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a3b60)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810a3b60-ffffffff810a3d8c: proc_dostring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810abc20)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/printk/printk.c:devkmsg_sysctl_set_loglvl
  - kernel/seccomp.c:read_actions_logged
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - mm/page_alloc.c:numa_zonelist_order_handler
  - drivers/char/random.c:proc_do_uuid
  - net/core/sysctl_net_core.c:proc_do_rss_key
  - net/core/sysctl_net_core.c:set_default_qdisc
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
```
**Symbols:**

```
ffffffff810abc20-ffffffff810abe4c: proc_dostring (STB_GLOBAL)
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
