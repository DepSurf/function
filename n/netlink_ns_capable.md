# Function: <code>netlink_ns_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174a160)
Location: net/netlink/af_netlink.c:1414
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_capable
  - net/netlink/af_netlink.c:netlink_net_capable
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff8174a160-ffffffff8174a174: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b70cc)
Location: net/netlink/af_netlink.c:797
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff817b7080-ffffffff817b7094: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e6b4c)
Location: net/netlink/af_netlink.c:814
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff817e6b00-ffffffff817e6b14: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8180694c)
Location: net/netlink/af_netlink.c:848
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81806900-ffffffff81806914: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8188561c)
Location: net/netlink/af_netlink.c:850
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff818855d0-ffffffff818855e4: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d8fb5)
Location: net/netlink/af_netlink.c:885
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff818d8f70-ffffffff818d8f84: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819057a5)
Location: net/netlink/af_netlink.c:880
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81905760-ffffffff81905774: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819669d5)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81966990-ffffffff819669a4: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199d455)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8199d410-ffffffff8199d424: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7767c)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/devlink.c:devlink_netns_get
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81a775c0-ffffffff81a77602: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a803fc)
Location: net/netlink/af_netlink.c:872
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/devlink.c:devlink_netns_get
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81a80340-ffffffff81a80382: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6934c)
Location: net/netlink/af_netlink.c:882
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81a69290-ffffffff81a692d2: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b228fc)
Location: net/netlink/af_netlink.c:885
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81b22840-ffffffff81b22882: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cab20a)
Location: net/netlink/af_netlink.c:885
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81cab140-ffffffff81cab18a: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e68cea)
Location: net/netlink/af_netlink.c:898
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81e68c70-ffffffff81e68cba: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec4b5a)
Location: net/netlink/af_netlink.c:898
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81ec49e0-ffffffff81ec4a2a: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f87f2a)
Location: net/netlink/af_netlink.c:901
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/devlink/dev.c:devlink_nl_reload_doit
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81f87d40-ffffffff81f87d8a: netlink_ns_capable (STB_GLOBAL)
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
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4ab4c)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffff800010c4aaa8-ffff800010c4aaec: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5b58c)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
c0d5b52c-c0d5b54c: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d48aa0)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
c000000000d48a40-c000000000d48a58: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b7e76)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffe0007b7de4-ffffffe0007b7e20: netlink_ns_capable (STB_GLOBAL)
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
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193d2c5)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8193d280-ffffffff8193d294: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f6dc5)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff818f6d80-ffffffff818f6d94: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198e455)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8198e410-ffffffff8198e424: netlink_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool netlink_ns_capable(const struct sk_buff *skb, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b0d05)
Location: net/netlink/af_netlink.c:871
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff819b0cc0-ffffffff819b0cd4: netlink_ns_capable (STB_GLOBAL)
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
