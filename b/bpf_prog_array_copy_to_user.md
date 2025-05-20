# Function: <code>bpf_prog_array_copy_to_user</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *progs, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e0a0)
Location: kernel/bpf/core.c:1475
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff8119e0a0-ffffffff8119e14b: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *progs, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b27d0)
Location: kernel/bpf/core.c:1592
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811b27d0-ffffffff811b28aa: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c1320)
Location: kernel/bpf/core.c:1846
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811c1320-ffffffff811c1420: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1aa0)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811d1aa0-ffffffff811d1b6f: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de020)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811de020-ffffffff811de109: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faae0)
Location: kernel/bpf/core.c:1923
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811faae0-ffffffff811fabc9: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9d30)
Location: kernel/bpf/core.c:1925
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811f9d30-ffffffff811f9e19: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faca0)
Location: kernel/bpf/core.c:2021
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811faca0-ffffffff811fad86: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c3b0)
Location: kernel/bpf/core.c:2034
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff8122c3b0-ffffffff8122c496: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e000)
Location: kernel/bpf/core.c:2320
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff8126e000-ffffffff8126e0ec: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3610)
Location: kernel/bpf/core.c:2314
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff812c3610-ffffffff812c36fc: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea460)
Location: kernel/bpf/core.c:2331
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff812ea460-ffffffff812ea54c: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308770)
Location: kernel/bpf/core.c:2507
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff81308770-ffffffff8130885c: bpf_prog_array_copy_to_user (STB_GLOBAL)
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f078)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffff80001025f078-ffff80001025f2bc: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492580)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
c0492580-c04926f0: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000304050)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
c000000000304050-c0000000003041c8: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d188)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffe00019d188-ffffffe00019d26a: bpf_prog_array_copy_to_user (STB_GLOBAL)
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6640)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811d6640-ffffffff811d6729: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c9400)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811c9400-ffffffff811c94e9: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4410)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811d4410-ffffffff811d44f9: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array *array, __u32 *prog_ids, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2730)
Location: kernel/bpf/core.c:1845
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
**Symbols:**

```
ffffffff811e2730-ffffffff811e2819: bpf_prog_array_copy_to_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog_array *array</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog_array *progs</code>
</li>
</ul>
</details>
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
