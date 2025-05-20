# Function: <code>nf_bridge_get</code>

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
In net/core/skbuff.c (ffffffff81705c02)
Location: include/linux/skbuff.h:3316
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff8175c653)
Location: include/linux/skbuff.h:3316
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff817c4bc2)
Location: include/linux/skbuff.h:3316
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff8176c8d2)
Location: include/linux/skbuff.h:3523
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff817c9455)
Location: include/linux/skbuff.h:3523
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81831c98)
Location: include/linux/skbuff.h:3523
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81799aa2)
Location: include/linux/skbuff.h:3575
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff817f8ff6)
Location: include/linux/skbuff.h:3575
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff818636c8)
Location: include/linux/skbuff.h:3575
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff817b8f11)
Location: include/linux/skbuff.h:3633
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff818193f4)
Location: include/linux/skbuff.h:3633
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81888b02)
Location: include/linux/skbuff.h:3633
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff818318da)
Location: include/linux/skbuff.h:3817
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff818979be)
Location: include/linux/skbuff.h:3817
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81909c95)
Location: include/linux/skbuff.h:3817
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff8187bddc)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/ipv4/ip_output.c (ffffffff818ebcfe)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff8196101b)
Location: include/linux/skbuff.h:3827
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
