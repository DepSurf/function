# Function: <code>neigh_hh_output</code>

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
In net/ipv4/ip_output.c (ffffffff8175d0fd)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff817c528f)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (ffffffff817c9ebd)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81831e7f)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (ffffffff817f91b7)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81863e23)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (ffffffff8181964e)
Location: include/net/neighbour.h:452
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff8188946f)
Location: include/net/neighbour.h:452
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (ffffffff81897c79)
Location: include/net/neighbour.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff8190995f)
Location: include/net/neighbour.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:454
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:454
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:461
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:461
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:463
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:463
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int neigh_hh_output(const struct hh_cache *hh, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9b650)
Location: include/net/neighbour.h:461
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c380)
Location: include/net/neighbour.h:461
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81a9b650-ffffffff81a9b770: neigh_hh_output (STB_LOCAL)
ffffffff81b2c380-ffffffff81b2c4a0: neigh_hh_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
int neigh_hh_output(const struct hh_cache *hh, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29fc0)
Location: include/net/neighbour.h:462
Inline: False
```
```
In net/ipv4/ip_output.c (ffffffff81aa54c0)
Location: include/net/neighbour.h:462
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ae30)
Location: include/net/neighbour.h:462
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81a29fc0-ffffffff81a2a0ce: neigh_hh_output (STB_LOCAL)
ffffffff81aa54c0-ffffffff81aa55ce: neigh_hh_output (STB_LOCAL)
ffffffff81b3ae30-ffffffff81b3af3e: neigh_hh_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
int neigh_hh_output(const struct hh_cache *hh, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a11210)
Location: include/net/neighbour.h:462
Inline: False
```
```
In net/ipv4/ip_output.c (ffffffff81a90580)
Location: include/net/neighbour.h:462
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81b28a60)
Location: include/net/neighbour.h:462
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81a11210-ffffffff81a1131e: neigh_hh_output (STB_LOCAL)
ffffffff81a90580-ffffffff81a9068e: neigh_hh_output (STB_LOCAL)
ffffffff81b28a60-ffffffff81b28b6e: neigh_hh_output (STB_LOCAL)
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
In net/core/filter.c (0)
Location: include/net/neighbour.h:463
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:463
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:463
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
int neigh_hh_output(const struct hh_cache *hh, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3d2c0)
Location: include/net/neighbour.h:496
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/ip_output.c (ffffffff81cd8d50)
Location: include/net/neighbour.h:496
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81d87000)
Location: include/net/neighbour.h:496
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81c3d2c0-ffffffff81c3d3c1: neigh_hh_output (STB_LOCAL)
ffffffff81cd8d50-ffffffff81cd8e51: neigh_hh_output (STB_LOCAL)
ffffffff81d87000-ffffffff81d87101: neigh_hh_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int neigh_hh_output(const struct hh_cache *hh, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df50f0)
Location: include/net/neighbour.h:493
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/ip_output.c (ffffffff81e99690)
Location: include/net/neighbour.h:493
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81f54fa0)
Location: include/net/neighbour.h:493
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81df50f0-ffffffff81df51de: neigh_hh_output (STB_LOCAL)
ffffffff81e99690-ffffffff81e9977e: neigh_hh_output (STB_LOCAL)
ffffffff81f54fa0-ffffffff81f5508e: neigh_hh_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int neigh_hh_output(const struct hh_cache *hh, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e66ae0)
Location: include/net/neighbour.h:491
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/ip_output.c (ffffffff81ef7f90)
Location: include/net/neighbour.h:491
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81fb49b0)
Location: include/net/neighbour.h:491
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81e66ae0-ffffffff81e66bce: neigh_hh_output (STB_LOCAL)
ffffffff81ef7f90-ffffffff81ef807e: neigh_hh_output (STB_LOCAL)
ffffffff81fb49b0-ffffffff81fb4a9e: neigh_hh_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int neigh_hh_output(const struct hh_cache *hh, struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f25c90)
Location: include/net/neighbour.h:489
Inline: False
Direct callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/ip_output.c (ffffffff81fbbfe0)
Location: include/net/neighbour.h:489
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff82082050)
Location: include/net/neighbour.h:489
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
**Symbols:**

```
ffffffff81f25c90-ffffffff81f25d7e: neigh_hh_output (STB_LOCAL)
ffffffff81fbbfe0-ffffffff81fbc0ce: neigh_hh_output (STB_LOCAL)
ffffffff82082050-ffffffff8208213e: neigh_hh_output (STB_LOCAL)
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (ffffffe0007cadd8)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffe000843dbe)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
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
In net/ipv4/ip_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/neighbour.h:462
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
