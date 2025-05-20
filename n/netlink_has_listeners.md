# Function: <code>netlink_has_listeners</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174b0e0)
Location: net/netlink/af_netlink.c:1952
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
```
**Symbols:**

```
ffffffff8174b0e0-ffffffff8174b133: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b7c00)
Location: net/netlink/af_netlink.c:1259
Inline: True
Direct callers:
  - kernel/audit.c:audit_log_end
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
**Symbols:**

```
ffffffff817b7c00-ffffffff817b7c59: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e7670)
Location: net/netlink/af_netlink.c:1276
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_thread
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
**Symbols:**

```
ffffffff817e7670-ffffffff817e76c9: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81807380)
Location: net/netlink/af_netlink.c:1310
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81807380-ffffffff818073d3: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81885ef0)
Location: net/netlink/af_netlink.c:1323
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81885ef0-ffffffff81885f43: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d9860)
Location: net/netlink/af_netlink.c:1362
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818d9860-ffffffff818d98b3: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819062b0)
Location: net/netlink/af_netlink.c:1355
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff819062b0-ffffffff81906303: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81967540)
Location: net/netlink/af_netlink.c:1347
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81967540-ffffffff81967595: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199dfd0)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8199dfd0-ffffffff8199e025: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a77560)
Location: net/netlink/af_netlink.c:1348
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
**Symbols:**

```
ffffffff81a77560-ffffffff81a775b7: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a802c0)
Location: net/netlink/af_netlink.c:1349
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
**Symbols:**

```
ffffffff81a802c0-ffffffff81a80336: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a69000)
Location: net/netlink/af_netlink.c:1359
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
**Symbols:**

```
ffffffff81a69000-ffffffff81a69076: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b22540)
Location: net/netlink/af_netlink.c:1364
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
**Symbols:**

```
ffffffff81b22540-ffffffff81b225b6: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caa2d0)
Location: net/netlink/af_netlink.c:1364
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
```
**Symbols:**

```
ffffffff81caa2d0-ffffffff81caa34a: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e673c0)
Location: net/netlink/af_netlink.c:1384
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81e673c0-ffffffff81e6743a: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec31a0)
Location: net/netlink/af_netlink.c:1384
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
  - net/handshake/netlink.c:handshake_genl_notify
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81ec31a0-ffffffff81ec321a: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f864f0)
Location: net/netlink/af_netlink.c:1386
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - drivers/thermal/thermal_netlink.c:thermal_genl_send_event
  - drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp
  - net/core/sock.c:__sk_free
  - net/core/netdev-genl.c:netdev_genl_dev_notify
  - net/core/page_pool_user.c:netdev_nl_page_pool_event
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_del_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/devlink/port.c:devlink_port_notify
  - net/devlink/region.c:devlink_nl_region_notify
  - net/devlink/rate.c:devlink_rate_notify
  - net/devlink/linecard.c:devlink_linecard_notify
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_userspace_pm_active
  - net/handshake/netlink.c:handshake_genl_notify
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81f864f0-ffffffff81f8656c: netlink_has_listeners (STB_GLOBAL)
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
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4b2e8)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff800010c4b2e8-ffff800010c4b374: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5be08)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0d5be08-c0d5be8c: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d484a0)
Location: net/netlink/af_netlink.c:1348
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000d484a0-c000000000d48520: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b8840)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe0007b8840-ffffffe0007b88ba: netlink_has_listeners (STB_GLOBAL)
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
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193de40)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8193de40-ffffffff8193de95: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f7940)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff818f7940-ffffffff818f7995: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198efd0)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/netfilter/nfnetlink.c:nfnetlink_has_listeners
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8198efd0-ffffffff8198f025: netlink_has_listeners (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int netlink_has_listeners(struct sock *sk, unsigned int group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b1880)
Location: net/netlink/af_netlink.c:1348
Inline: True
Direct callers:
  - kernel/audit.c:kauditd_send_multicast_skb
  - drivers/connector/connector.c:cn_netlink_send_mult
  - net/core/sock.c:__sk_free
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff819b1880-ffffffff819b18f7: netlink_has_listeners (STB_GLOBAL)
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
