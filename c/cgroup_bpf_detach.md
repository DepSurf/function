# Function: <code>cgroup_bpf_detach</code>

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
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81135260)
Location: kernel/cgroup/cgroup.c:5855
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff81135260-ffffffff811352b2: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81143980)
Location: kernel/cgroup/cgroup.c:5893
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81143980-ffffffff811439d2: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f490)
Location: kernel/cgroup/cgroup.c:5996
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff8114f490-ffffffff8114f4e2: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b350)
Location: kernel/cgroup/cgroup.c:6420
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff8115b350-ffffffff8115b39c: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81167010)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81167010-ffffffff8116705c: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81178740)
Location: kernel/cgroup/cgroup.c:6510
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81178740-ffffffff8117878e: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175500)
Location: kernel/cgroup/cgroup.c:6502
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81175500-ffffffff8117554e: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81176070)
Location: kernel/cgroup/cgroup.c:6480
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81176070-ffffffff811760be: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d630)
Location: kernel/cgroup/cgroup.c:6703
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff8119d630-ffffffff8119d67e: cgroup_bpf_detach (STB_GLOBAL)
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
In kernel/bpf/cgroup.c (ffffffff812c4ef8)
Location: kernel/bpf/cgroup.c:836
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
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
In kernel/bpf/cgroup.c (ffffffff8132a3f8)
Location: kernel/bpf/cgroup.c:1007
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
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
In kernel/bpf/cgroup.c (ffffffff8135a538)
Location: kernel/bpf/cgroup.c:1007
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
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
In kernel/bpf/cgroup.c (ffffffff813830f8)
Location: kernel/bpf/cgroup.c:1008
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
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
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8f18)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffff8000101d8f18-ffff8000101d8f84: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041bdbc)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
c041bdbc-c041be10: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002464b0)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
c0000000002464b0-c000000000246534: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151ef4)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffe000151ef4-ffffffe000151f52: cgroup_bpf_detach (STB_GLOBAL)
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
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f630)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff8115f630-ffffffff8115f67c: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811528c0)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff811528c0-ffffffff8115290c: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d400)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff8115d400-ffffffff8115d44c: cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a630)
Location: kernel/cgroup/cgroup.c:6439
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff8116a630-ffffffff8116a67c: cgroup_bpf_detach (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
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
