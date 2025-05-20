# Function: <code>netlink_broadcast_filtered</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174b8e0)
Location: net/netlink/af_netlink.c:2076
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:nlmsg_notify
```
**Symbols:**

```
ffffffff8174b8e0-ffffffff8174bc9c: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b88c0)
Location: net/netlink/af_netlink.c:1383
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff817b88c0-ffffffff817b8c78: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e8370)
Location: net/netlink/af_netlink.c:1400
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff817e8370-ffffffff817e8728: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81808350)
Location: net/netlink/af_netlink.c:1435
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81808350-ffffffff818086e9: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818871b0)
Location: net/netlink/af_netlink.c:1448
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818871b0-ffffffff81887564: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818da850)
Location: net/netlink/af_netlink.c:1487
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff818da850-ffffffff818dac31: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81907130)
Location: net/netlink/af_netlink.c:1480
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff81907130-ffffffff81907514: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819683f0)
Location: net/netlink/af_netlink.c:1480
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff819683f0-ffffffff819687c8: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199ee90)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff8199ee90-ffffffff8199f268: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a78fa0)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff81a78fa0-ffffffff81a79147: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a817d0)
Location: net/netlink/af_netlink.c:1482
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff81a817d0-ffffffff81a81977: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6a8d0)
Location: net/netlink/af_netlink.c:1492
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff81a6a8d0-ffffffff81a6aa79: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b23ed0)
Location: net/netlink/af_netlink.c:1497
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff81b23ed0-ffffffff81b24079: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, netlink_filter_fn filter, void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8a3b0)
Location: net/netlink/af_netlink.c:1519
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - fs/quota/netlink.c:quota_send_warning
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/regulator/event.c:reg_generate_netlink_event
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - drivers/dpll/dpll_netlink.c:dpll_pin_event_send
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
  - net/core/sock_diag.c:sock_diag_broadcast_destroy_work
  - net/core/netdev-genl.c:netdev_genl_dev_notify
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_hw_summary_work
  - net/core/drop_monitor.c:send_dm_alert
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/netlink/genetlink.c:genlmsg_multicast_allns
  - net/ethtool/netlink.c:ethnl_multicast
  - net/devlink/port.c:devlink_port_notify
  - net/devlink/region.c:devlink_nl_region_notify
  - net/devlink/rate.c:devlink_rate_notify
  - net/devlink/linecard.c:devlink_linecard_notify
  - net/mptcp/pm_netlink.c:mptcp_nl_mcast_send
  - net/handshake/netlink.c:handshake_genl_notify
```
**Symbols:**

```
ffffffff81f8a3b0-ffffffff81f8a585: netlink_broadcast_filtered (STB_GLOBAL)
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
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4c118)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffff800010c4c118-ffff800010c4c58c: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5ce84)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
c0d5ce84-c0d5d2dc: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4aa90)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
c000000000d4aa90-c000000000d4afd8: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b9500)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffe0007b9500-ffffffe0007b98f6: netlink_broadcast_filtered (STB_GLOBAL)
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
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193ed00)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff8193ed00-ffffffff8193f0d8: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f8800)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff818f8800-ffffffff818f8bd8: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198fe90)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff8198fe90-ffffffff81990268: netlink_broadcast_filtered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlink_broadcast_filtered(struct sock *ssk, struct sk_buff *skb, u32 portid, u32 group, gfp_t allocation, int (*filter)(struct sock *, struct sk_buff *, void *), void *filter_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b2760)
Location: net/netlink/af_netlink.c:1481
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:netlink_sendmsg
```
**Symbols:**

```
ffffffff819b2760-ffffffff819b2b37: netlink_broadcast_filtered (STB_GLOBAL)
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
