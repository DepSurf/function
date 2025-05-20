# Function: <code>tcp_collapse_retrans</code>

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
In net/ipv4/tcp_output.c (ffffffff81778710)
Location: net/ipv4/tcp_output.c:2446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff817e5755)
Location: net/ipv4/tcp_output.c:2479
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff81815b96)
Location: net/ipv4/tcp_output.c:2601
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81835f3a)
Location: net/ipv4/tcp_output.c:2676
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b54b3)
Location: net/ipv4/tcp_output.c:2729
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190ac5f)
Location: net/ipv4/tcp_output.c:2710
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff81938f0a)
Location: net/ipv4/tcp_output.c:2741
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff8199d14e)
Location: net/ipv4/tcp_output.c:2768
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff819d3c0e)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_collapse_retrans(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac0050)
Location: net/ipv4/tcp_output.c:2864
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81ac0050-ffffffff81ac0328: tcp_collapse_retrans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_collapse_retrans(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acbab0)
Location: net/ipv4/tcp_output.c:3036
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81acbab0-ffffffff81acbd82: tcp_collapse_retrans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_collapse_retrans(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab6d20)
Location: net/ipv4/tcp_output.c:3041
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81ab6d20-ffffffff81ab6fcd: tcp_collapse_retrans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_collapse_retrans(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b73f10)
Location: net/ipv4/tcp_output.c:3041
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
**Symbols:**

```
ffffffff81b73f10-ffffffff81b741ba: tcp_collapse_retrans (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81d037fb)
Location: net/ipv4/tcp_output.c:3041
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
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
In net/ipv4/tcp_output.c (ffffffff81ec873b)
Location: net/ipv4/tcp_output.c:3043
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
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
In net/ipv4/tcp_output.c (ffffffff81f2725c)
Location: net/ipv4/tcp_output.c:3125
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
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
In net/ipv4/tcp_output.c (ffffffff81febc4c)
Location: net/ipv4/tcp_output.c:3183
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
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
In net/ipv4/tcp_output.c (ffff800010c86630)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (c0d95b08)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (c000000000d93030)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffe0007e7bd0)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff81973a7e)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff8192d54e)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff819de24e)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp_output.c (ffffffff819e7ece)
Location: net/ipv4/tcp_output.c:2795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
</ul>
