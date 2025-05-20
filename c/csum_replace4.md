# Function: <code>csum_replace4</code>

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
In net/core/utils.c (ffffffff8172fdf7)
Location: include/net/checksum.h:123
Inline: True
```
```
In net/core/filter.c (ffffffff817323ad)
Location: include/net/checksum.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff8179a547)
Location: include/net/checksum.h:128
Inline: True
```
```
In net/core/filter.c (ffffffff8179c8bc)
Location: include/net/checksum.h:128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff817c82e7)
Location: include/net/checksum.h:128
Inline: True
```
```
In net/core/filter.c (ffffffff817cbb5c)
Location: include/net/checksum.h:128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff817e6c37)
Location: include/net/checksum.h:128
Inline: True
```
```
In net/core/filter.c (ffffffff817eac3c)
Location: include/net/checksum.h:128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff81861b77)
Location: include/net/checksum.h:128
Inline: True
```
```
In net/core/filter.c (ffffffff81866e48)
Location: include/net/checksum.h:128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff818ad797)
Location: include/net/checksum.h:128
Inline: True
```
```
In net/core/filter.c (ffffffff818b67e9)
Location: include/net/checksum.h:128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff818d19f7)
Location: include/net/checksum.h:128
Inline: True
```
```
In net/core/filter.c (ffffffff818db9f4)
Location: include/net/checksum.h:128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff8191ec87)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff81928e85)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff81950ec7)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff8195b565)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff81a21c26)
Location: include/net/checksum.h:118
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a2f9f5)
Location: include/net/checksum.h:118
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff81a21fa6)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a322c5)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81ae454c)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
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
In net/core/utils.c (ffffffff81a092d6)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a19422)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81acf88f)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
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
In net/core/utils.c (ffffffff81abb777)
Location: include/net/checksum.h:127
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81aca1d2)
Location: include/net/checksum.h:127
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e2af)
Location: include/net/checksum.h:127
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
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
In net/core/utils.c (ffffffff81c36057)
Location: include/net/checksum.h:129
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81c46d0c)
Location: include/net/checksum.h:129
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f4bf)
Location: include/net/checksum.h:129
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
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
In net/core/utils.c (ffffffff81de96e7)
Location: include/net/checksum.h:129
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81dfb24c)
Location: include/net/checksum.h:129
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81ee667f)
Location: include/net/checksum.h:129
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
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
In net/core/utils.c (ffffffff81e5aef6)
Location: include/net/checksum.h:131
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81e6d05f)
Location: include/net/checksum.h:131
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81f45ebf)
Location: include/net/checksum.h:131
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
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
In net/core/utils.c (ffffffff81f1a2b6)
Location: include/net/checksum.h:131
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81f2c8cf)
Location: include/net/checksum.h:131
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff8200bfff)
Location: include/net/checksum.h:131
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
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
In net/core/utils.c (ffff800010bf2b10)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffff800010bfc560)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (c0d0b328)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (c0d1734c)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (c000000000cd7950)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (c000000000ce4e00)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffe000774552)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffe000779272)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff818f0e97)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff818fb535)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff818aacd7)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff818b5365)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff81941ec7)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff8194c565)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff819637c7)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff8196df25)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
</details>
</li>
</ul>

## Differences
