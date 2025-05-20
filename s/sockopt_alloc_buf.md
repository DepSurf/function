# Function: <code>sockopt_alloc_buf</code>

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
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7ee0)
Location: kernel/bpf/cgroup.c:957
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff811f7ee0-ffffffff811f7f38: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204f47)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122cac0)
Location: kernel/bpf/cgroup.c:1277
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff8122cac0-ffffffff8122cb27: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234f40)
Location: kernel/bpf/cgroup.c:1301
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff81234f40-ffffffff81234fa7: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen, struct bpf_sockopt_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812388c0)
Location: kernel/bpf/cgroup.c:1305
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff812388c0-ffffffff8123894b: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen, struct bpf_sockopt_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81272ee0)
Location: kernel/bpf/cgroup.c:1335
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff81272ee0-ffffffff81272f6b: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen, struct bpf_sockopt_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c27d0)
Location: kernel/bpf/cgroup.c:1503
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff812c27d0-ffffffff812c286b: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen, struct bpf_sockopt_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81326fb0)
Location: kernel/bpf/cgroup.c:1742
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff81326fb0-ffffffff8132704b: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen, struct bpf_sockopt_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813572f0)
Location: kernel/bpf/cgroup.c:1742
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff813572f0-ffffffff8135738b: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen, struct bpf_sockopt_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137fe20)
Location: kernel/bpf/cgroup.c:1757
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
ffffffff8137fe20-ffffffff8137febb: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028e3c8)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern *ctx, int max_optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bd270)
Location: kernel/bpf/cgroup.c:967
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
**Symbols:**

```
c04bd270-c04bd2d0: sockopt_alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000339df0)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c1574)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fd567)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f02b7)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fb337)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209eb8)
Location: kernel/bpf/cgroup.c:967
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_sockopt_buf *buf</code>
</li>
</ul>
</details>
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
</ul>
