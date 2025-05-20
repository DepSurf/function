# Function: <code>bpf_skb_change_proto</code>

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
u64 bpf_skb_change_proto(u64 r1, u64 r2, u64 flags, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d670)
Location: net/core/filter.c:1933
Inline: False
```
**Symbols:**

```
ffffffff8179d670-ffffffff8179db2d: bpf_skb_change_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cc0d0)
Location: net/core/filter.c:2055
Inline: False
```
**Symbols:**

```
ffffffff817cc0d0-ffffffff817cc58d: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eb140)
Location: net/core/filter.c:2099
Inline: False
```
**Symbols:**

```
ffffffff817eb140-ffffffff817eb47a: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81866f90)
Location: net/core/filter.c:2164
Inline: False
```
**Symbols:**

```
ffffffff81866f90-ffffffff81867348: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b6080)
Location: net/core/filter.c:2693
Inline: False
```
**Symbols:**

```
ffffffff818b6080-ffffffff818b6333: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818db130)
Location: net/core/filter.c:2883
Inline: False
```
**Symbols:**

```
ffffffff818db130-ffffffff818db3d4: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819284f0)
Location: net/core/filter.c:2929
Inline: False
```
**Symbols:**

```
ffffffff819284f0-ffffffff81928778: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195a280)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
ffffffff8195a280-ffffffff8195a508: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2dd30)
Location: net/core/filter.c:2969
Inline: False
```
**Symbols:**

```
ffffffff81a2dd30-ffffffff81a2ddc4: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30300)
Location: net/core/filter.c:3338
Inline: False
```
**Symbols:**

```
ffffffff81a30300-ffffffff81a30394: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19b20)
Location: net/core/filter.c:3331
Inline: False
```
**Symbols:**

```
ffffffff81a19b20-ffffffff81a19d71: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acad80)
Location: net/core/filter.c:3300
Inline: False
```
**Symbols:**

```
ffffffff81acad80-ffffffff81acafb1: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c47dd0)
Location: net/core/filter.c:3301
Inline: False
```
**Symbols:**

```
ffffffff81c47dd0-ffffffff81c48003: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfc6a0)
Location: net/core/filter.c:3311
Inline: False
```
**Symbols:**

```
ffffffff81dfc6a0-ffffffff81dfc9a4: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6d890)
Location: net/core/filter.c:3327
Inline: False
```
**Symbols:**

```
ffffffff81e6d890-ffffffff81e6db94: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2d0d0)
Location: net/core/filter.c:3361
Inline: False
```
**Symbols:**

```
ffffffff81f2d0d0-ffffffff81f2d3d4: bpf_skb_change_proto (STB_GLOBAL)
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfc1a8)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
ffff800010bfc1a8-ffff800010bfc448: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d16904)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
c0d16904-c0d16c00: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce6d70)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
c000000000ce6d70-c000000000ce7110: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077e41a)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
ffffffe00077e41a-ffffffe00077e634: bpf_skb_change_proto (STB_GLOBAL)
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
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fa250)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
ffffffff818fa250-ffffffff818fa4d8: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b4080)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
ffffffff818b4080-ffffffff818b4308: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194b280)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
ffffffff8194b280-ffffffff8194b508: bpf_skb_change_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_change_proto(u64 skb, u64 proto, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196cb90)
Location: net/core/filter.c:2931
Inline: False
```
**Symbols:**

```
ffffffff8196cb90-ffffffff8196ce18: bpf_skb_change_proto (STB_GLOBAL)
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
<code>u64 proto</code>
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
