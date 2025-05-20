# Function: <code>ipv6_change_dsfield</code>

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
In net/ipv6/reassembly.c (ffffffff817ee912)
Location: include/net/dsfield.h:43
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff8185d170)
Location: include/net/dsfield.h:43
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff8188f0cc)
Location: include/net/dsfield.h:43
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff818b55da)
Location: include/net/dsfield.h:43
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff81938350)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff81991370)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv6/reassembly.c (ffffffff819c7ab1)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/xfrm/xfrm_input.c (ffffffff819f4bcf)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5e9d)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffffffff81a35d30)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffff81a2b87f)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cb1d)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffffffff81a6c850)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffff81b1d712)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f6f1)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
```
```
In net/ipv6/reassembly.c (ffffffff81b65a50)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffff81b2bf34)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2dfc1)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
```
```
In net/ipv6/reassembly.c (ffffffff81b741b0)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffff81b19ba2)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b402)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81b62c10)
Location: include/net/dsfield.h:44
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81bdde72)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81bdfaaf)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81c2a6ab)
Location: include/net/dsfield.h:44
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81d74fd6)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7696f)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81dc7b58)
Location: include/net/dsfield.h:44
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81f41d16)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81f430cf)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
```
```
In net/ipv6/reassembly.c (ffffffff81f988c8)
Location: include/net/dsfield.h:44
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81fa15a8)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa28ef)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
```
```
In net/ipv6/reassembly.c (ffffffff81ff92a8)
Location: include/net/dsfield.h:44
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff8206e8c8)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm6_beet_make_header
```
```
In net/xfrm/xfrm_output.c (ffffffff8206fbef)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_make_header
```
```
In net/ipv6/reassembly.c (ffffffff820c6f28)
Location: include/net/dsfield.h:44
Inline: True
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
In net/xfrm/xfrm_input.c (ffff800010cea310)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb79c)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffff800010d35248)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (c0df2760)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3684)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (c0e371d4)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (c000000000e0de08)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f79c)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (c000000000e66ffc)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffe000837f1a)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008390f0)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffffffe000872626)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffff819caf0f)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc1ad)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffffffff81a0bee0)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffff81987cff)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81988f9d)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffffffff819c8ca0)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
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
In net/xfrm/xfrm_input.c (ffffffff81a3598f)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36c2d)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffffffff81a76960)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90ea4)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
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
In net/xfrm/xfrm_input.c (ffffffff81a412fa)
Location: include/net/dsfield.h:44
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a425bd)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/reassembly.c (ffffffff81a83090)
Location: include/net/dsfield.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
</details>
</li>
</ul>

## Differences
