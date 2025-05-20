# Function: <code>nf_ip6_checksum_partial</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__sum16 nf_ip6_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff817fde80)
Location: net/ipv6/netfilter.c:165
Inline: False
```
**Symbols:**

```
ffffffff817fde80-ffffffff817fdf44: nf_ip6_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__sum16 nf_ip6_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff8186d7e0)
Location: net/ipv6/netfilter.c:165
Inline: False
```
**Symbols:**

```
ffffffff8186d7e0-ffffffff8186d8a1: nf_ip6_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__sum16 nf_ip6_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff818a05e0)
Location: net/ipv6/netfilter.c:166
Inline: False
```
**Symbols:**

```
ffffffff818a05e0-ffffffff818a06a1: nf_ip6_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__sum16 nf_ip6_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff818c6c20)
Location: net/ipv6/netfilter.c:166
Inline: False
```
**Symbols:**

```
ffffffff818c6c20-ffffffff818c6cea: nf_ip6_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__sum16 nf_ip6_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff8194a0e0)
Location: net/ipv6/netfilter.c:167
Inline: False
```
**Symbols:**

```
ffffffff8194a0e0-ffffffff8194a1aa: nf_ip6_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__sum16 nf_ip6_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/netfilter.c (ffffffff819a30c0)
Location: net/ipv6/netfilter.c:142
Inline: False
```
**Symbols:**

```
ffffffff819a30c0-ffffffff819a3186: nf_ip6_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff8190ea4a)
Location: net/netfilter/utils.c:96
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81970609)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff819a6ff9)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81a90359)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81a9a229)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81a85523)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81b3fc13)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81ccc433)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81e8c333)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81eea3a0)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81fae150)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffff800010c56a68)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (c0d66218)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (c000000000d5764c)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffe0007c0a74)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81946e69)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81900959)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff81997ff9)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
In net/netfilter/utils.c (ffffffff819bacd9)
Location: net/netfilter/utils.c:97
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
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
</ul>
