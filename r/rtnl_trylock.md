# Function: <code>rtnl_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81729d00)
Location: net/core/rtnetlink.c:86
Inline: False
Direct callers:
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
```
**Symbols:**

```
ffffffff81729d00-ffffffff81729d17: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81793840)
Location: net/core/rtnetlink.c:108
Inline: False
Direct callers:
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81793840-ffffffff81793857: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c1110)
Location: net/core/rtnetlink.c:108
Inline: False
Direct callers:
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff817c1110-ffffffff817c1127: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817df8d0)
Location: net/core/rtnetlink.c:110
Inline: False
Direct callers:
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff817df8d0-ffffffff817df8e7: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185a130)
Location: net/core/rtnetlink.c:110
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff8185a130-ffffffff8185a147: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a59b0)
Location: net/core/rtnetlink.c:121
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff818a59b0-ffffffff818a59c7: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c8f40)
Location: net/core/rtnetlink.c:121
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff818c8f40-ffffffff818c8f57: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81915f10)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81915f10-ffffffff81915f27: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81948520)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81948520-ffffffff81948537: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18360)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81a18360-ffffffff81a18377: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18430)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81a18430-ffffffff81a18447: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ff300)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff819ff300-ffffffff819ff317: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab14f0)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81ab14f0-ffffffff81ab1507: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2a6a0)
Location: net/core/rtnetlink.c:151
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81c2a6a0-ffffffff81c2a6bd: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ddd420)
Location: net/core/rtnetlink.c:152
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81ddd420-ffffffff81ddd43d: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4e170)
Location: net/core/rtnetlink.c:155
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81e4e170-ffffffff81e4e18d: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0ced0)
Location: net/core/rtnetlink.c:156
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_rx_dim_work
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
```
**Symbols:**

```
ffffffff81f0ced0-ffffffff81f0ceed: rtnl_trylock (STB_GLOBAL)
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
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bea0d8)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffff800010bea0d8-ffff800010bea100: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d02a48)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
c0d02a48-c0d02a6c: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccc500)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
c000000000ccc500-c000000000ccc53c: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076d98a)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffe00076d98a-ffffffe00076d9b4: rtnl_trylock (STB_GLOBAL)
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
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e84f0)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff818e84f0-ffffffff818e8507: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a2330)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff818a2330-ffffffff818a2347: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81939520)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81939520-ffffffff81939537: rtnl_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtnl_trylock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195ac00)
Location: net/core/rtnetlink.c:116
Inline: False
Direct callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff8195ac00-ffffffff8195ac17: rtnl_trylock (STB_GLOBAL)
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
