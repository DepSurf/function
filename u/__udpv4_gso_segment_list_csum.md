# Function: <code>__udpv4_gso_segment_list_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__udpv4_gso_segment_list_csum(struct sk_buff *segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae4600)
Location: net/ipv4/udp_offload.c:217
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81ae4600-ffffffff81ae4719: __udpv4_gso_segment_list_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad04f9)
Location: net/ipv4/udp_offload.c:217
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8ef17)
Location: net/ipv4/udp_offload.c:217
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d1fb88)
Location: net/ipv4/udp_offload.c:218
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee6d78)
Location: net/ipv4/udp_offload.c:218
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f4661f)
Location: net/ipv4/udp_offload.c:219
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200c75f)
Location: net/ipv4/udp_offload.c:219
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
</details>
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
<b>Regular</b>
<ul>
</ul>
