# Function: <code>ip6_datagram_dst_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81863440)
Location: net/ipv6/datagram.c:67
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81863440-ffffffff8186373d: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81895a50)
Location: net/ipv6/datagram.c:68
Inline: False
Direct callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81895a50-ffffffff81895d57: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff818bbfc0)
Location: net/ipv6/datagram.c:68
Inline: False
Direct callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff818bbfc0-ffffffff818bc2e9: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff8193f090)
Location: net/ipv6/datagram.c:68
Inline: False
Direct callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff8193f090-ffffffff8193f3c2: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81997f80)
Location: net/ipv6/datagram.c:68
Inline: False
Direct callers:
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81997f80-ffffffff819981df: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff819ce910)
Location: net/ipv6/datagram.c:68
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff819ce910-ffffffff819ceb6f: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a3d5c0)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a3d5c0-ffffffff81a3d840: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a74220)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a74220-ffffffff81a744a9: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b6e520)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81b6e520-ffffffff81b6e6b4: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b7cfd0)
Location: net/ipv6/datagram.c:66
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81b7cfd0-ffffffff81b7d16e: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b6bab0)
Location: net/ipv6/datagram.c:66
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81b6bab0-ffffffff81b6bd44: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:66
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81d40f1e-ffffffff81d40f62: ip6_datagram_dst_update.cold (STB_LOCAL)
ffffffff81c33910-ffffffff81c33bc9: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:66
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81f0d862-ffffffff81f0d8a6: ip6_datagram_dst_update.cold (STB_LOCAL)
ffffffff81dd1170-ffffffff81dd143c: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:71
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff820b4ce1-ffffffff820b4d25: ip6_datagram_dst_update.cold (STB_LOCAL)
ffffffff81fa2760-ffffffff81fa2a3a: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:71
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff82135c78-ffffffff82135caa: ip6_datagram_dst_update.cold (STB_LOCAL)
ffffffff82003000-ffffffff820032ec: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:72
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff822178c6-ffffffff822178f8: ip6_datagram_dst_update.cold (STB_LOCAL)
ffffffff820d1dd0-ffffffff820d20ba: ip6_datagram_dst_update (STB_GLOBAL)
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
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffff800010d3cc60)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffff800010d3cc60-ffff800010d3cebc: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (c0e3fec0)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
c0e3fec0-c0e40120: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (c000000000e70bf0)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
c000000000e70bf0-c000000000e70f38: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffe0008794f6)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffe0008794f6-ffffffe00087970a: ip6_datagram_dst_update (STB_GLOBAL)
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
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a138b0)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a138b0-ffffffff81a13b39: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff819d0670)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff819d0670-ffffffff819d08f9: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a7e330)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a7e330-ffffffff81a7e5b9: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_datagram_dst_update(struct sock *sk, bool fix_sk_saddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a8abc0)
Location: net/ipv6/datagram.c:65
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/datagram.c:__ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a8abc0-ffffffff81a8ae4b: ip6_datagram_dst_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
