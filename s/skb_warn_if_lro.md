# Function: <code>skb_warn_if_lro</code>

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
In net/ipv4/ip_forward.c (ffffffff8175a770)
Location: include/linux/skbuff.h:3511
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff817c68e9)
Location: include/linux/skbuff.h:3511
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv4/ip_forward.c (ffffffff817c6b2e)
Location: include/linux/skbuff.h:3731
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff818339ea)
Location: include/linux/skbuff.h:3731
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv4/ip_forward.c (ffffffff817f662e)
Location: include/linux/skbuff.h:3790
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81865464)
Location: include/linux/skbuff.h:3790
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv4/ip_forward.c (ffffffff81816a3e)
Location: include/linux/skbuff.h:3854
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81889c4a)
Location: include/linux/skbuff.h:3854
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv4/ip_forward.c (ffffffff81895bfe)
Location: include/linux/skbuff.h:4045
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff8190ae3a)
Location: include/linux/skbuff.h:4045
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff8194fd21)
Location: include/linux/skbuff.h:4045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff818e9ebe)
Location: include/linux/skbuff.h:4077
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff8196233c)
Location: include/linux/skbuff.h:4077
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff819a8bc3)
Location: include/linux/skbuff.h:4077
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff819172ee)
Location: include/linux/skbuff.h:4246
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81997312)
Location: include/linux/skbuff.h:4246
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff819df6ed)
Location: include/linux/skbuff.h:4246
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff8197921e)
Location: include/linux/skbuff.h:4353
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a032ea)
Location: include/linux/skbuff.h:4353
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e287)
Location: include/linux/skbuff.h:4353
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff819afb8e)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a39eba)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a84ee7)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81a99a5e)
Location: include/linux/skbuff.h:4477
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f6ef)
Location: include/linux/skbuff.h:4477
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ff67)
Location: include/linux/skbuff.h:4477
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81aa39ae)
Location: include/linux/skbuff.h:4506
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e144)
Location: include/linux/skbuff.h:4506
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f3e7)
Location: include/linux/skbuff.h:4506
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81a8ea6e)
Location: include/linux/skbuff.h:4570
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c8db)
Location: include/linux/skbuff.h:4570
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e157)
Location: include/linux/skbuff.h:4570
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81b49c6e)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2a21)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81c49777)
Location: include/linux/skbuff.h:4609
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81cd71de)
Location: include/linux/skbuff.h:5031
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b5cf)
Location: include/linux/skbuff.h:5031
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81de8f5e)
Location: include/linux/skbuff.h:5031
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81e977ae)
Location: include/linux/skbuff.h:4927
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81f595df)
Location: include/linux/skbuff.h:4927
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc68e)
Location: include/linux/skbuff.h:4927
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81ef5fde)
Location: include/linux/skbuff.h:4890
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81fb928f)
Location: include/linux/skbuff.h:4890
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff8201cf7e)
Location: include/linux/skbuff.h:4890
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff81fb9f6e)
Location: include/linux/skbuff.h:4930
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff8208680f)
Location: include/linux/skbuff.h:4930
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff820ebf61)
Location: include/linux/skbuff.h:4930
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffff800010c60254)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffff800010cfae64)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffff800010d50f7c)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (c0d6fb04)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (c0e01760)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (c0e51af8)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (c000000000d6314c)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (c000000000e222f4)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (c000000000e88e94)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffe0007c850e)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffe000845a04)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffe00088922e)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff8194f9fe)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff819d954a)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a24577)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff819094ee)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff8199630a)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff819e1337)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff819ba1ce)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a43fca)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a8eff7)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/ipv4/ip_forward.c (ffffffff819c3abe)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fc6b)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bd77)
Location: include/linux/skbuff.h:4437
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
</details>
</li>
</ul>

## Differences
