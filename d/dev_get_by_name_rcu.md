# Function: <code>dev_get_by_name_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718ae0)
Location: net/core/dev.c:748
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81718ae0-ffffffff81718b5a: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780a50)
Location: net/core/dev.c:752
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81780a50-ffffffff81780ac8: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ae890)
Location: net/core/dev.c:751
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff817ae890-ffffffff817ae908: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd1e0)
Location: net/core/dev.c:758
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff817cd1e0-ffffffff817cd276: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846b20)
Location: net/core/dev.c:761
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81846b20-ffffffff81846bb6: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:761
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81898f84-ffffffff81898f90: dev_get_by_name_rcu.cold.155 (STB_LOCAL)
ffffffff818901a0-ffffffff8189022e: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:763
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff818bb3d6-ffffffff818bb3e2: dev_get_by_name_rcu.cold.160 (STB_LOCAL)
ffffffff818b0430-ffffffff818b04be: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:759
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff819072bf-ffffffff819072cb: dev_get_by_name_rcu.cold (STB_LOCAL)
ffffffff818fd180-ffffffff818fd213: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8193991f-ffffffff8193992b: dev_get_by_name_rcu.cold (STB_LOCAL)
ffffffff8192f790-ffffffff8192f823: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02139)
Location: net/core/dev.c:879
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_by_name
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev_ioctl.c:dev_load
  - net/core/dev_ioctl.c:dev_ifsioc_locked
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81a02110-ffffffff81a02129: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a027d3)
Location: net/core/dev.c:882
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_load
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81a02750-ffffffff81a02769: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e9343)
Location: net/core/dev.c:930
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_load
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff819e92c0-ffffffff819e92d9: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9a173)
Location: net/core/dev.c:807
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_load
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81a9a0f0-ffffffff81a9a109: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81c0c1ca)
Location: net/core/dev.c:754
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81f02891-ffffffff81f0289d: dev_get_by_name_rcu.cold (STB_LOCAL)
ffffffff81c14320-ffffffff81c143a2: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc49da)
Location: net/core/dev.c:754
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_get_by_name
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81dc4b60-ffffffff81dc4bea: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e361ba)
Location: net/core/dev.c:752
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:netdev_get_by_name
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81e34a80-ffffffff81e34b0a: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef447a)
Location: net/core/dev.c:769
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:netdev_get_by_name
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff81ef2150-ffffffff81ef21da: dev_get_by_name_rcu (STB_GLOBAL)
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
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bca288)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffff800010bca288-ffff800010bca344: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce82e4)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c0ce82e4-c0ce8394: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca95d0)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
c000000000ca95d0-c000000000ca9790: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007570e0)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffe0007570e0-ffffffe00075715e: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff818d98ef-ffffffff818d98fb: dev_get_by_name_rcu.cold (STB_LOCAL)
ffffffff818cf790-ffffffff818cf823: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8189372f-ffffffff8189373b: dev_get_by_name_rcu.cold (STB_LOCAL)
ffffffff818898b0-ffffffff81889943: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8192a91f-ffffffff8192a92b: dev_get_by_name_rcu.cold (STB_LOCAL)
ffffffff81920790-ffffffff81920823: dev_get_by_name_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct net_device *dev_get_by_name_rcu(struct net *net, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:677
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/dev.c:dev_get_by_name
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg_spkt
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
**Symbols:**

```
ffffffff8194c069-ffffffff8194c075: dev_get_by_name_rcu.cold (STB_LOCAL)
ffffffff819424f0-ffffffff81942583: dev_get_by_name_rcu (STB_GLOBAL)
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
