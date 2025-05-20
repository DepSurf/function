# Function: <code>cgroup_path_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811133b0)
Location: kernel/cgroup.c:2288
Inline: False
Direct callers:
  - kernel/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff811133b0-ffffffff81113428: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111b880)
Location: kernel/cgroup.c:2330
Inline: False
Direct callers:
  - kernel/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff8111b880-ffffffff8111b8f6: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81123bd0)
Location: kernel/cgroup.c:2336
Inline: False
Direct callers:
  - kernel/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff81123bd0-ffffffff81123c44: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124680)
Location: kernel/cgroup/cgroup.c:1924
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff81124680-ffffffff811246f3: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81130800)
Location: kernel/cgroup/cgroup.c:2102
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff81130800-ffffffff81130873: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113eee0)
Location: kernel/cgroup/cgroup.c:2120
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff8113eee0-ffffffff8113ef53: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a900)
Location: kernel/cgroup/cgroup.c:2161
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff8114a900-ffffffff8114a973: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156080)
Location: kernel/cgroup/cgroup.c:2297
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff81156080-ffffffff811560f7: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161ce0)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff81161ce0-ffffffff81161d57: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811713b0)
Location: kernel/cgroup/cgroup.c:2225
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff811713b0-ffffffff8117143d: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116de20)
Location: kernel/cgroup/cgroup.c:2221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff8116de20-ffffffff8116dead: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116eda0)
Location: kernel/cgroup/cgroup.c:2234
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff8116eda0-ffffffff8116ee2d: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81195030)
Location: kernel/cgroup/cgroup.c:2289
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff81195030-ffffffff81195115: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c4990)
Location: kernel/cgroup/cgroup.c:2293
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff811c4990-ffffffff811c4a75: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81206490)
Location: kernel/cgroup/cgroup.c:2354
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/bpf/cgroup_iter.c:bpf_iter_cgroup_show_fdinfo
```
**Symbols:**

```
ffffffff81206490-ffffffff81206575: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121bb70)
Location: kernel/cgroup/cgroup.c:2362
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/bpf/cgroup_iter.c:bpf_iter_cgroup_show_fdinfo
```
**Symbols:**

```
ffffffff8121bb70-ffffffff8121bc55: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812372e0)
Location: kernel/cgroup/cgroup.c:2371
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/bpf/cgroup_iter.c:bpf_iter_cgroup_show_fdinfo
```
**Symbols:**

```
ffffffff812372e0-ffffffff81237356: cgroup_path_ns (STB_GLOBAL)
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
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d3028)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffff8000101d3028-ffff8000101d3114: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0415e74)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
c0415e74-c0415efc: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023e160)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
c00000000023e160-c00000000023e240: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014c8c6)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffe00014c8c6-ffffffe00014c984: cgroup_path_ns (STB_GLOBAL)
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
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a300)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff8115a300-ffffffff8115a377: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d5f0)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff8114d5f0-ffffffff8114d661: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811580d0)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff811580d0-ffffffff81158147: cgroup_path_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_path_ns(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165130)
Location: kernel/cgroup/cgroup.c:2298
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
**Symbols:**

```
ffffffff81165130-ffffffff8116519e: cgroup_path_ns (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>int</code>
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
