# Function: <code>cgroup_path_ns_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff81113350)
Location: kernel/cgroup.c:2276
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_path_ns
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_release_agent
  - kernel/cgroup.c:proc_cgroup_show
```
**Symbols:**

```
ffffffff81113350-ffffffff811133a2: cgroup_path_ns_locked.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff8111a9f0)
Location: kernel/cgroup.c:2318
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_release_agent
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff8111a9f0-ffffffff8111aa4d: cgroup_path_ns_locked.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff81122560)
Location: kernel/cgroup.c:2328
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_release_agent
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff81122560-ffffffff811225a6: cgroup_path_ns_locked.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124630)
Location: kernel/cgroup/cgroup.c:1916
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff81124630-ffffffff81124677: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811307b0)
Location: kernel/cgroup/cgroup.c:2094
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff811307b0-ffffffff811307f7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113ee90)
Location: kernel/cgroup/cgroup.c:2112
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff8113ee90-ffffffff8113eed7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a8b0)
Location: kernel/cgroup/cgroup.c:2153
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff8114a8b0-ffffffff8114a8f7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156030)
Location: kernel/cgroup/cgroup.c:2289
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff81156030-ffffffff81156077: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161c90)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff81161c90-ffffffff81161cd7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117756a)
Location: kernel/cgroup/cgroup.c:2217
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff81173260-ffffffff811732a7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117424a)
Location: kernel/cgroup/cgroup.c:2213
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff8116ff60-ffffffff8116ffa7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174e1a)
Location: kernel/cgroup/cgroup.c:2226
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff81170b90-ffffffff81170bd7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119c187)
Location: kernel/cgroup/cgroup.c:2281
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff811971b0-ffffffff8119723d: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cc474)
Location: kernel/cgroup/cgroup.c:2285
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff811c71e0-ffffffff811c727f: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120f9c4)
Location: kernel/cgroup/cgroup.c:2346
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_ns
Direct callers:
  - kernel/cgroup/cgroup.c:task_cgroup_path
```
**Symbols:**

```
ffffffff81209e00-ffffffff81209e9f: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812253e6)
Location: kernel/cgroup/cgroup.c:2354
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff8121f570-ffffffff8121f60f: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81237230)
Location: kernel/cgroup/cgroup.c:2363
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_ns
```
**Symbols:**

```
ffffffff81237230-ffffffff812372cc: cgroup_path_ns_locked (STB_GLOBAL)
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
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d2fd0)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffff8000101d2fd0-ffff8000101d3028: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0415e2c)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
c0415e2c-c0415e74: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023e0f0)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
c00000000023e0f0-c00000000023e160: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014c870)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffe00014c870-ffffffe00014c8c6: cgroup_path_ns_locked (STB_GLOBAL)
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
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a2b0)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff8115a2b0-ffffffff8115a2f7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d5a0)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff8114d5a0-ffffffff8114d5e7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158080)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff81158080-ffffffff811580c7: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup *cgrp, char *buf, size_t buflen, struct cgroup_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811650e0)
Location: kernel/cgroup/cgroup.c:2290
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
```
**Symbols:**

```
ffffffff811650e0-ffffffff81165127: cgroup_path_ns_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
