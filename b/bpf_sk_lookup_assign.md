# Function: <code>bpf_sk_lookup_assign</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sk_lookup_assign(u64 ctx, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30480)
Location: net/core/filter.c:10112
Inline: False
```
**Symbols:**

```
ffffffff81a30480-ffffffff81a30530: bpf_sk_lookup_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_lookup_assign(u64 ctx, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a173e0)
Location: net/core/filter.c:10253
Inline: False
```
**Symbols:**

```
ffffffff81a173e0-ffffffff81a17499: bpf_sk_lookup_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_lookup_assign(u64 ctx, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:10452
Inline: False
```
**Symbols:**

```
ffffffff81d3775b-ffffffff81d37783: bpf_sk_lookup_assign.cold (STB_LOCAL)
ffffffff81acde60-ffffffff81acdf4c: bpf_sk_lookup_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_lookup_assign(u64 ctx, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:10958
Inline: False
```
**Symbols:**

```
ffffffff81f040af-ffffffff81f040cf: bpf_sk_lookup_assign.cold (STB_LOCAL)
ffffffff81c4bbc0-ffffffff81c4bd01: bpf_sk_lookup_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_lookup_assign(u64 ctx, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:11164
Inline: False
```
**Symbols:**

```
ffffffff820ac33e-ffffffff820ac35e: bpf_sk_lookup_assign.cold (STB_LOCAL)
ffffffff81dfbbf0-ffffffff81dfbd31: bpf_sk_lookup_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_lookup_assign(u64 ctx, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:11313
Inline: False
```
**Symbols:**

```
ffffffff8212d9f4-ffffffff8212da14: bpf_sk_lookup_assign.cold (STB_LOCAL)
ffffffff81e6caf0-ffffffff81e6cc0d: bpf_sk_lookup_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_lookup_assign(u64 ctx, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:11404
Inline: False
```
**Symbols:**

```
ffffffff8220f6b3-ffffffff8220f6d3: bpf_sk_lookup_assign.cold (STB_LOCAL)
ffffffff81f2b520-ffffffff81f2b66e: bpf_sk_lookup_assign (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
