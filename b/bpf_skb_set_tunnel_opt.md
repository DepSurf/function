# Function: <code>bpf_skb_set_tunnel_opt</code>

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
u64 bpf_skb_set_tunnel_opt(u64 r1, u64 r2, u64 size, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179baa0)
Location: net/core/filter.c:2236
Inline: False
```
**Symbols:**

```
ffffffff8179baa0-ffffffff8179bb37: bpf_skb_set_tunnel_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cbf10)
Location: net/core/filter.c:2491
Inline: False
```
**Symbols:**

```
ffffffff817cbf10-ffffffff817cbfa2: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eb810)
Location: net/core/filter.c:2650
Inline: False
```
**Symbols:**

```
ffffffff817eb810-ffffffff817eb8ae: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818664d0)
Location: net/core/filter.c:3048
Inline: False
```
**Symbols:**

```
ffffffff818664d0-ffffffff8186656e: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5000)
Location: net/core/filter.c:3673
Inline: False
```
**Symbols:**

```
ffffffff818b5000-ffffffff818b508c: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dabe0)
Location: net/core/filter.c:3861
Inline: False
```
**Symbols:**

```
ffffffff818dabe0-ffffffff818dac6a: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81927650)
Location: net/core/filter.c:3998
Inline: False
```
**Symbols:**

```
ffffffff81927650-ffffffff819276e6: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959d10)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
ffffffff81959d10-ffffffff81959da6: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d4e0)
Location: net/core/filter.c:3977
Inline: False
```
**Symbols:**

```
ffffffff81a2d4e0-ffffffff81a2d576: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ed80)
Location: net/core/filter.c:4385
Inline: False
```
**Symbols:**

```
ffffffff81a2ed80-ffffffff81a2ee1b: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a16db0)
Location: net/core/filter.c:4324
Inline: False
```
**Symbols:**

```
ffffffff81a16db0-ffffffff81a16e5c: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac8240)
Location: net/core/filter.c:4382
Inline: False
```
**Symbols:**

```
ffffffff81ac8240-ffffffff81ac82ec: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c45860)
Location: net/core/filter.c:4673
Inline: False
```
**Symbols:**

```
ffffffff81c45860-ffffffff81c45925: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df9a10)
Location: net/core/filter.c:4691
Inline: False
```
**Symbols:**

```
ffffffff81df9a10-ffffffff81df9ad5: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6b8f0)
Location: net/core/filter.c:4745
Inline: False
```
**Symbols:**

```
ffffffff81e6b8f0-ffffffff81e6ba58: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2aa40)
Location: net/core/filter.c:4819
Inline: False
```
**Symbols:**

```
ffffffff81f2aa40-ffffffff81f2aba8: bpf_skb_set_tunnel_opt (STB_GLOBAL)
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
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bff9d0)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
ffff800010bff9d0-ffff800010bffaa8: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d15c1c)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
c0d15c1c-c0d15cdc: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce3e80)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
c000000000ce3e80-c000000000ce3f78: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077df7c)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
ffffffe00077df7c-ffffffe00077e036: bpf_skb_set_tunnel_opt (STB_GLOBAL)
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
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9ce0)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
ffffffff818f9ce0-ffffffff818f9d76: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3b10)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
ffffffff818b3b10-ffffffff818b3ba6: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194ad10)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
ffffffff8194ad10-ffffffff8194ada6: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_set_tunnel_opt(u64 skb, u64 from, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196c620)
Location: net/core/filter.c:4005
Inline: False
```
**Symbols:**

```
ffffffff8196c620-ffffffff8196c6b6: bpf_skb_set_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 from</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
