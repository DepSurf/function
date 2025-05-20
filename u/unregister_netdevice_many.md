# Function: <code>unregister_netdevice_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716940)
Location: net/core/dev.c:7263
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_device_event
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81716940-ffffffff817169de: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e920)
Location: net/core/dev.c:7781
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
**Symbols:**

```
ffffffff8177e920-ffffffff8177e9c4: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ac210)
Location: net/core/dev.c:7952
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
**Symbols:**

```
ffffffff817ac210-ffffffff817ac2b4: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff817cb57d)
Location: net/core/dev.c:8146
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff817cb390-ffffffff817cb41e: unregister_netdevice_many.part.102 (STB_LOCAL)
ffffffff817cb420-ffffffff817cb43a: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81844e10)
Location: net/core/dev.c:8325
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81844c20-ffffffff81844cae: unregister_netdevice_many.part.107 (STB_LOCAL)
ffffffff81844cb0-ffffffff81844cca: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81898300)
Location: net/core/dev.c:8575
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81898300-ffffffff8189839b: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba760)
Location: net/core/dev.c:9205
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff818ba760-ffffffff818ba7fb: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818fce0c)
Location: net/core/dev.c:9310
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff818fcc20-ffffffff818fcca9: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff818fccb0-ffffffff818fccc9: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8192f419)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff8192f230-ffffffff8192f2b6: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff8192f2c0-ffffffff8192f2d9: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a0e489)
Location: net/core/dev.c:10109
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81a0e150-ffffffff81a0e1d9: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff81a0e1e0-ffffffff81a0e1f9: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a05ff9)
Location: net/core/dev.c:10818
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81a05cc0-ffffffff81a05d49: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff81a05d50-ffffffff81a05d69: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ec190)
Location: net/core/dev.c:11000
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff819ec190-ffffffff819ec6e8: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:11007
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81d3617d-ffffffff81d361bb: unregister_netdevice_many.cold (STB_LOCAL)
ffffffff81a9d080-ffffffff81a9d60a: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10787
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81f029ed-ffffffff81f02a29: unregister_netdevice_many.cold (STB_LOCAL)
ffffffff81c167e0-ffffffff81c16e4f: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dd1b63)
Location: net/core/dev.c:10887
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdevice_queue
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81dd11c0-ffffffff81dd11de: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e42743)
Location: net/core/dev.c:10904
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdevice_queue
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81e41db0-ffffffff81e41dce: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f01371)
Location: net/core/dev.c:11115
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdevice_queue
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81f007f0-ffffffff81f0080e: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffff800010bcc2a8)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffff800010bcc078-ffff800010bcc120: unregister_netdevice_many.part.0 (STB_LOCAL)
ffff800010bcc120-ffff800010bcc158: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c0cea308)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
c0cea0fc-c0cea18c: unregister_netdevice_many.part.0 (STB_LOCAL)
c0cea18c-c0cea1b4: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000ca8db0)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
c000000000ca8b00-c000000000ca8bdc: unregister_netdevice_many.part.0 (STB_LOCAL)
c000000000ca8be0-c000000000ca8c00: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe000759ae8)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffe00075991a-ffffffe000759998: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffe000759998-ffffffe0007599c8: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818cf419)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff818cf230-ffffffff818cf2b6: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff818cf2c0-ffffffff818cf2d9: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81889539)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/vxlan.c:vxlan_exit_batch_net
  - drivers/net/vxlan.c:vxlan_netdevice_event
  - drivers/net/vxlan.c:vxlan_dev_create
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81889350-ffffffff818893d6: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff818893e0-ffffffff818893f9: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81920419)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81920230-ffffffff819202b6: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff819202c0-ffffffff819202d9: unregister_netdevice_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_netdevice_many(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81942179)
Location: net/core/dev.c:9654
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_delete_link
  - net/core/rtnetlink.c:__rtnl_link_unregister
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
```
**Symbols:**

```
ffffffff81941f90-ffffffff81942016: unregister_netdevice_many.part.0 (STB_LOCAL)
ffffffff81942020-ffffffff81942039: unregister_netdevice_many (STB_GLOBAL)
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
