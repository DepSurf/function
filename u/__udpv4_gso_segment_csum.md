# Function: <code>__udpv4_gso_segment_csum</code>

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
void __udpv4_gso_segment_csum(struct sk_buff *seg, __be32 *oldip, __be32 *newip, __be16 *oldport, __be16 *newport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae44f0)
Location: net/ipv4/udp_offload.c:190
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_list_csum
```
**Symbols:**

```
ffffffff81ae44f0-ffffffff81ae45f8: __udpv4_gso_segment_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff *seg, __be32 *oldip, __be32 *newip, __be16 *oldport, __be16 *newport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81acf830)
Location: net/ipv4/udp_offload.c:190
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81acf830-ffffffff81acf93b: __udpv4_gso_segment_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff *seg, __be32 *oldip, __be32 *newip, __be16 *oldport, __be16 *newport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8e250)
Location: net/ipv4/udp_offload.c:190
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81b8e250-ffffffff81b8e35b: __udpv4_gso_segment_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff *seg, __be32 *oldip, __be32 *newip, __be16 *oldport, __be16 *newport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d1f460)
Location: net/ipv4/udp_offload.c:191
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81d1f460-ffffffff81d1f583: __udpv4_gso_segment_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff *seg, __be32 *oldip, __be32 *newip, __be16 *oldport, __be16 *newport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee6620)
Location: net/ipv4/udp_offload.c:191
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81ee6620-ffffffff81ee6743: __udpv4_gso_segment_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff *seg, __be32 *oldip, __be32 *newip, __be16 *oldport, __be16 *newport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f45e60)
Location: net/ipv4/udp_offload.c:192
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81f45e60-ffffffff81f45f83: __udpv4_gso_segment_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __udpv4_gso_segment_csum(struct sk_buff *seg, __be32 *oldip, __be32 *newip, __be16 *oldport, __be16 *newport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200bfa0)
Location: net/ipv4/udp_offload.c:192
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff8200bfa0-ffffffff8200c0c3: __udpv4_gso_segment_csum (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
