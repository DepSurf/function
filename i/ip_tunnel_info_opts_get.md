# Function: <code>ip_tunnel_info_opts_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179b9bb)
Location: include/net/ip_tunnels.h:428
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/filter.c (ffffffff817cbff1)
Location: include/net/ip_tunnels.h:449
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/filter.c (ffffffff817ebb2a)
Location: include/net/ip_tunnels.h:451
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/filter.c (ffffffff81866a8a)
Location: include/net/ip_tunnels.h:458
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/filter.c (ffffffff818b557a)
Location: include/net/ip_tunnels.h:490
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff818a923a)
Location: include/net/ip_tunnels.h:492
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818dacba)
Location: include/net/ip_tunnels.h:492
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff818f49a3)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff819277a1)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff8192695a)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81959e61)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff819fad65)
Location: include/net/ip_tunnels.h:497
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2d6f1)
Location: include/net/ip_tunnels.h:497
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff819fa975)
Location: include/net/ip_tunnels.h:497
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a2f1b1)
Location: include/net/ip_tunnels.h:497
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff819e0b75)
Location: include/net/ip_tunnels.h:497
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81a17571)
Location: include/net/ip_tunnels.h:497
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff81a90ef5)
Location: include/net/ip_tunnels.h:498
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81ac8ac1)
Location: include/net/ip_tunnels.h:498
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff81c06fac)
Location: include/net/ip_tunnels.h:509
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81c45ea7)
Location: include/net/ip_tunnels.h:509
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
void ip_tunnel_info_opts_get(void *to, const struct ip_tunnel_info *info);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db64e0)
Location: include/net/ip_tunnels.h:521
Inline: False
Direct callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81df44c0)
Location: include/net/ip_tunnels.h:521
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
```
**Symbols:**

```
ffffffff81db64e0-ffffffff81db6583: ip_tunnel_info_opts_get (STB_LOCAL)
ffffffff81df44c0-ffffffff81df4563: ip_tunnel_info_opts_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void ip_tunnel_info_opts_get(void *to, const struct ip_tunnel_info *info);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e26890)
Location: include/net/ip_tunnels.h:525
Inline: False
Direct callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81e65f60)
Location: include/net/ip_tunnels.h:525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
```
**Symbols:**

```
ffffffff81e26890-ffffffff81e26933: ip_tunnel_info_opts_get (STB_LOCAL)
ffffffff81e65f60-ffffffff81e66003: ip_tunnel_info_opts_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void ip_tunnel_info_opts_get(void *to, const struct ip_tunnel_info *info);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee4820)
Location: include/net/ip_tunnels.h:508
Inline: False
Direct callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff81f25110)
Location: include/net/ip_tunnels.h:508
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
```
**Symbols:**

```
ffffffff81ee4820-ffffffff81ee48c3: ip_tunnel_info_opts_get (STB_LOCAL)
ffffffff81f25110-ffffffff81f251b3: ip_tunnel_info_opts_get (STB_LOCAL)
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
In net/core/flow_dissector.c (ffff800010bc2cbc)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffff800010bfba8c)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (c0cddfa4)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c0d16560)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (c000000000c9ccfc)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (c000000000ce40b4)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffe00074f9c6)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffe00077e08a)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff818c695a)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818f9e31)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff8188089a)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff818b3c61)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff8191795a)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff8194ae61)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
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
In net/core/flow_dissector.c (ffffffff81938b6a)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissect_tunnel_info
```
```
In net/core/filter.c (ffffffff8196c771)
Location: include/net/ip_tunnels.h:493
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_tunnel_opt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
