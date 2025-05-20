# Function: <code>inet_get_local_port_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81763a00)
Location: net/ipv4/inet_connection_sock.c:33
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81763a00-ffffffff81763a31: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d02ce)
Location: net/ipv4/inet_connection_sock.c:34
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff817cfed0-ffffffff817cff01: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8180010e)
Location: net/ipv4/inet_connection_sock.c:34
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff817ffcc0-ffffffff817ffcf1: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8182100d)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff8181ffe0-ffffffff81820011: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189fdcd)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff8189efd0-ffffffff8189f001: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f48eb)
Location: net/ipv4/inet_connection_sock.c:110
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff818f3830-ffffffff818f3863: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819226ae)
Location: net/ipv4/inet_connection_sock.c:119
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81921350-ffffffff81921383: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81984e14)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81983ee0-ffffffff81983f11: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bb887)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff819ba690-ffffffff819ba6c1: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5f65)
Location: net/ipv4/inet_connection_sock.c:120
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81aa51f0-ffffffff81aa5223: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab05a5)
Location: net/ipv4/inet_connection_sock.c:120
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81aaf800-ffffffff81aaf833: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b783)
Location: net/ipv4/inet_connection_sock.c:120
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81a9ab10-ffffffff81a9ab43: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b56db3)
Location: net/ipv4/inet_connection_sock.c:120
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81b55f80-ffffffff81b55fb3: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3d40)
Location: net/ipv4/inet_connection_sock.c:120
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81ce3d40-ffffffff81ce3d81: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6790)
Location: net/ipv4/inet_connection_sock.c:120
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81ea6790-ffffffff81ea67d1: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(const struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f061ca)
Location: net/ipv4/inet_connection_sock.c:120
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_sk_get_local_port_range
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81f04f60-ffffffff81f04fa1: inet_get_local_port_range (STB_GLOBAL)
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
In security/selinux/hooks.c (ffffffff816e6daf)
Location: include/net/ip.h:352
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc927a)
Location: include/net/ip.h:352
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203df23)
Location: include/net/ip.h:352
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
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
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6e278)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffff800010c6c3c0-ffff800010c6c428: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7b028)
Location: net/ipv4/inet_connection_sock.c:115
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
c0d7b028-c0d7b0a8: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d73e44)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
c000000000d71a00-c000000000d71a5c: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d28a2)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffe0007d1b80-ffffffe0007d1bde: inet_get_local_port_range (STB_GLOBAL)
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
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195b6f7)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff8195a500-ffffffff8195a531: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819151e7)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit_one
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff81913ff0-ffffffff81914021: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c5ec7)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff819c4cd0-ffffffff819c4d01: inet_get_local_port_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void inet_get_local_port_range(struct net *net, int *low, int *high);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cf9a9)
Location: net/ipv4/inet_connection_sock.c:115
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
**Symbols:**

```
ffffffff819ce780-ffffffff819ce7b1: inet_get_local_port_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net *net</code> ➡️ <code>const struct net *net</code>
</li>
</ul>
</details>
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
