# Function: <code>__cgroup_bpf_attach</code>

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
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b2890)
Location: kernel/bpf/cgroup.c:187
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811b2890-ffffffff811b2c15: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1f30)
Location: kernel/bpf/cgroup.c:186
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811d1f30-ffffffff811d22c5: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e1cc0)
Location: kernel/bpf/cgroup.c:236
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811e1cc0-ffffffff811e212a: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f8e10)
Location: kernel/bpf/cgroup.c:291
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811f8e10-ffffffff811f9296: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81205ed0)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81205ed0-ffffffff81206368: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122d660)
Location: kernel/bpf/cgroup.c:416
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8122d660-ffffffff8122dc4f: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81235ba0)
Location: kernel/bpf/cgroup.c:433
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81235ba0-ffffffff81236110: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81239df0)
Location: kernel/bpf/cgroup.c:433
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81239df0-ffffffff8123a355: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81274620)
Location: kernel/bpf/cgroup.c:433
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81274620-ffffffff81274da4: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c4230)
Location: kernel/bpf/cgroup.c:472
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff812c4230-ffffffff812c49af: __cgroup_bpf_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81328a80)
Location: kernel/bpf/cgroup.c:607
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81328a80-ffffffff81329226: __cgroup_bpf_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81358de0)
Location: kernel/bpf/cgroup.c:607
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81358de0-ffffffff813595c2: __cgroup_bpf_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_prog *replace_prog, struct bpf_cgroup_link *link, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81381960)
Location: kernel/bpf/cgroup.c:607
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
**Symbols:**

```
ffffffff81381960-ffffffff81382171: __cgroup_bpf_attach (STB_LOCAL)
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
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028f1c8)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffff80001028f1c8-ffff80001028f5f4: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bea08)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
c04bea08-c04bef28: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033be20)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
c00000000033be20-c00000000033c3b8: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c22b8)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffe0001c22b8-ffffffe0001c2680: __cgroup_bpf_attach (STB_GLOBAL)
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
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fe4f0)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811fe4f0-ffffffff811fe988: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f1240)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811f1240-ffffffff811f16d8: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fc2c0)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811fc2c0-ffffffff811fc758: __cgroup_bpf_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120af30)
Location: kernel/bpf/cgroup.c:301
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8120af30-ffffffff8120b3c8: __cgroup_bpf_attach (STB_GLOBAL)
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
