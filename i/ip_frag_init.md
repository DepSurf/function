# Function: <code>ip_frag_init</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197b80d)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff8197ad90-ffffffff8197ade5: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b1eca)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff819b1700-ffffffff819b1758: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9c748)
Location: net/ipv4/ip_output.c:646
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81a9b5f0-ffffffff81a9b648: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa65ae)
Location: net/ipv4/ip_output.c:653
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81aa5460-ffffffff81aa54b8: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9172e)
Location: net/ipv4/ip_output.c:654
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81a90520-ffffffff81a90578: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4cafe)
Location: net/ipv4/ip_output.c:641
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81b4b790-ffffffff81b4b7e8: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cda225)
Location: net/ipv4/ip_output.c:641
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81cd8ce0-ffffffff81cd8d4d: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9a9e5)
Location: net/ipv4/ip_output.c:641
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81e993f0-ffffffff81e9945d: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81ef9386)
Location: net/ipv4/ip_output.c:643
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81ef7ce0-ffffffff81ef7d4d: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fbd2a3)
Location: net/ipv4/ip_output.c:644
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81fbbc00-ffffffff81fbbc6d: ip_frag_init (STB_GLOBAL)
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
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c63be0)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffff800010c61ba8-ffff800010c61c38: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d72124)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
c0d71610-c0d71678: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d65da4)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
c000000000d652f0-c000000000d65344: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007ca49a)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffe0007c9cd6-ffffffe0007c9d6a: ip_frag_init (STB_GLOBAL)
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
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81951d3a)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81951570-ffffffff819515c8: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190b82a)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff8190b060-ffffffff8190b0b8: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bc50a)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff819bbd40-ffffffff819bbd98: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ip_frag_init(struct sk_buff *skb, unsigned int hlen, unsigned int ll_rs, unsigned int mtu, bool DF, struct ip_frag_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c5e1a)
Location: net/ipv4/ip_output.c:647
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff819c5650-ffffffff819c56a8: ip_frag_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool DF</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, hlen, ll_rs, mtu, state</code> ➡️ <code>skb, hlen, ll_rs, mtu, DF, state</code>
</li>
</ul>
</details>
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
