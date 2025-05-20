# Function: <code>tcp_synack_options</code>

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
In net/ipv4/tcp_output.c (ffffffff81774be5)
Location: net/ipv4/tcp_output.c:611
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff817e1b66)
Location: net/ipv4/tcp_output.c:609
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff81812066)
Location: net/ipv4/tcp_output.c:609
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff818323bd)
Location: net/ipv4/tcp_output.c:610
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff818b14f9)
Location: net/ipv4/tcp_output.c:648
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff81906d33)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff81934ee7)
Location: net/ipv4/tcp_output.c:657
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff81998ea5)
Location: net/ipv4/tcp_output.c:657
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff819cf9c5)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_md5sig_key *md5, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abb880)
Location: net/ipv4/tcp_output.c:698
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81abb880-ffffffff81abba5e: tcp_synack_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_md5sig_key *md5, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac6c40)
Location: net/ipv4/tcp_output.c:841
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81ac6c40-ffffffff81ac6e6a: tcp_synack_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_md5sig_key *md5, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab1e50)
Location: net/ipv4/tcp_output.c:841
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81ab1e50-ffffffff81ab2074: tcp_synack_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_md5sig_key *md5, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:841
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81b6ec70-ffffffff81b6eebc: tcp_synack_options (STB_LOCAL)
ffffffff81d3ae03-ffffffff81d3ae7a: tcp_synack_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_md5sig_key *md5, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:840
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81cfe2b0-ffffffff81cfe502: tcp_synack_options (STB_LOCAL)
ffffffff81f076da-ffffffff81f07751: tcp_synack_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_md5sig_key *md5, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:840
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81ec2f30-ffffffff81ec317d: tcp_synack_options (STB_LOCAL)
ffffffff820af152-ffffffff820af1c9: tcp_synack_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_md5sig_key *md5, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:842
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81f211a0-ffffffff81f213ed: tcp_synack_options (STB_LOCAL)
ffffffff8213051b-ffffffff82130592: tcp_synack_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int tcp_synack_options(const struct sock *sk, struct request_sock *req, unsigned int mss, struct sk_buff *skb, struct tcp_out_options *opts, const struct tcp_key *key, struct tcp_fastopen_cookie *foc, enum tcp_synack_type synack_type, struct sk_buff *syn_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:893
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
**Symbols:**

```
ffffffff81fe64e0-ffffffff81fe67c4: tcp_synack_options (STB_LOCAL)
ffffffff82211f3c-ffffffff82211fde: tcp_synack_options.cold (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffff800010c82ba8)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (c0d915a4)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (c000000000d8da04)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffe0007e43bc)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff8196f835)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff81929305)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff819da005)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
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
In net/ipv4/tcp_output.c (ffffffff819e3c7a)
Location: net/ipv4/tcp_output.c:660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff *syn_skb</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcp_key *key</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct tcp_md5sig_key *md5</code>
</li>
</ul>
</details>
</li>
</ul>
