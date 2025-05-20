# Function: <code>skb_frag_list_init</code>

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
In net/ipv4/ip_fragment.c (ffffffff8175a172)
Location: include/linux/skbuff.h:2787
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175ccc5)
Location: include/linux/skbuff.h:2787
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff817c7811)
Location: include/linux/skbuff.h:2787
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff817ee541)
Location: include/linux/skbuff.h:2787
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff817c6593)
Location: include/linux/skbuff.h:2980
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817c9ab8)
Location: include/linux/skbuff.h:2980
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81834917)
Location: include/linux/skbuff.h:2980
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff8185cd7d)
Location: include/linux/skbuff.h:2980
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff817f6093)
Location: include/linux/skbuff.h:3033
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817f9a39)
Location: include/linux/skbuff.h:3033
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff818663a9)
Location: include/linux/skbuff.h:3033
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff8188ecbb)
Location: include/linux/skbuff.h:3033
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff818164d4)
Location: include/linux/skbuff.h:3098
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81819e6b)
Location: include/linux/skbuff.h:3098
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff8188a81c)
Location: include/linux/skbuff.h:3098
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff818b5171)
Location: include/linux/skbuff.h:3098
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff8189566c)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818984a4)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff8190ba23)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff81937ee7)
Location: include/linux/skbuff.h:3215
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff818e9838)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff818ec707)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81963196)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff81991064)
Location: include/linux/skbuff.h:3226
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff819168dc)
Location: include/linux/skbuff.h:3303
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81919898)
Location: include/linux/skbuff.h:3303
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81998179)
Location: include/linux/skbuff.h:3303
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/reassembly.c (ffffffff819c77bd)
Location: include/linux/skbuff.h:3303
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
In net/ipv4/ip_output.c (ffffffff8197ad31)
Location: include/linux/skbuff.h:3390
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf3f8)
Location: include/linux/skbuff.h:3390
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a02110)
Location: include/linux/skbuff.h:3390
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff819b16a1)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05f87)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a38120)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81a9bc0d)
Location: include/linux/skbuff.h:3479
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81af569a)
Location: include/linux/skbuff.h:3479
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d0a2)
Location: include/linux/skbuff.h:3479
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81aa5a6d)
Location: include/linux/skbuff.h:3505
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0245a)
Location: include/linux/skbuff.h:3505
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bab2)
Location: include/linux/skbuff.h:3505
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81a9096d)
Location: include/linux/skbuff.h:3569
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedd67)
Location: include/linux/skbuff.h:3569
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81b293e2)
Location: include/linux/skbuff.h:3569
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81b4baed)
Location: include/linux/skbuff.h:3606
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae117)
Location: include/linux/skbuff.h:3606
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81beee10)
Location: include/linux/skbuff.h:3606
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81cd91cd)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41252)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81d874cf)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81e998fd)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a002)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81f5510f)
Location: include/linux/skbuff.h:3876
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81ef822c)
Location: include/linux/skbuff.h:3910
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69b11)
Location: include/linux/skbuff.h:3910
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4b20)
Location: include/linux/skbuff.h:3910
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81fbc14c)
Location: include/linux/skbuff.h:3938
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff82030191)
Location: include/linux/skbuff.h:3938
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff820821c0)
Location: include/linux/skbuff.h:3938
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffff800010c62248)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffff800010cbef34)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffff800010cf829c)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (c0d715dc)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (c0dca6b0)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (c0e015a8)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (c000000000d652a8)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (c000000000dd975c)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (c000000000e20204)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffe0007c9c68)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffe000814cd6)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffe000844b38)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff81951511)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5d27)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff819d77b0)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff8190b001)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f7e7)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81994570)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff819bbce1)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81a105c7)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a42230)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
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
In net/ipv4/ip_output.c (ffffffff819c55f1)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_init
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1ae17)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dec0)
Location: include/linux/skbuff.h:3455
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_init
```
</details>
</li>
</ul>

## Differences
