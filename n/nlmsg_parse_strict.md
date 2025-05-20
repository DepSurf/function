# Function: <code>nlmsg_parse_strict</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a75d8)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/core/neighbour.c (ffffffff818c4061)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff818cabe6)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81954849)
Location: include/net/netlink.h:531
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff819603c3)
Location: include/net/netlink.h:531
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv6/addrconf.c (ffffffff8199b9f9)
Location: include/net/netlink.h:531
Inline: True
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
