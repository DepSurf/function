# Function: <code>bpf_prog_array_is_empty</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1a60)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811d1a60-ffffffff811d1a98: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ddfe0)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811ddfe0-ffffffff811de018: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faaa0)
Location: kernel/bpf/core.c:1893
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811faaa0-ffffffff811faad8: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9cf0)
Location: kernel/bpf/core.c:1895
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811f9cf0-ffffffff811f9d28: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fac60)
Location: kernel/bpf/core.c:1991
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811fac60-ffffffff811fac98: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c370)
Location: kernel/bpf/core.c:2004
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff8122c370-ffffffff8122c3a8: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126dfb0)
Location: kernel/bpf/core.c:2290
Inline: False
```
**Symbols:**

```
ffffffff8126dfb0-ffffffff8126dff8: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c35b0)
Location: kernel/bpf/core.c:2284
Inline: False
```
**Symbols:**

```
ffffffff812c35b0-ffffffff812c35f8: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea400)
Location: kernel/bpf/core.c:2301
Inline: False
```
**Symbols:**

```
ffffffff812ea400-ffffffff812ea448: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308710)
Location: kernel/bpf/core.c:2477
Inline: False
```
**Symbols:**

```
ffffffff81308710-ffffffff81308758: bpf_prog_array_is_empty (STB_GLOBAL)
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
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f010)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffff80001025f010-ffff80001025f074: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c049252c)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
c049252c-c0492580: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303ff0)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
c000000000303ff0-c000000000304048: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d13e)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffe00019d13e-ffffffe00019d188: bpf_prog_array_is_empty (STB_GLOBAL)
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
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6600)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811d6600-ffffffff811d6638: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c93c0)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811c93c0-ffffffff811c93f8: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d43d0)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811d43d0-ffffffff811d4408: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bpf_prog_array_is_empty(struct bpf_prog_array *array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e26f0)
Location: kernel/bpf/core.c:1815
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811e26f0-ffffffff811e2728: bpf_prog_array_is_empty (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
