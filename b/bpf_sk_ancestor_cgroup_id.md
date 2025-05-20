# Function: <code>bpf_sk_ancestor_cgroup_id</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2c140)
Location: net/core/filter.c:4127
Inline: False
```
**Symbols:**

```
ffffffff81a2c140-ffffffff81a2c197: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e840)
Location: net/core/filter.c:4533
Inline: False
```
**Symbols:**

```
ffffffff81a2e840-ffffffff81a2e8cd: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a15e90)
Location: net/core/filter.c:4472
Inline: False
```
**Symbols:**

```
ffffffff81a15e90-ffffffff81a15f18: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4530
Inline: False
```
**Symbols:**

```
ffffffff81d375d5-ffffffff81d375f5: bpf_sk_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81acc000-ffffffff81acc09d: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4821
Inline: False
```
**Symbols:**

```
ffffffff81f03e92-ffffffff81f03eb2: bpf_sk_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81c48860-ffffffff81c48923: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4839
Inline: False
```
**Symbols:**

```
ffffffff820ac5ca-ffffffff820ac5ea: bpf_sk_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81dfd390-ffffffff81dfd446: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4893
Inline: False
```
**Symbols:**

```
ffffffff8212db83-ffffffff8212dbab: bpf_sk_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81e6de70-ffffffff81e6def0: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_ancestor_cgroup_id(u64 sk, u64 ancestor_level, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4967
Inline: False
```
**Symbols:**

```
ffffffff8220f8c8-ffffffff8220f8f0: bpf_sk_ancestor_cgroup_id.cold (STB_LOCAL)
ffffffff81f2cf00-ffffffff81f2cf80: bpf_sk_ancestor_cgroup_id (STB_GLOBAL)
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
