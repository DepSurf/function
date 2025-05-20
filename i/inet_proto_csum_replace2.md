# Function: <code>inet_proto_csum_replace2</code>

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
In net/core/filter.c (ffffffff817327fc)
Location: include/net/checksum.h:150
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
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
In net/core/filter.c (ffffffff8179c6f3)
Location: include/net/checksum.h:155
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
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
In net/core/filter.c (ffffffff817cb993)
Location: include/net/checksum.h:155
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
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
In net/core/filter.c (ffffffff817eaa6b)
Location: include/net/checksum.h:155
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
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
In net/core/filter.c (ffffffff81866c57)
Location: include/net/checksum.h:155
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
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
In net/core/filter.c (ffffffff818b5d2f)
Location: include/net/checksum.h:155
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
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
In net/core/filter.c (ffffffff818db8e9)
Location: include/net/checksum.h:155
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81928d73)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195b453)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fbd3)
Location: include/net/checksum.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
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
In net/core/filter.c (ffffffff81a324a3)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81ae45bb)
Location: include/net/checksum.h:151
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
In net/core/filter.c (ffffffff81a195f3)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81acf8fe)
Location: include/net/checksum.h:151
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
In net/core/filter.c (ffffffff81aca0c3)
Location: include/net/checksum.h:160
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e31e)
Location: include/net/checksum.h:160
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
In net/core/filter.c (ffffffff81c46c28)
Location: include/net/checksum.h:162
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f546)
Location: include/net/checksum.h:162
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
In net/core/filter.c (ffffffff81dfb158)
Location: include/net/checksum.h:162
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6706)
Location: include/net/checksum.h:162
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
In net/core/filter.c (ffffffff81e6ced0)
Location: include/net/checksum.h:164
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81f45f46)
Location: include/net/checksum.h:164
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
In net/core/filter.c (ffffffff81f2c740)
Location: include/net/checksum.h:164
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff8200c086)
Location: include/net/checksum.h:164
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfc784)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d17560)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce50f0)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f4e4)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fb423)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5253)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194c453)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196de13)
Location: include/net/checksum.h:151
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l4_csum_replace
```
</details>
</li>
</ul>

## Differences
