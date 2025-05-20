# Function: <code>bpf_sk_lookup_run_v4</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81aad280)
Location: include/linux/filter.h:1369
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81adea30)
Location: include/linux/filter.h:1369
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81aad280-ffffffff81aad42b: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff81adea30-ffffffff81adebdb: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (ffffffff81a98360)
Location: include/linux/filter.h:1408
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81ac9a20)
Location: include/linux/filter.h:1408
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81a98360-ffffffff81a98501: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff81ac9a20-ffffffff81ac9bc1: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/filter.h:1432
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (0)
Location: include/linux/filter.h:1432
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81b53820-ffffffff81b539d9: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff81d3a1ec-ffffffff81d3a216: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
ffffffff81b882a0-ffffffff81b88459: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff81d3bf8b-ffffffff81d3bfb5: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/filter.h:1455
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (0)
Location: include/linux/filter.h:1455
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81ce1340-ffffffff81ce152e: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff81f0696b-ffffffff81f0699b: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
ffffffff81d19420-ffffffff81d1960e: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff81f087c2-ffffffff81f087f2: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/filter.h:1430
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (0)
Location: include/linux/filter.h:1430
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81ea2330-ffffffff81ea251e: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff820ae522-ffffffff820ae552: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
ffffffff81edfda0-ffffffff81edff8e: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff820b024e-ffffffff820b027e: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/filter.h:1430
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (0)
Location: include/linux/filter.h:1430
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81f00b50-ffffffff81f00d3d: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff8212fa33-ffffffff8212fa63: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
ffffffff81f3f1e0-ffffffff81f3f3cd: bpf_sk_lookup_run_v4.constprop.0 (STB_LOCAL)
ffffffff821314da-ffffffff8213150a: bpf_sk_lookup_run_v4.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bpf_sk_lookup_run_v4(struct net *net, int protocol, const __be32 saddr, const __be16 sport, const __be32 daddr, const u16 dport, const int ifindex, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/filter.h:1467
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_lookup_run_sk_lookup
```
**Symbols:**

```
ffffffff81fc4d10-ffffffff81fc4f06: bpf_sk_lookup_run_v4 (STB_LOCAL)
ffffffff822117b1-ffffffff822117e1: bpf_sk_lookup_run_v4.cold (STB_LOCAL)
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
