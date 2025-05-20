# Function: <code>nf_ip_reroute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int nf_ip_reroute(struct net *net, struct sk_buff *skb, const struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff817ac530)
Location: net/ipv4/netfilter.c:106
Inline: True
```
**Symbols:**

```
ffffffff817ac530-ffffffff817ac586: nf_ip_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int nf_ip_reroute(struct net *net, struct sk_buff *skb, const struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff81819870)
Location: net/ipv4/netfilter.c:106
Inline: True
```
**Symbols:**

```
ffffffff81819870-ffffffff818198c6: nf_ip_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int nf_ip_reroute(struct net *net, struct sk_buff *skb, const struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff8184b130)
Location: net/ipv4/netfilter.c:109
Inline: True
```
**Symbols:**

```
ffffffff8184b130-ffffffff8184b186: nf_ip_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int nf_ip_reroute(struct net *net, struct sk_buff *skb, const struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff8186ebb0)
Location: net/ipv4/netfilter.c:110
Inline: True
```
**Symbols:**

```
ffffffff8186ebb0-ffffffff8186ec06: nf_ip_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int nf_ip_reroute(struct net *net, struct sk_buff *skb, const struct nf_queue_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff818ef570)
Location: net/ipv4/netfilter.c:110
Inline: True
```
**Symbols:**

```
ffffffff818ef570-ffffffff818ef5c6: nf_ip_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nf_ip_reroute(struct sk_buff *skb, const struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff81945ed0)
Location: net/ipv4/netfilter.c:83
Inline: True
Direct callers:
  - net/netfilter/utils.c:nf_reroute
```
**Symbols:**

```
ffffffff81945ed0-ffffffff81945f27: nf_ip_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nf_ip_reroute(struct sk_buff *skb, const struct nf_queue_entry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff81976070)
Location: net/ipv4/netfilter.c:83
Inline: True
Direct callers:
  - net/netfilter/utils.c:nf_reroute
```
**Symbols:**

```
ffffffff81976070-ffffffff819760c7: nf_ip_reroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819707b2)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (ffffffff819a71a2)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a90502)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a9a3d2)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a856c2)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81b3fdb2)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81ccc640)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81e8c560)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81eea760)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81fae510)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (ffff800010c56cdc)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (c0d663e4)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (c000000000d57958)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (ffffffe0007c0c20)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (ffffffff81947012)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81900b02)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (ffffffff819981a2)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
In net/netfilter/utils.c (ffffffff819bae82)
Location: net/netfilter/utils.c:182
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_reroute
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, entry</code> ➡️ <code>skb, entry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
