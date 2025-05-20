# Function: <code>sk_select_reuseport</code>

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
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d5660)
Location: net/core/filter.c:7806
Inline: False
```
**Symbols:**

```
ffffffff818d5660-ffffffff818d56e5: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81923040)
Location: net/core/filter.c:8628
Inline: False
```
**Symbols:**

```
ffffffff81923040-ffffffff819230cc: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81955270)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
ffffffff81955270-ffffffff819552fc: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2b9c0)
Location: net/core/filter.c:9025
Inline: False
```
**Symbols:**

```
ffffffff81a2b9c0-ffffffff81a2babb: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2cf50)
Location: net/core/filter.c:9893
Inline: False
```
**Symbols:**

```
ffffffff81a2cf50-ffffffff81a2d04b: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a13fa0)
Location: net/core/filter.c:10034
Inline: False
```
**Symbols:**

```
ffffffff81a13fa0-ffffffff81a1409b: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:10213
Inline: False
```
**Symbols:**

```
ffffffff81d37783-ffffffff81d377a3: sk_select_reuseport.cold (STB_LOCAL)
ffffffff81acdf50-ffffffff81ace074: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:10719
Inline: False
```
**Symbols:**

```
ffffffff81f040cf-ffffffff81f040ef: sk_select_reuseport.cold (STB_LOCAL)
ffffffff81c4bd10-ffffffff81c4be3e: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:10925
Inline: False
```
**Symbols:**

```
ffffffff820ac5aa-ffffffff820ac5ca: sk_select_reuseport.cold (STB_LOCAL)
ffffffff81dfd050-ffffffff81dfd18f: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:11074
Inline: False
```
**Symbols:**

```
ffffffff8212db6a-ffffffff8212db83: sk_select_reuseport.cold (STB_LOCAL)
ffffffff81e6d750-ffffffff81e6d877: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:11165
Inline: False
```
**Symbols:**

```
ffffffff8220f8f0-ffffffff8220f909: sk_select_reuseport.cold (STB_LOCAL)
ffffffff81f2cf90-ffffffff81f2d0b7: sk_select_reuseport (STB_GLOBAL)
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
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf6db0)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
ffff800010bf6db0-ffff800010bf6e6c: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d10048)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
c0d10048-c0d10104: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdc8f0)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
c000000000cdc8f0-c000000000cdc9dc: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007784a6)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
ffffffe0007784a6-ffffffe000778532: sk_select_reuseport (STB_GLOBAL)
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
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5240)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
ffffffff818f5240-ffffffff818f52cc: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818af070)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
ffffffff818af070-ffffffff818af0fc: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81946270)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
ffffffff81946270-ffffffff819462fc: sk_select_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 sk_select_reuseport(u64 reuse_kern, u64 map, u64 key, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81967b60)
Location: net/core/filter.c:8715
Inline: False
```
**Symbols:**

```
ffffffff81967b60-ffffffff81967bec: sk_select_reuseport (STB_GLOBAL)
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
