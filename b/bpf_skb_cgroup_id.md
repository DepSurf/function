# Function: <code>bpf_skb_cgroup_id</code>

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
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818aea30)
Location: net/core/filter.c:3753
Inline: False
```
**Symbols:**

```
ffffffff818aea30-ffffffff818aea98: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d2cc0)
Location: net/core/filter.c:3941
Inline: False
```
**Symbols:**

```
ffffffff818d2cc0-ffffffff818d2d28: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8191fdb0)
Location: net/core/filter.c:4078
Inline: False
```
**Symbols:**

```
ffffffff8191fdb0-ffffffff8191fe1e: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81951ff0)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
ffffffff81951ff0-ffffffff8195205e: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a231f0)
Location: net/core/filter.c:4065
Inline: False
```
**Symbols:**

```
ffffffff81a231f0-ffffffff81a2325e: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a235b0)
Location: net/core/filter.c:4477
Inline: False
```
**Symbols:**

```
ffffffff81a235b0-ffffffff81a23619: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0a900)
Location: net/core/filter.c:4416
Inline: False
```
**Symbols:**

```
ffffffff81a0a900-ffffffff81a0a974: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4474
Inline: False
```
**Symbols:**

```
ffffffff81d373f2-ffffffff81d37412: bpf_skb_cgroup_id.cold (STB_LOCAL)
ffffffff81acb000-ffffffff81acb063: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4765
Inline: False
```
**Symbols:**

```
ffffffff81f03e2a-ffffffff81f03e4a: bpf_skb_cgroup_id.cold (STB_LOCAL)
ffffffff81c48560-ffffffff81c485db: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4783
Inline: False
```
**Symbols:**

```
ffffffff820ac4c7-ffffffff820ac4e7: bpf_skb_cgroup_id.cold (STB_LOCAL)
ffffffff81dfc9c0-ffffffff81dfca3b: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4837
Inline: False
```
**Symbols:**

```
ffffffff8212da9b-ffffffff8212dab6: bpf_skb_cgroup_id.cold (STB_LOCAL)
ffffffff81e6d2f0-ffffffff81e6d35e: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4911
Inline: False
```
**Symbols:**

```
ffffffff8220f7f9-ffffffff8220f814: bpf_skb_cgroup_id.cold (STB_LOCAL)
ffffffff81f2caa0-ffffffff81f2cb0e: bpf_skb_cgroup_id (STB_GLOBAL)
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
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf4170)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
ffff800010bf4170-ffff800010bf4218: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0c964)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
c0d0c964-c0d0c9fc: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cd92d0)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
c000000000cd92d0-c000000000cd9374: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077565a)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
ffffffe00077565a-ffffffe0007756da: bpf_skb_cgroup_id (STB_GLOBAL)
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
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f1fc0)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
ffffffff818f1fc0-ffffffff818f202e: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818abdf0)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
ffffffff818abdf0-ffffffff818abe5e: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81942ff0)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
ffffffff81942ff0-ffffffff8194305e: bpf_skb_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_cgroup_id(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819648e0)
Location: net/core/filter.c:4085
Inline: False
```
**Symbols:**

```
ffffffff819648e0-ffffffff8196494e: bpf_skb_cgroup_id (STB_GLOBAL)
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
