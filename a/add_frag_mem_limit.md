# Function: <code>add_frag_mem_limit</code>

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
In net/ipv4/ip_fragment.c (ffffffff81759d4a)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff817a2057)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff817ee2d5)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff817c61a6)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fd25)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff8185cb18)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff817f5ca6)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81841275)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff8188ea28)
Location: include/net/inet_frag.h:160
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff81816065)
Location: include/net/inet_frag.h:143
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81862aef)
Location: include/net/inet_frag.h:143
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff818b4daa)
Location: include/net/inet_frag.h:143
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff818952f6)
Location: include/net/inet_frag.h:144
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2c1f)
Location: include/net/inet_frag.h:144
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81937b1a)
Location: include/net/inet_frag.h:144
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff818e96e6)
Location: include/net/inet_frag.h:133
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81939413)
Location: include/net/inet_frag.h:133
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81990aad)
Location: include/net/inet_frag.h:133
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff819164b8)
Location: include/net/inet_frag.h:140
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81969000)
Location: include/net/inet_frag.h:140
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff819c71eb)
Location: include/net/inet_frag.h:140
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff8197834a)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf498)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a36349)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff819aecba)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0601b)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a6ce69)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff81a990cf)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81af572e)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b65de2)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81aa303f)
Location: include/net/inet_frag.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81b024ee)
Location: include/net/inet_frag.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b74552)
Location: include/net/inet_frag.h:150
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81a8e04f)
Location: include/net/inet_frag.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeddfb)
Location: include/net/inet_frag.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81b62fb1)
Location: include/net/inet_frag.h:150
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
In net/ipv4/ip_fragment.c (ffffffff81b4923f)
Location: include/net/inet_frag.h:157
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae1ab)
Location: include/net/inet_frag.h:157
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81c2aa61)
Location: include/net/inet_frag.h:157
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
In net/ipv4/ip_fragment.c (ffffffff81cd68c2)
Location: include/net/inet_frag.h:159
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81d412ee)
Location: include/net/inet_frag.h:159
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81dc7f51)
Location: include/net/inet_frag.h:159
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
In net/ipv4/ip_fragment.c (ffffffff81e96e69)
Location: include/net/inet_frag.h:166
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a09e)
Location: include/net/inet_frag.h:166
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81f98cc3)
Location: include/net/inet_frag.h:166
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
In net/ipv4/ip_fragment.c (ffffffff81ef56a6)
Location: include/net/inet_frag.h:166
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69bbb)
Location: include/net/inet_frag.h:166
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81ff969d)
Location: include/net/inet_frag.h:166
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
In net/ipv4/ip_fragment.c (ffffffff81fb9656)
Location: include/net/inet_frag.h:166
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8203023b)
Location: include/net/inet_frag.h:166
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff820c730d)
Location: include/net/inet_frag.h:166
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
In net/ipv4/ip_fragment.c (ffff800010c5f89c)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffff800010cbefbc)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffff800010d355c4)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In net/ipv4/ip_fragment.c (c0d6e8f8)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c0dca724)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (c0e37684)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In net/ipv4/ip_fragment.c (c000000000d61e50)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c000000000dd97f8)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (c000000000e67628)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffe0007c7700)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffe000814d44)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffe000872956)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff8194eb2a)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5dbb)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a0c4f9)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff8190861a)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f87b)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff819c92b9)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/ipv4/ip_fragment.c (ffffffff819b92fa)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1065b)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a76f79)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90b30)
Location: include/net/inet_frag.h:149
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
In net/ipv4/ip_fragment.c (ffffffff819c2bea)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aeab)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a83599)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
</ul>

## Differences
