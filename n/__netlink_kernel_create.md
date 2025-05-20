# Function: <code>__netlink_kernel_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174d300)
Location: net/netlink/af_netlink.c:2619
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff8174d300-ffffffff8174d559: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b96f0)
Location: net/netlink/af_netlink.c:1894
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff817b96f0-ffffffff817b9960: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e9090)
Location: net/netlink/af_netlink.c:1911
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff817e9090-ffffffff817e9300: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81808d80)
Location: net/netlink/af_netlink.c:1962
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81808d80-ffffffff81808fdf: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81887c50)
Location: net/netlink/af_netlink.c:1975
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81887c50-ffffffff81887eaf: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818db640)
Location: net/netlink/af_netlink.c:2016
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff818db640-ffffffff818db89f: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81907f40)
Location: net/netlink/af_netlink.c:2025
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81907f40-ffffffff819081d3: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81969220)
Location: net/netlink/af_netlink.c:2025
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81969220-ffffffff81969483: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199fcc0)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff8199fcc0-ffffffff8199ff23: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a79440)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff81a79440-ffffffff81a796ab: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a82250)
Location: net/netlink/af_netlink.c:2027
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff81a82250-ffffffff81a824bb: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6b330)
Location: net/netlink/af_netlink.c:2037
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff81a6b330-ffffffff81a6b59c: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b24960)
Location: net/netlink/af_netlink.c:2048
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff81b24960-ffffffff81b24bcc: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cac3b0)
Location: net/netlink/af_netlink.c:2027
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - lib/kobject_uevent.c:uevent_net_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
```
**Symbols:**

```
ffffffff81cac3b0-ffffffff81cac668: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e69fa0)
Location: net/netlink/af_netlink.c:2048
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81e69fa0-ffffffff81e6a258: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec5f70)
Location: net/netlink/af_netlink.c:2021
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81ec5f70-ffffffff81ec621c: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f891d0)
Location: net/netlink/af_netlink.c:2015
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81f891d0-ffffffff81f89484: __netlink_kernel_create (STB_GLOBAL)
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
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4e188)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffff800010c4e188-ffff800010c4e3e0: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5e3e4)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
c0d5e3e4-c0d5e634: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4c530)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
c000000000d4c530-c000000000d4c864: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007ba2ea)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffe0007ba2ea-ffffffe0007ba4e2: __netlink_kernel_create (STB_GLOBAL)
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
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193fb30)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff8193fb30-ffffffff8193fd93: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f9620)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff818f9620-ffffffff818f9883: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81990cc0)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - net/netfilter/nfnetlink.c:nfnetlink_net_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff81990cc0-ffffffff81990f23: __netlink_kernel_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__netlink_kernel_create(struct net *net, int unit, struct module *module, struct netlink_kernel_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b3740)
Location: net/netlink/af_netlink.c:2026
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_init
  - security/selinux/netlink.c:selnl_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
  - net/core/rtnetlink.c:rtnetlink_net_init
  - net/core/sock_diag.c:diag_net_init
  - net/netlink/genetlink.c:genl_pernet_init
  - lib/kobject_uevent.c:uevent_net_init
```
**Symbols:**

```
ffffffff819b3740-ffffffff819b39a3: __netlink_kernel_create (STB_GLOBAL)
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
