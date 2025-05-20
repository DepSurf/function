# Function: <code>netlink_kernel_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81120bfe)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff81f98819)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff813ed177)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff81541c9b)
Location: include/linux/netlink.h:60
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff815b6bfb)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff8172b48b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff8173338b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff8174f96b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff8179a227)
Location: include/linux/netlink.h:60
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81128b4e)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff81fc34b1)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff81432de7)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff815935db)
Location: include/linux/netlink.h:60
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8160f31b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81794ceb)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff8179ee2b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff817bb93b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81808107)
Location: include/linux/netlink.h:60
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811327ae)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff81fffefd)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff8144f057)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff815c0e9b)
Location: include/linux/netlink.h:60
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8163ebbb)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff817c256b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff817cd7fb)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff817eb27b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff818391e1)
Location: include/linux/netlink.h:60
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133f16)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff820e35f0)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff815d69db)
Location: include/linux/netlink.h:60
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff816536fb)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff817e0d06)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff817ecb36)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff8180b28b)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a6f1)
Location: include/linux/netlink.h:60
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff818ef28e)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140cd6)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff826ec283)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff8163d7bb)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff816bcbab)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff8185b3b6)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81868d16)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff8188a1eb)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff818da62c)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff8197556e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114f6fd)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff8271662f)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff81678e0c)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff816f90a9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff818a6cee)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff818b8c21)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff818dd879)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff819310e5)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff819d1c73)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115c3dd)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff828ce0f2)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff81697eec)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8171b989)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff818ca37e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff818df871)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff8190a239)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81960989)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a0b0d3)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81168aa4)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff828e7b5d)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff816d0a69)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81756fc9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff8191732e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff8192dec1)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff8196b639)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff819c54a7)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a7aab3)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81174944)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff828f0649)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff816f4889)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8177b269)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff8194996e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81960151)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff819a1fe9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc047)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81ab1e13)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811869b4)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff82d05851)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff815ec563)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff817ace79)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8183e3d9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81a194ae)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81a33551)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81a7b9c9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea0b8)
Location: include/linux/netlink.h:58
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81183cce)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff82ff2c2e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff81610d43)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff817c1a09)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8184eb09)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81a1969e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81a358c1)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81a84889)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6f18)
Location: include/linux/netlink.h:58
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184bfe)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff831fd60a)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff815f43b3)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff817a4f29)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81831fa9)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81a005ae)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81a1ca11)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81a6d981)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2674)
Location: include/linux/netlink.h:60
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811acf1e)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff832e4806)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff81661723)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff818308a9)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff818bdff9)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81ab26fe)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81ad0291)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81b27091)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1e8f)
Location: include/linux/netlink.h:60
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811deb64)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff8349b40a)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In lib/kobject_uevent.c (ffffffff8177b4e3)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
```
In drivers/connector/connector.c (ffffffff81971c19)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81a0a2b9)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81c2b87e)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81c4db01)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81caffd1)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34558)
Location: include/linux/netlink.h:60
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81224794)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff83ed22c4)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff81adce79)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81b89979)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81dde4fe)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81e02ac1)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81e6dd41)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81efca38)
Location: include/linux/netlink.h:60
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff82024703)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123ad5c)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff836f734c)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff81b2b0f4)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81bdd874)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81e4f436)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81e75029)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81ec9e5a)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c47e)
Location: include/linux/netlink.h:59
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff820a480b)
Location: include/linux/netlink.h:59
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81254c24)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff8392a6e4)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff81b82424)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_init
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81c32629)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff81f0e47e)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81f348d1)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81f8ce42)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff820229fb)
Location: include/linux/netlink.h:60
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff8217c912)
Location: include/linux/netlink.h:60
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e9458)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffff80001146a628)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffff8000108dd984)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffff800010981028)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffff800010beb4a0)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffff800010c03974)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffff800010c50c70)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3fd4)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffff800010d8c8fc)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c04293c4)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (c1543270)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (c09cccb0)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (c0a53988)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (c0d04224)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (c0d1cd08)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (c0d608fc)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (c0dbf4d4)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (c0e86cd8)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025a258)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (c000000001398c60)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (c000000000971418)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (c000000000a3ce90)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (c000000000cce99c)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (c000000000ced294)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (c000000000d4f940)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (c000000000dcb458)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (c000000000ecddb0)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015e25c)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffe0000256a2)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffe000574210)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffe0005e6abe)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffe00076edbc)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffe0007829a4)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffe0007bc0e0)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffe00080be60)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffe0008b5224)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116cf64)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff828d94fd)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff816ba079)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8172f959)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff818e993e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81900121)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81941e59)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bde7)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a50c63)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81160104)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff828d1c19)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff81697cb9)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81708d79)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff818a377e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff818b9f51)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff818fb949)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff819558a7)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81a0dd63)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116ad34)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff828ec271)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff816e8549)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff8176e729)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff8193a96e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81951151)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff81992fe9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/netfilter/nfnetlink.c (ffffffff819986d1)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_net_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06687)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81abd053)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81178534)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_init
```
```
In security/selinux/netlink.c (ffffffff828f1693)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - security/selinux/netlink.c:selnl_init
```
```
In drivers/connector/connector.c (ffffffff81702c49)
Location: include/linux/netlink.h:58
Inline: True
```
```
In drivers/scsi/scsi_netlink.c (ffffffff81789ec9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - drivers/scsi/scsi_netlink.c:scsi_netlink_init
```
```
In net/core/rtnetlink.c (ffffffff8195c19e)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_net_init
```
```
In net/core/sock_diag.c (ffffffff81972a91)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/core/sock_diag.c:diag_net_init
```
```
In net/netlink/genetlink.c (ffffffff819b5ad9)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_pernet_init
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10d07)
Location: include/linux/netlink.h:58
Inline: True
```
```
In lib/kobject_uevent.c (ffffffff81ac94d3)
Location: include/linux/netlink.h:58
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
```
</details>
</li>
</ul>

## Differences
