# Function: <code>skb_forward_csum</code>

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
In net/ipv4/ip_forward.c (ffffffff8175a7ce)
Location: include/linux/skbuff.h:3525
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff817c693e)
Location: include/linux/skbuff.h:3525
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
In net/ipv4/ip_forward.c (ffffffff817c6b8c)
Location: include/linux/skbuff.h:3745
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81833a3e)
Location: include/linux/skbuff.h:3745
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
In net/ipv4/ip_forward.c (ffffffff817f668c)
Location: include/linux/skbuff.h:3804
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff818654b8)
Location: include/linux/skbuff.h:3804
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
In net/ipv4/ip_forward.c (ffffffff81816aa1)
Location: include/linux/skbuff.h:3868
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81889c9a)
Location: include/linux/skbuff.h:3868
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
In net/ipv4/ip_forward.c (ffffffff81895c61)
Location: include/linux/skbuff.h:4059
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff8190ae8a)
Location: include/linux/skbuff.h:4059
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff8194fd46)
Location: include/linux/skbuff.h:4059
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
In net/ipv4/ip_forward.c (ffffffff818e9f21)
Location: include/linux/skbuff.h:4091
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff8196238a)
Location: include/linux/skbuff.h:4091
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff819a8be8)
Location: include/linux/skbuff.h:4091
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
In net/ipv4/ip_forward.c (ffffffff81917343)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81997359)
Location: include/linux/skbuff.h:4260
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff819df70f)
Location: include/linux/skbuff.h:4260
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
In net/ipv4/ip_forward.c (ffffffff81979278)
Location: include/linux/skbuff.h:4367
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a03334)
Location: include/linux/skbuff.h:4367
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e2ae)
Location: include/linux/skbuff.h:4367
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
In net/ipv4/ip_forward.c (ffffffff819afbe8)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a39f04)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a84f0e)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (ffffffff81a99ab8)
Location: include/linux/skbuff.h:4491
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f739)
Location: include/linux/skbuff.h:4491
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ff8e)
Location: include/linux/skbuff.h:4491
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
In net/ipv4/ip_forward.c (ffffffff81aa3a08)
Location: include/linux/skbuff.h:4520
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e18c)
Location: include/linux/skbuff.h:4520
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f40e)
Location: include/linux/skbuff.h:4520
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
In net/ipv4/ip_forward.c (ffffffff81a8eaee)
Location: include/linux/skbuff.h:4584
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c914)
Location: include/linux/skbuff.h:4584
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e181)
Location: include/linux/skbuff.h:4584
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
In net/ipv4/ip_forward.c (ffffffff81b49cfd)
Location: include/linux/skbuff.h:4623
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2a5d)
Location: include/linux/skbuff.h:4623
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81c497a1)
Location: include/linux/skbuff.h:4623
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
In net/ipv4/ip_forward.c (ffffffff81cd723a)
Location: include/linux/skbuff.h:5045
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b621)
Location: include/linux/skbuff.h:5045
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81de8f83)
Location: include/linux/skbuff.h:5045
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
In net/ipv4/ip_forward.c (ffffffff81e9785b)
Location: include/linux/skbuff.h:4941
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81f5964d)
Location: include/linux/skbuff.h:4941
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc6b3)
Location: include/linux/skbuff.h:4941
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
In net/ipv4/ip_forward.c (ffffffff81ef6098)
Location: include/linux/skbuff.h:4904
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81fb92fe)
Location: include/linux/skbuff.h:4904
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff8201cfa3)
Location: include/linux/skbuff.h:4904
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
In net/ipv4/ip_forward.c (ffffffff81fba028)
Location: include/linux/skbuff.h:4944
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff8208687e)
Location: include/linux/skbuff.h:4944
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff820ebf86)
Location: include/linux/skbuff.h:4944
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
In net/ipv4/ip_forward.c (ffff800010c602a0)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffff800010cfae9c)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffff800010d50fa0)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (c0d6fb58)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (c0e017a4)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (c0e51b20)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (c000000000d631a8)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (c000000000e2233c)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (c000000000e88ec4)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (ffffffe0007c854a)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffe000845a32)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffe000889244)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (ffffffff8194fa58)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff819d9594)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a2459e)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (ffffffff81909548)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81996354)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff819e135e)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (ffffffff819ba228)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a44014)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f01e)
Location: include/linux/skbuff.h:4451
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
In net/ipv4/ip_forward.c (ffffffff819c3b18)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fcb5)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bd9e)
Location: include/linux/skbuff.h:4451
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
</details>
</li>
</ul>

## Differences
