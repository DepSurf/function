# Function: <code>bpf_skb_under_cgroup</code>

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
u64 bpf_skb_under_cgroup(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179b600)
Location: net/core/filter.c:2286
Inline: False
```
**Symbols:**

```
ffffffff8179b600-ffffffff8179b6a0: bpf_skb_under_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817c95f0)
Location: net/core/filter.c:2539
Inline: False
```
**Symbols:**

```
ffffffff817c95f0-ffffffff817c96b4: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e8530)
Location: net/core/filter.c:2699
Inline: False
```
**Symbols:**

```
ffffffff817e8530-ffffffff817e85ec: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81863890)
Location: net/core/filter.c:3098
Inline: False
```
**Symbols:**

```
ffffffff81863890-ffffffff8186394f: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ae970)
Location: net/core/filter.c:3723
Inline: False
```
**Symbols:**

```
ffffffff818ae970-ffffffff818aea2f: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d2c00)
Location: net/core/filter.c:3911
Inline: False
```
**Symbols:**

```
ffffffff818d2c00-ffffffff818d2cbf: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81922f70)
Location: net/core/filter.c:4048
Inline: False
```
**Symbols:**

```
ffffffff81922f70-ffffffff8192303a: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819551a0)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
ffffffff819551a0-ffffffff8195526a: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a27730)
Location: net/core/filter.c:4027
Inline: False
```
**Symbols:**

```
ffffffff81a27730-ffffffff81a277fd: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a27f40)
Location: net/core/filter.c:4435
Inline: False
```
**Symbols:**

```
ffffffff81a27f40-ffffffff81a2800d: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0f2b0)
Location: net/core/filter.c:4374
Inline: False
```
**Symbols:**

```
ffffffff81a0f2b0-ffffffff81a0f398: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4432
Inline: False
```
**Symbols:**

```
ffffffff81d375b5-ffffffff81d375d5: bpf_skb_under_cgroup.cold (STB_LOCAL)
ffffffff81acbf10-ffffffff81acbff4: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4723
Inline: False
```
**Symbols:**

```
ffffffff81f03eb2-ffffffff81f03ed2: bpf_skb_under_cgroup.cold (STB_LOCAL)
ffffffff81c48930-ffffffff81c48a43: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4741
Inline: False
```
**Symbols:**

```
ffffffff820ac60a-ffffffff820ac62a: bpf_skb_under_cgroup.cold (STB_LOCAL)
ffffffff81dfd6b0-ffffffff81dfd7b7: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4795
Inline: False
```
**Symbols:**

```
ffffffff8212dbd3-ffffffff8212dbf3: bpf_skb_under_cgroup.cold (STB_LOCAL)
ffffffff81e6dfa0-ffffffff81e6e07c: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4869
Inline: False
```
**Symbols:**

```
ffffffff8220f931-ffffffff8220f951: bpf_skb_under_cgroup.cold (STB_LOCAL)
ffffffff81f2d490-ffffffff81f2d56c: bpf_skb_under_cgroup (STB_GLOBAL)
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf6ca0)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
ffff800010bf6ca0-ffff800010bf6dac: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0ff3c)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
c0d0ff3c-c0d10048: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdc7e0)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
c000000000cdc7e0-c000000000cdc8e8: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007783c6)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
ffffffe0007783c6-ffffffe0007784a6: bpf_skb_under_cgroup (STB_GLOBAL)
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
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5170)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
ffffffff818f5170-ffffffff818f523a: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818aefa0)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
ffffffff818aefa0-ffffffff818af06a: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819461a0)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
ffffffff819461a0-ffffffff8194626a: bpf_skb_under_cgroup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_under_cgroup(u64 skb, u64 map, u64 idx, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81967a90)
Location: net/core/filter.c:4055
Inline: False
```
**Symbols:**

```
ffffffff81967a90-ffffffff81967b5a: bpf_skb_under_cgroup (STB_GLOBAL)
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
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 idx</code>
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
<code>u64 r3</code>
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
