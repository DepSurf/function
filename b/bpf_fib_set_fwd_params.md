# Function: <code>bpf_fib_set_fwd_params</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818b2840)
Location: net/core/filter.c:4167
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff818b2840-ffffffff818b287d: bpf_fib_set_fwd_params.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818d75e0)
Location: net/core/filter.c:4452
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff818d75e0-ffffffff818d761d: bpf_fib_set_fwd_params.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff819250f0)
Location: net/core/filter.c:4590
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff819250f0-ffffffff8192512d: bpf_fib_set_fwd_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81957520)
Location: net/core/filter.c:4599
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81957520-ffffffff8195755d: bpf_fib_set_fwd_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a28220)
Location: net/core/filter.c:4725
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81a28220-ffffffff81a28265: bpf_fib_set_fwd_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a28a40)
Location: net/core/filter.c:5269
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81a28a40-ffffffff81a28a7c: bpf_fib_set_fwd_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0fe30)
Location: net/core/filter.c:5245
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81a0fe30-ffffffff81a0fe74: bpf_fib_set_fwd_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac2100)
Location: net/core/filter.c:5369
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81ac2100-ffffffff81ac2144: bpf_fib_set_fwd_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3c690)
Location: net/core/filter.c:5678
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81c3c690-ffffffff81c3c6e0: bpf_fib_set_fwd_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df4580)
Location: net/core/filter.c:5692
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81df4580-ffffffff81df45d0: bpf_fib_set_fwd_params (STB_LOCAL)
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
In net/core/filter.c (ffffffff81e6fd54)
Location: net/core/filter.c:5746
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
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
In net/core/filter.c (ffffffff81f2f51e)
Location: net/core/filter.c:5820
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffff800010bf8a48)
Location: net/core/filter.c:4599
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffff800010bf8a48-ffff800010bf8ab4: bpf_fib_set_fwd_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d102dc)
Location: net/core/filter.c:4599
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
c0d102dc-c0d1032c: bpf_fib_set_fwd_params (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_fib_set_fwd_params(struct bpf_fib_lookup *params, const struct neighbour *neigh, const struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdcc50)
Location: net/core/filter.c:4599
Inline: False
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
c000000000cdcc50-c000000000cdcc98: bpf_fib_set_fwd_params (STB_LOCAL)
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
In net/core/filter.c (ffffffe000780442)
Location: net/core/filter.c:4599
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818f74f0)
Location: net/core/filter.c:4599
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff818f74f0-ffffffff818f752d: bpf_fib_set_fwd_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818b1320)
Location: net/core/filter.c:4599
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff818b1320-ffffffff818b135d: bpf_fib_set_fwd_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81948520)
Location: net/core/filter.c:4599
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81948520-ffffffff8194855d: bpf_fib_set_fwd_params.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81969e30)
Location: net/core/filter.c:4599
Inline: True
Direct callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
```
**Symbols:**

```
ffffffff81969e30-ffffffff81969e6d: bpf_fib_set_fwd_params.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 mtu</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
