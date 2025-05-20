# Function: <code>ip_copy_addrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175e4d8)
Location: net/ipv4/ip_output.c:371
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_make_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817cb510)
Location: net/ipv4/ip_output.c:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fb170)
Location: net/ipv4/ip_output.c:413
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81818440)
Location: net/ipv4/ip_output.c:417
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81818440-ffffffff81818453: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818975a0)
Location: net/ipv4/ip_output.c:417
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff818975a0-ffffffff818975b3: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818eb880)
Location: net/ipv4/ip_output.c:417
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff818eb880-ffffffff818eb893: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81918da0)
Location: net/ipv4/ip_output.c:417
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffffffff81918da0-ffffffff81918db3: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197adf0)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffffffff8197adf0-ffffffff8197ae03: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b1760)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffffffff819b1760-ffffffff819b1773: ip_copy_addrs (STB_LOCAL)
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
In net/ipv4/ip_output.c (ffffffff81a9ef7f)
Location: net/ipv4/ip_output.c:443
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff81aa8ebf)
Location: net/ipv4/ip_output.c:444
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff81a93fb0)
Location: net/ipv4/ip_output.c:445
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff81b4f3de)
Location: net/ipv4/ip_output.c:443
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff81cdcd5b)
Location: net/ipv4/ip_output.c:443
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff81e9d7cb)
Location: net/ipv4/ip_output.c:443
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff81efbf20)
Location: net/ipv4/ip_output.c:445
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
In net/ipv4/ip_output.c (ffffffff81fbfe60)
Location: net/ipv4/ip_output.c:446
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c61c38)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffff800010c61c38-ffff800010c61c68: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d71678)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
c0d71678-c0d716a0: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d65350)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
c000000000d65350-c000000000d65364: ip_copy_addrs (STB_LOCAL)
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
In net/ipv4/ip_output.c (ffffffe0007ccce8)
Location: net/ipv4/ip_output.c:444
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
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
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819515d0)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffffffff819515d0-ffffffff819515e3: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190b0c0)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffffffff8190b0c0-ffffffff8190b0d3: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bbda0)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffffffff819bbda0-ffffffff819bbdb3: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr *iph, const struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c56b0)
Location: net/ipv4/ip_output.c:444
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
**Symbols:**

```
ffffffff819c56b0-ffffffff819c56c3: ip_copy_addrs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
