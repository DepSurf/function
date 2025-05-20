# Function: <code>cgroup_bpf_attach</code>

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
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81135200)
Location: kernel/cgroup/cgroup.c:5845
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff81135200-ffffffff81135252: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81143920)
Location: kernel/cgroup/cgroup.c:5883
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81143920-ffffffff81143972: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f430)
Location: kernel/cgroup/cgroup.c:5986
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff8114f430-ffffffff8114f482: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b2f0)
Location: kernel/cgroup/cgroup.c:6410
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff8115b2f0-ffffffff8115b346: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166fb0)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81166fb0-ffffffff81167006: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811786d0)
Location: kernel/cgroup/cgroup.c:6496
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff811786d0-ffffffff8117873e: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175490)
Location: kernel/cgroup/cgroup.c:6488
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81175490-ffffffff811754fe: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81176000)
Location: kernel/cgroup/cgroup.c:6466
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81176000-ffffffff8117606e: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d5c0)
Location: kernel/cgroup/cgroup.c:6689
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff8119d5c0-ffffffff8119d62e: cgroup_bpf_attach (STB_GLOBAL)
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
In kernel/bpf/cgroup.c (ffffffff812c509f)
Location: kernel/bpf/cgroup.c:565
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
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
In kernel/bpf/cgroup.c (ffffffff8132a5af)
Location: kernel/bpf/cgroup.c:724
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
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
In kernel/bpf/cgroup.c (ffffffff8135a6ef)
Location: kernel/bpf/cgroup.c:724
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
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
In kernel/bpf/cgroup.c (ffffffff813832dd)
Location: kernel/bpf/cgroup.c:724
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
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
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8ea0)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffff8000101d8ea0-ffff8000101d8f18: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041bd60)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
c041bd60-c041bdbc: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000246420)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
c000000000246420-c0000000002464ac: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151e8e)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffe000151e8e-ffffffe000151ef4: cgroup_bpf_attach (STB_GLOBAL)
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
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f5d0)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff8115f5d0-ffffffff8115f626: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81152860)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81152860-ffffffff811528b6: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d3a0)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff8115d3a0-ffffffff8115d3f6: cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a5d0)
Location: kernel/cgroup/cgroup.c:6429
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff8116a5d0-ffffffff8116a626: cgroup_bpf_attach (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct bpf_prog *replace_prog</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_cgroup_link *link</code>
</li>
<li>
<b>Param reordered. </b>
<code>cgrp, prog, type, flags</code> ➡️ <code>cgrp, prog, replace_prog, link, type, flags</code>
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
