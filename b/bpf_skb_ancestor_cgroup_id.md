# Function: <code>bpf_skb_ancestor_cgroup_id</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d2d30)
Location: net/core/filter.c:3960
Inline: False
```
**Symbols:**

```
ffffffff818d2d30-ffffffff818d2dd2: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8191fe20)
Location: net/core/filter.c:4097
Inline: False
```
**Symbols:**

```
ffffffff8191fe20-ffffffff8191fed0: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81952060)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
ffffffff81952060-ffffffff819520f9: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a23260)
Location: net/core/filter.c:4096
Inline: False
```
**Symbols:**

```
ffffffff81a23260-ffffffff81a232f9: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a23620)
Location: net/core/filter.c:4507
Inline: False
```
**Symbols:**

```
ffffffff81a23620-ffffffff81a236b4: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0a980)
Location: net/core/filter.c:4446
Inline: False
```
**Symbols:**

```
ffffffff81a0a980-ffffffff81a0aa17: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4504
Inline: False
```
**Symbols:**

```
ffffffff81d375f5-ffffffff81d37615: bpf_skb_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81acc0a0-ffffffff81acc137: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
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
ffffffff81f03ed2-ffffffff81f03ef2: bpf_skb_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81c48a50-ffffffff81c48b05: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4813
Inline: False
```
**Symbols:**

```
ffffffff820ac5ea-ffffffff820ac60a: bpf_skb_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81dfd460-ffffffff81dfd504: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4867
Inline: False
```
**Symbols:**

```
ffffffff8212dbab-ffffffff8212dbd3: bpf_skb_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81e6df00-ffffffff81e6df86: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4941
Inline: False
```
**Symbols:**

```
ffffffff8220f909-ffffffff8220f931: bpf_skb_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81f2d3f0-ffffffff81f2d476: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
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
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf4218)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
ffff800010bf4218-ffff800010bf430c: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0c9fc)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
c0d0c9fc-c0d0cac0: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cd9380)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
c000000000cd9380-c000000000cd946c: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007756da)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
ffffffe0007756da-ffffffe000775780: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
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
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f2030)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
ffffffff818f2030-ffffffff818f20c9: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818abe60)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
ffffffff818abe60-ffffffff818abef9: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81943060)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
ffffffff81943060-ffffffff819430f9: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_ancestor_cgroup_id(u64 skb, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81964950)
Location: net/core/filter.c:4104
Inline: False
```
**Symbols:**

```
ffffffff81964950-ffffffff819649e9: bpf_skb_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
