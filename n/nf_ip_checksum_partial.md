# Function: <code>nf_ip_checksum_partial</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__sum16 nf_ip_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff817ac460)
Location: net/ipv4/netfilter.c:154
Inline: False
```
**Symbols:**

```
ffffffff817ac460-ffffffff817ac4e6: nf_ip_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__sum16 nf_ip_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff818197a0)
Location: net/ipv4/netfilter.c:154
Inline: False
```
**Symbols:**

```
ffffffff818197a0-ffffffff8181982a: nf_ip_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__sum16 nf_ip_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff8184b060)
Location: net/ipv4/netfilter.c:157
Inline: False
```
**Symbols:**

```
ffffffff8184b060-ffffffff8184b0ea: nf_ip_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__sum16 nf_ip_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff8186eae0)
Location: net/ipv4/netfilter.c:158
Inline: False
```
**Symbols:**

```
ffffffff8186eae0-ffffffff8186eb6a: nf_ip_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__sum16 nf_ip_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff818ef4a0)
Location: net/ipv4/netfilter.c:158
Inline: False
```
**Symbols:**

```
ffffffff818ef4a0-ffffffff818ef52a: nf_ip_checksum_partial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__sum16 nf_ip_checksum_partial(struct sk_buff *skb, unsigned int hook, unsigned int dataoff, unsigned int len, u_int8_t protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netfilter.c (ffffffff81945e40)
Location: net/ipv4/netfilter.c:132
Inline: False
```
**Symbols:**

```
ffffffff81945e40-ffffffff81945ecb: nf_ip_checksum_partial (STB_GLOBAL)
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
In net/netfilter/utils.c (ffffffff8190eadb)
Location: net/netfilter/utils.c:42
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
In net/netfilter/utils.c (ffffffff819706a3)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff819a7093)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81a903f3)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81a9a2c3)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81a855b6)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81b3fca6)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81ccc4e4)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81e8c3e4)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81eea3e9)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81fae199)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffff800010c56b1c)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (c0d662c0)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (c000000000d57740)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffe0007c0afe)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81946f03)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff819009f3)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff81998093)
Location: net/netfilter/utils.c:43
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
In net/netfilter/utils.c (ffffffff819bad73)
Location: net/netfilter/utils.c:43
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
