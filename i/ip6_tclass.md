# Function: <code>ip6_tclass</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff817dca0d)
Location: include/net/ipv6.h:815
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe6b9)
Location: include/net/ipv6.h:815
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817a8fa0)
Location: include/net/ipv6.h:847
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184a8bd)
Location: include/net/ipv6.h:847
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff8186e049)
Location: include/net/ipv6.h:847
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817d7ade)
Location: include/net/ipv6.h:852
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187c761)
Location: include/net/ipv6.h:852
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff818a0e29)
Location: include/net/ipv6.h:852
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/ipv6.h:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff817f5f9d)
Location: include/net/ipv6.h:853
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a221f)
Location: include/net/ipv6.h:853
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff818c748f)
Location: include/net/ipv6.h:853
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/ipv6.h:853
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81872469)
Location: include/net/ipv6.h:894
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_fib6_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81924bcc)
Location: include/net/ipv6.h:894
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a9af)
Location: include/net/ipv6.h:894
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/ipv6.h:894
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8197028c)
Location: include/net/ipv6.h:893
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d021)
Location: include/net/ipv6.h:893
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff819a38a2)
Location: include/net/ipv6.h:893
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a74c8)
Location: include/net/ipv6.h:893
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5ebc)
Location: include/net/ipv6.h:892
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b2ee5)
Location: include/net/ipv6.h:892
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff819da612)
Location: include/net/ipv6.h:892
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de01f)
Location: include/net/ipv6.h:892
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a124d7)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a21549)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81a4919e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cb8e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a490c7)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a57fb9)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fd9e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8375e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3fb9e)
Location: include/net/ipv6.h:954
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b50277)
Location: include/net/ipv6.h:954
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a799)
Location: include/net/ipv6.h:954
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e553)
Location: include/net/ipv6.h:954
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4e65e)
Location: include/net/ipv6.h:954
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5f30c)
Location: include/net/ipv6.h:954
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81b896e9)
Location: include/net/ipv6.h:954
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d56a)
Location: include/net/ipv6.h:954
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3c4be)
Location: include/net/ipv6.h:955
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4db8b)
Location: include/net/ipv6.h:955
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7852e)
Location: include/net/ipv6.h:955
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c41a)
Location: include/net/ipv6.h:955
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c02db8)
Location: include/net/ipv6.h:966
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c14ea4)
Location: include/net/ipv6.h:966
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81c43010)
Location: include/net/ipv6.h:966
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c4731a)
Location: include/net/ipv6.h:966
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9cc51)
Location: include/net/ipv6.h:1020
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0657)
Location: include/net/ipv6.h:1020
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1c20)
Location: include/net/ipv6.h:1020
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6689)
Location: include/net/ipv6.h:1020
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6b9b7)
Location: include/net/ipv6.h:1053
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f821ab)
Location: include/net/ipv6.h:1053
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb4130)
Location: include/net/ipv6.h:1053
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9386)
Location: include/net/ipv6.h:1053
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcbb07)
Location: include/net/ipv6.h:1050
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe250c)
Location: include/net/ipv6.h:1050
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/fib6_rules.c (ffffffff820148d0)
Location: include/net/ipv6.h:1050
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019ae6)
Location: include/net/ipv6.h:1050
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff82099247)
Location: include/net/ipv6.h:1051
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820b042f)
Location: include/net/ipv6.h:1051
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3a10)
Location: include/net/ipv6.h:1051
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8ab6)
Location: include/net/ipv6.h:1051
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0f8f0)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1d3fc)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b460)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f50c)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1229c)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (c0e22098)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (c0e4c74c)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (c0e50264)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e37010)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4b800)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (c000000000e81228)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86704)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008533ea)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe00086063a)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffe000884496)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887a78)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8757)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7649)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f42e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22dee)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/route.c (ffffffff819a5517)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b4409)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff819dc1ee)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfbae)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a531d7)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a620c9)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89eae)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d86e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f127)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6e5c5)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff81a96b0e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a568)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
</ul>

## Differences
