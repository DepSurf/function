# Function: <code>security_skb_classify_flow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c990)
Location: security/security.c:1488
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8133c990-ffffffff8133c9db: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371fc0)
Location: security/security.c:1518
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81371fc0-ffffffff8137200b: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813888f0)
Location: security/security.c:1539
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff813888f0-ffffffff8138893b: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d930)
Location: security/security.c:2515
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8139d930-ffffffff8139d97b: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3210)
Location: security/security.c:2376
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff813c3210-ffffffff813c3261: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3dd0)
Location: security/security.c:1698
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff813f3dd0-ffffffff813f3e17: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f090)
Location: security/security.c:2458
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8140f090-ffffffff8140f0d7: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c490)
Location: security/security.c:2477
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8143c490-ffffffff8143c4d9: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456010)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81456010-ffffffff81456057: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8d80)
Location: security/security.c:2851
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff814a8d80-ffffffff814a8dc7: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6380)
Location: security/security.c:2869
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff814c6380-ffffffff814c63c7: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc630)
Location: security/security.c:2932
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff814cc630-ffffffff814cc677: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524ff0)
Location: security/security.c:2940
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81524ff0-ffffffff81525037: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8f90)
Location: security/security.c:2969
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff815b8f90-ffffffff815b8fe5: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816646a0)
Location: security/security.c:2949
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff816646a0-ffffffff816646f5: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169cb80)
Location: security/security.c:5261
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8169cb80-ffffffff8169cbd5: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d94d0)
Location: security/security.c:5452
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff816d94d0-ffffffff816d9525: security_skb_classify_flow (STB_GLOBAL)
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
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105417c8)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffff8000105417c8-ffff80001054182c: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7794)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
c06f7794-c06f77f4: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693aa0)
Location: security/security.c:2516
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
c000000000693aa0-c000000000693b48: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e488)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffe00039e488-ffffffe00039e4d0: security_skb_classify_flow (STB_GLOBAL)
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
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e5f0)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8144e5f0-ffffffff8144e637: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f040)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8143f040-ffffffff8143f087: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a690)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8144a690-ffffffff8144a6d7: security_skb_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void security_skb_classify_flow(struct sk_buff *skb, struct flowi *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461a60)
Location: security/security.c:2516
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81461a60-ffffffff81461aa7: security_skb_classify_flow (STB_GLOBAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct flowi_common *flic</code>
</li>
<li>
<b>Param removed. </b>
<code>struct flowi *fl</code>
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
