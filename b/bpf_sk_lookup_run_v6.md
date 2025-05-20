# Function: <code>bpf_sk_lookup_run_v6</code>

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
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b661d0)
Location: include/linux/filter.h:1405
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b933b0)
Location: include/linux/filter.h:1405
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b661d0-ffffffff81b66375: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff81b933b0-ffffffff81b93555: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b54350)
Location: include/linux/filter.h:1444
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b824e0)
Location: include/linux/filter.h:1444
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81b54350-ffffffff81b544eb: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff81b824e0-ffffffff81b8267b: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: include/linux/filter.h:1468
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/filter.h:1468
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81c1b2d0-ffffffff81c1b483: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff81d40627-ffffffff81d40651: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
ffffffff81c4e590-ffffffff81c4e743: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff81d41896-ffffffff81d418c0: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: include/linux/filter.h:1492
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/filter.h:1492
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81db7a30-ffffffff81db7c1b: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff81f0cfed-ffffffff81f0d01d: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
ffffffff81deee60-ffffffff81def04b: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff81f0e1fd-ffffffff81f0e22d: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: include/linux/filter.h:1467
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/filter.h:1467
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81f87890-ffffffff81f87a7b: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff820b4437-ffffffff820b4467: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
ffffffff81fc2ef0-ffffffff81fc30db: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff820b53a7-ffffffff820b53d7: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (0)
Location: include/linux/filter.h:1467
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/filter.h:1467
Inline: True
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
**Symbols:**

```
ffffffff81fe7d20-ffffffff81fe7f08: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff82135520-ffffffff82135550: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
ffffffff82023e60-ffffffff82024048: bpf_sk_lookup_run_v6.constprop.0 (STB_LOCAL)
ffffffff82136287-ffffffff821362b7: bpf_sk_lookup_run_v6.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bpf_sk_lookup_run_v6(struct net *net, int protocol, const struct in6_addr *saddr, const __be16 sport, const struct in6_addr *daddr, const u16 dport, const int ifindex, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/filter.h:1504
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_run_sk_lookup
```
**Symbols:**

```
ffffffff820f2f70-ffffffff820f3161: bpf_sk_lookup_run_v6 (STB_LOCAL)
ffffffff82217e57-ffffffff82217e87: bpf_sk_lookup_run_v6.cold (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
</ul>
