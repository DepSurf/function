# Function: <code>netlink_kernel_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174a4c0)
Location: net/netlink/af_netlink.c:2694
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff8174a4c0-ffffffff8174a4e2: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b9801)
Location: net/netlink/af_netlink.c:1969
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff817b7540-ffffffff817b7562: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e91a1)
Location: net/netlink/af_netlink.c:1986
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff817e6fe0-ffffffff817e7002: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81808e92)
Location: net/netlink/af_netlink.c:2037
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff81806d40-ffffffff81806d63: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81887d62)
Location: net/netlink/af_netlink.c:2050
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff81885a20-ffffffff81885a43: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818db748)
Location: net/netlink/af_netlink.c:2091
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff818d93c0-ffffffff818d93e2: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819080f9)
Location: net/netlink/af_netlink.c:2100
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff81905bb0-ffffffff81905bd2: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8196932a)
Location: net/netlink/af_netlink.c:2100
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff81966e10-ffffffff81966e32: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199fdca)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff8199d890-ffffffff8199d8b2: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7960c)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff81a76870-ffffffff81a76892: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a8241c)
Location: net/netlink/af_netlink.c:2102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff81a7f5c0-ffffffff81a7f5e2: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6b4ff)
Location: net/netlink/af_netlink.c:2112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff81a68590-ffffffff81a685b2: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b24b2f)
Location: net/netlink/af_netlink.c:2123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff81b21b00-ffffffff81b21b22: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cac635)
Location: net/netlink/af_netlink.c:2102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
```
**Symbols:**

```
ffffffff81caa360-ffffffff81caa38e: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6a225)
Location: net/netlink/af_netlink.c:2123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff81e67470-ffffffff81e6749e: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec61e9)
Location: net/netlink/af_netlink.c:2094
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff81ec3250-ffffffff81ec327e: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f89451)
Location: net/netlink/af_netlink.c:2089
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/connector/connector.c:cn_init
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff81f865a0-ffffffff81f865ce: netlink_kernel_release (STB_GLOBAL)
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
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4e28c)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffff800010c4ad60-ffff800010c4ad94: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5e4fc)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
c0d5b8f0-c0d5b920: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4c670)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
c000000000d48ed0-c000000000d48f18: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007ba3d0)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffe0007b8086-ffffffe0007b80b6: netlink_kernel_release (STB_GLOBAL)
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
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193fc3a)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff8193d700-ffffffff8193d722: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f972a)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff818f7200-ffffffff818f7222: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81990dca)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/netfilter/nfnetlink.c:nfnetlink_net_exit_batch
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff8198e890-ffffffff8198e8b2: netlink_kernel_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void netlink_kernel_release(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b384a)
Location: net/netlink/af_netlink.c:2101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
Direct callers:
  - kernel/audit.c:audit_net_exit
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_netlink.c:scsi_netlink_exit
  - net/core/rtnetlink.c:rtnetlink_net_exit
  - net/core/sock_diag.c:diag_net_exit
  - net/netlink/genetlink.c:genl_pernet_exit
  - net/ipv4/fib_frontend.c:fib_net_exit
  - lib/kobject_uevent.c:uevent_net_exit
```
**Symbols:**

```
ffffffff819b1140-ffffffff819b1162: netlink_kernel_release (STB_GLOBAL)
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
