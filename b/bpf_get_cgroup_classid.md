# Function: <code>bpf_get_cgroup_classid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817324d0)
Location: net/core/filter.c:1478
Inline: False
```
**Symbols:**

```
ffffffff817324d0-ffffffff81732513: bpf_get_cgroup_classid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179ccb0)
Location: net/core/filter.c:1687
Inline: False
```
**Symbols:**

```
ffffffff8179ccb0-ffffffff8179cd24: bpf_get_cgroup_classid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca340)
Location: net/core/filter.c:1795
Inline: False
```
**Symbols:**

```
ffffffff817ca340-ffffffff817ca3b4: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e92e0)
Location: net/core/filter.c:1821
Inline: False
```
**Symbols:**

```
ffffffff817e92e0-ffffffff817e9355: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818646e0)
Location: net/core/filter.c:1886
Inline: False
```
**Symbols:**

```
ffffffff818646e0-ffffffff81864755: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1830)
Location: net/core/filter.c:2405
Inline: False
```
**Symbols:**

```
ffffffff818b1830-ffffffff818b18a5: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d6260)
Location: net/core/filter.c:2597
Inline: False
```
**Symbols:**

```
ffffffff818d6260-ffffffff818d62d5: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81923a30)
Location: net/core/filter.c:2643
Inline: False
```
**Symbols:**

```
ffffffff81923a30-ffffffff81923aa5: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81955c60)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
ffffffff81955c60-ffffffff81955cd5: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29790)
Location: net/core/filter.c:2683
Inline: False
```
**Symbols:**

```
ffffffff81a29790-ffffffff81a29808: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a0f0)
Location: net/core/filter.c:3052
Inline: False
```
**Symbols:**

```
ffffffff81a2a0f0-ffffffff81a2a168: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a11340)
Location: net/core/filter.c:3049
Inline: False
```
**Symbols:**

```
ffffffff81a11340-ffffffff81a113cb: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3036
Inline: False
```
**Symbols:**

```
ffffffff81d37657-ffffffff81d37677: bpf_get_cgroup_classid.cold (STB_LOCAL)
ffffffff81acc750-ffffffff81acc7ca: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3037
Inline: False
```
**Symbols:**

```
ffffffff81f03fab-ffffffff81f03fcb: bpf_get_cgroup_classid.cold (STB_LOCAL)
ffffffff81c495e0-ffffffff81c49672: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3044
Inline: False
```
**Symbols:**

```
ffffffff820ac77c-ffffffff820ac79c: bpf_get_cgroup_classid.cold (STB_LOCAL)
ffffffff81dfe5e0-ffffffff81dfe672: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3060
Inline: False
```
**Symbols:**

```
ffffffff8212ddb3-ffffffff8212ddce: bpf_get_cgroup_classid.cold (STB_LOCAL)
ffffffff81e6f7a0-ffffffff81e6f82a: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3094
Inline: False
```
**Symbols:**

```
ffffffff8220fb19-ffffffff8220fb34: bpf_get_cgroup_classid.cold (STB_LOCAL)
ffffffff81f2ef70-ffffffff81f2effa: bpf_get_cgroup_classid (STB_GLOBAL)
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
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf7a20)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
ffff800010bf7a20-ffff800010bf7ab0: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d11238)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
c0d11238-c0d112d8: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdd970)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
c000000000cdd970-c000000000cdda60: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077942a)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
ffffffe00077942a-ffffffe0007794b0: bpf_get_cgroup_classid (STB_GLOBAL)
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
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5c30)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
ffffffff818f5c30-ffffffff818f5ca5: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818afa60)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
ffffffff818afa60-ffffffff818afad5: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81946c60)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
ffffffff81946c60-ffffffff81946cd5: bpf_get_cgroup_classid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_get_cgroup_classid(u64 skb, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81968570)
Location: net/core/filter.c:2645
Inline: False
```
**Symbols:**

```
ffffffff81968570-ffffffff819685e5: bpf_get_cgroup_classid (STB_GLOBAL)
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
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_4</code>
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
