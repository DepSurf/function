# Function: <code>bpf_skb_vlan_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 r1, u64 r2, u64 vlan_tci, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731aa0)
Location: net/core/filter.c:1509
Inline: False
```
**Symbols:**

```
ffffffff81731aa0-ffffffff81731ad7: bpf_skb_vlan_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 r1, u64 r2, u64 vlan_tci, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179dc30)
Location: net/core/filter.c:1728
Inline: False
```
**Symbols:**

```
ffffffff8179dc30-ffffffff8179dd58: bpf_skb_vlan_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cc690)
Location: net/core/filter.c:1852
Inline: False
```
**Symbols:**

```
ffffffff817cc690-ffffffff817cc7b8: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eb9b0)
Location: net/core/filter.c:1896
Inline: False
```
**Symbols:**

```
ffffffff817eb9b0-ffffffff817ebad8: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81866800)
Location: net/core/filter.c:1961
Inline: False
```
**Symbols:**

```
ffffffff81866800-ffffffff81866948: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5970)
Location: net/core/filter.c:2480
Inline: False
```
**Symbols:**

```
ffffffff818b5970-ffffffff818b5abf: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dbb80)
Location: net/core/filter.c:2672
Inline: False
```
**Symbols:**

```
ffffffff818dbb80-ffffffff818dbcbf: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81929340)
Location: net/core/filter.c:2718
Inline: False
```
**Symbols:**

```
ffffffff81929340-ffffffff81929485: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195ba20)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
ffffffff8195ba20-ffffffff8195bb65: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ead0)
Location: net/core/filter.c:2758
Inline: False
```
**Symbols:**

```
ffffffff81a2ead0-ffffffff81a2ec17: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30740)
Location: net/core/filter.c:3127
Inline: False
```
**Symbols:**

```
ffffffff81a30740-ffffffff81a30887: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a177e0)
Location: net/core/filter.c:3124
Inline: False
```
**Symbols:**

```
ffffffff81a177e0-ffffffff81a17925: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac8e20)
Location: net/core/filter.c:3111
Inline: False
```
**Symbols:**

```
ffffffff81ac8e20-ffffffff81ac8f65: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c45c90)
Location: net/core/filter.c:3112
Inline: False
```
**Symbols:**

```
ffffffff81c45c90-ffffffff81c45de5: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfa120)
Location: net/core/filter.c:3119
Inline: False
```
**Symbols:**

```
ffffffff81dfa120-ffffffff81dfa275: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6bc20)
Location: net/core/filter.c:3135
Inline: False
```
**Symbols:**

```
ffffffff81e6bc20-ffffffff81e6bd75: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2ad00)
Location: net/core/filter.c:3169
Inline: False
```
**Symbols:**

```
ffffffff81f2ad00-ffffffff81f2ae55: bpf_skb_vlan_push (STB_GLOBAL)
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfcab8)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
ffff800010bfcab8-ffff800010bfcbfc: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d182a4)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
c0d182a4-c0d183e4: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce8040)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
c000000000ce8040-c000000000ce81e4: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f8bc)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
ffffffe00077f8bc-ffffffe00077f9f0: bpf_skb_vlan_push (STB_GLOBAL)
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fb9f0)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
ffffffff818fb9f0-ffffffff818fbb35: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5820)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
ffffffff818b5820-ffffffff818b5965: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194ca20)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
ffffffff8194ca20-ffffffff8194cb65: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196e3e0)
Location: net/core/filter.c:2720
Inline: False
```
**Symbols:**

```
ffffffff8196e3e0-ffffffff8196e525: bpf_skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<code>u64 vlan_proto</code>
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
