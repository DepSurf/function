# Function: <code>ip6_sk_dst_store_flow</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819777f0)
Location: net/ipv6/route.c:2405
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff819777f0-ffffffff819778c5: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad3f0)
Location: net/ipv6/route.c:2398
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff819ad3f0-ffffffff819ad4c9: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1a570)
Location: net/ipv6/route.c:2816
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a1a570-ffffffff81a1a625: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a511e0)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a511e0-ffffffff81a51295: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b48900)
Location: net/ipv6/route.c:2850
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b48900-ffffffff81b489ba: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b574e0)
Location: net/ipv6/route.c:2834
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b574e0-ffffffff81b575c7: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b450d0)
Location: net/ipv6/route.c:2843
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81b450d0-ffffffff81b451b7: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2973
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81d400ab-ffffffff81d400eb: ip6_sk_dst_store_flow.cold (STB_LOCAL)
ffffffff81c0c210-ffffffff81c0c300: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2969
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81f0ca24-ffffffff81f0ca64: ip6_sk_dst_store_flow.cold (STB_LOCAL)
ffffffff81da70b0-ffffffff81da71c0: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2969
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff820b4075-ffffffff820b40b5: ip6_sk_dst_store_flow.cold (STB_LOCAL)
ffffffff81f766b0-ffffffff81f767c0: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2969
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff8213513d-ffffffff8213516f: ip6_sk_dst_store_flow.cold (STB_LOCAL)
ffffffff81fd66c0-ffffffff81fd67e1: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2971
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff82216c0e-ffffffff82216c40: ip6_sk_dst_store_flow.cold (STB_LOCAL)
ffffffff820a4040-ffffffff820a4161: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d15108)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffff800010d15108-ffff800010d151f4: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1ad90)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
c0e1ad90-c0e1ae88: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e42040)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
c000000000e42040-c000000000e42154: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085a7da)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffe00085a7da-ffffffe00085a8e8: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f0870)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff819f0870-ffffffff819f0925: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ad630)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff819ad630-ffffffff819ad6e5: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5b2f0)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a5b2f0-ffffffff81a5b3a5: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_sk_dst_store_flow(struct sock *sk, struct dst_entry *dst, const struct flowi6 *fl6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a675d0)
Location: net/ipv6/route.c:2826
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_dst_update
```
**Symbols:**

```
ffffffff81a675d0-ffffffff81a676b6: ip6_sk_dst_store_flow (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
