# Function: <code>bpf_skb_get_tunnel_opt</code>

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
u64 bpf_skb_get_tunnel_opt(u64 r1, u64 r2, u64 size, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179b970)
Location: net/core/filter.c:2127
Inline: False
```
**Symbols:**

```
ffffffff8179b970-ffffffff8179ba9a: bpf_skb_get_tunnel_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cbfb0)
Location: net/core/filter.c:2385
Inline: False
```
**Symbols:**

```
ffffffff817cbfb0-ffffffff817cc0c4: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ebae0)
Location: net/core/filter.c:2544
Inline: False
```
**Symbols:**

```
ffffffff817ebae0-ffffffff817ebc03: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81866a40)
Location: net/core/filter.c:2942
Inline: False
```
**Symbols:**

```
ffffffff81866a40-ffffffff81866b63: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5530)
Location: net/core/filter.c:3564
Inline: False
```
**Symbols:**

```
ffffffff818b5530-ffffffff818b564b: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dac70)
Location: net/core/filter.c:3752
Inline: False
```
**Symbols:**

```
ffffffff818dac70-ffffffff818dad8b: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81927750)
Location: net/core/filter.c:3889
Inline: False
```
**Symbols:**

```
ffffffff81927750-ffffffff81927871: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959e10)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
ffffffff81959e10-ffffffff81959f31: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d6a0)
Location: net/core/filter.c:3868
Inline: False
```
**Symbols:**

```
ffffffff81a2d6a0-ffffffff81a2d7c1: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2f160)
Location: net/core/filter.c:4276
Inline: False
```
**Symbols:**

```
ffffffff81a2f160-ffffffff81a2f281: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a17510)
Location: net/core/filter.c:4215
Inline: False
```
**Symbols:**

```
ffffffff81a17510-ffffffff81a17641: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac8a60)
Location: net/core/filter.c:4273
Inline: False
```
**Symbols:**

```
ffffffff81ac8a60-ffffffff81ac8b91: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c45e40)
Location: net/core/filter.c:4559
Inline: False
```
**Symbols:**

```
ffffffff81c45e40-ffffffff81c45f9f: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df9e30)
Location: net/core/filter.c:4577
Inline: False
```
**Symbols:**

```
ffffffff81df9e30-ffffffff81df9f13: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6b610)
Location: net/core/filter.c:4628
Inline: False
```
**Symbols:**

```
ffffffff81e6b610-ffffffff81e6b6fc: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2a6f0)
Location: net/core/filter.c:4702
Inline: False
```
**Symbols:**

```
ffffffff81f2a6f0-ffffffff81f2a7dc: bpf_skb_get_tunnel_opt (STB_GLOBAL)
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfba20)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
ffff800010bfba20-ffff800010bfbb0c: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d164ec)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
c0d164ec-c0d165cc: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce4030)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
c000000000ce4030-c000000000ce418c: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077e036)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
ffffffe00077e036-ffffffe00077e0f4: bpf_skb_get_tunnel_opt (STB_GLOBAL)
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
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9de0)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
ffffffff818f9de0-ffffffff818f9f01: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3c10)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
ffffffff818b3c10-ffffffff818b3d31: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194ae10)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
ffffffff8194ae10-ffffffff8194af31: bpf_skb_get_tunnel_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_opt(u64 skb, u64 to, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196c720)
Location: net/core/filter.c:3896
Inline: False
```
**Symbols:**

```
ffffffff8196c720-ffffffff8196c841: bpf_skb_get_tunnel_opt (STB_GLOBAL)
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
<code>u64 to</code>
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
