# Function: <code>cgroup_bpf_query</code>

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
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811352c0)
Location: kernel/cgroup/cgroup.c:5865
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811352c0-ffffffff81135308: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811439e0)
Location: kernel/cgroup/cgroup.c:5903
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff811439e0-ffffffff81143a28: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f4f0)
Location: kernel/cgroup/cgroup.c:6006
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff8114f4f0-ffffffff8114f538: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b3a0)
Location: kernel/cgroup/cgroup.c:6430
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff8115b3a0-ffffffff8115b3ec: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81167060)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff81167060-ffffffff811670ac: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81178790)
Location: kernel/cgroup/cgroup.c:6521
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff81178790-ffffffff811787dc: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175550)
Location: kernel/cgroup/cgroup.c:6513
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff81175550-ffffffff8117559c: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811760c0)
Location: kernel/cgroup/cgroup.c:6491
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff811760c0-ffffffff8117610c: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d680)
Location: kernel/cgroup/cgroup.c:6714
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff8119d680-ffffffff8119d6cc: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c51a6)
Location: kernel/bpf/cgroup.c:906
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132a6c6)
Location: kernel/bpf/cgroup.c:1118
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135a806)
Location: kernel/bpf/cgroup.c:1118
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813833f6)
Location: kernel/bpf/cgroup.c:1119
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
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
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8f88)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffff8000101d8f88-ffff8000101d8ff4: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041be10)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
c041be10-c041be64: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000246540)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
c000000000246540-c0000000002465c4: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151f52)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffe000151f52-ffffffe000151fb0: cgroup_bpf_query (STB_GLOBAL)
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
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f680)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff8115f680-ffffffff8115f6cc: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81152910)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff81152910-ffffffff8115295c: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d450)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff8115d450-ffffffff8115d49c: cgroup_bpf_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup *cgrp, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a680)
Location: kernel/cgroup/cgroup.c:6449
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
```
**Symbols:**

```
ffffffff8116a680-ffffffff8116a6cc: cgroup_bpf_query (STB_GLOBAL)
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
