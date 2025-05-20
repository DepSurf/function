# Function: <code>INET_ECN_set_ce</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81924aab)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81956edb)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2bf40)
Location: include/net/inet_ecn.h:174
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81a2bf40-ffffffff81a2c136: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d520)
Location: include/net/inet_ecn.h:172
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81a2d520-ffffffff81a2d719: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a14880)
Location: include/net/inet_ecn.h:172
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81a14880-ffffffff81a14a69: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac53e0)
Location: include/net/inet_ecn.h:172
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81ac53e0-ffffffff81ac55c9: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c42720)
Location: include/net/inet_ecn.h:172
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81c42720-ffffffff81c42911: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df7700)
Location: include/net/inet_ecn.h:172
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81df7700-ffffffff81df78f1: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e69410)
Location: include/net/inet_ecn.h:172
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81e69410-ffffffff81e695fd: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f28960)
Location: include/net/inet_ecn.h:172
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
**Symbols:**

```
ffffffff81f28960-ffffffff81f28b4d: INET_ECN_set_ce (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf86b0)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d122f8)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdf5d0)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077a3ba)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f6eab)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/vxlan.c (ffffffff81772de1)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In net/core/filter.c (ffffffff818b0cdb)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967e05)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81947edb)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819697eb)
Location: include/net/inet_ecn.h:143
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
