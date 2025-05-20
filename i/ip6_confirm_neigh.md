# Function: <code>ip6_confirm_neigh</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818999f0)
Location: net/ipv6/route.c:225
Inline: False
```
**Symbols:**

```
ffffffff818999f0-ffffffff81899aff: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191ad90)
Location: net/ipv6/route.c:231
Inline: False
```
**Symbols:**

```
ffffffff8191ad90-ffffffff8191ae9f: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81972d20)
Location: net/ipv6/route.c:225
Inline: False
```
**Symbols:**

```
ffffffff81972d20-ffffffff81972e2e: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8800)
Location: net/ipv6/route.c:227
Inline: False
```
**Symbols:**

```
ffffffff819a8800-ffffffff819a890e: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a156d0)
Location: net/ipv6/route.c:225
Inline: False
```
**Symbols:**

```
ffffffff81a156d0-ffffffff81a157de: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4c2a0)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffffffff81a4c2a0-ffffffff81a4c3e8: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b42b10)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffffffff81b42b10-ffffffff81b42c58: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b51240)
Location: net/ipv6/route.c:227
Inline: False
```
**Symbols:**

```
ffffffff81b51240-ffffffff81b51388: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3f160)
Location: net/ipv6/route.c:230
Inline: False
```
**Symbols:**

```
ffffffff81b3f160-ffffffff81b3f2a5: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:230
Inline: False
```
**Symbols:**

```
ffffffff81c06c30-ffffffff81c06d8b: ip6_confirm_neigh (STB_LOCAL)
ffffffff81d3fcd4-ffffffff81d3fcf3: ip6_confirm_neigh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:235
Inline: False
```
**Symbols:**

```
ffffffff81da1490-ffffffff81da15fc: ip6_confirm_neigh (STB_LOCAL)
ffffffff81f0c652-ffffffff81f0c671: ip6_confirm_neigh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:235
Inline: False
```
**Symbols:**

```
ffffffff81f707d0-ffffffff81f7093c: ip6_confirm_neigh (STB_LOCAL)
ffffffff820b3ca3-ffffffff820b3cc2: ip6_confirm_neigh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:235
Inline: False
```
**Symbols:**

```
ffffffff81fd0440-ffffffff81fd05a0: ip6_confirm_neigh (STB_LOCAL)
ffffffff82134d90-ffffffff82134daf: ip6_confirm_neigh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:235
Inline: False
```
**Symbols:**

```
ffffffff8209dcd0-ffffffff8209de30: ip6_confirm_neigh (STB_LOCAL)
ffffffff82216854-ffffffff82216873: ip6_confirm_neigh.cold (STB_LOCAL)
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
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0ec18)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffff800010d0ec18-ffff800010d0ed78: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e167ac)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
c0e167ac-c0e1690c: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3bc60)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
c000000000e3bc60-c000000000e3be1c: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000856e3e)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffffffe000856e3e-ffffffe000856f86: ip6_confirm_neigh (STB_LOCAL)
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
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eb930)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffffffff819eb930-ffffffff819eba78: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a86f0)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffffffff819a86f0-ffffffff819a8838: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a563b0)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffffffff81a563b0-ffffffff81a564f8: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_confirm_neigh(const struct dst_entry *dst, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a62400)
Location: net/ipv6/route.c:226
Inline: False
```
**Symbols:**

```
ffffffff81a62400-ffffffff81a62548: ip6_confirm_neigh (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
