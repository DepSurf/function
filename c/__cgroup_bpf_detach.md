# Function: <code>__cgroup_bpf_detach</code>

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
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 unused_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b2c20)
Location: kernel/bpf/cgroup.c:296
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff811b2c20-ffffffff811b2e2c: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 unused_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d22d0)
Location: kernel/bpf/cgroup.c:295
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff811d22d0-ffffffff811d24de: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type, u32 unused_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e2130)
Location: kernel/bpf/cgroup.c:365
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff811e2130-ffffffff811e226d: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f92a0)
Location: kernel/bpf/cgroup.c:420
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff811f92a0-ffffffff811f93d5: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81206370)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff81206370-ffffffff812064a5: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122dc50)
Location: kernel/bpf/cgroup.c:654
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff8122dc50-ffffffff8122de16: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81236110)
Location: kernel/bpf/cgroup.c:667
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff81236110-ffffffff812362bf: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123a360)
Location: kernel/bpf/cgroup.c:667
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff8123a360-ffffffff8123a51a: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81274db0)
Location: kernel/bpf/cgroup.c:681
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff81274db0-ffffffff8127505e: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:788
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_release
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff812c3480-ffffffff812c3971: __cgroup_bpf_detach (STB_LOCAL)
ffffffff81e6ab8f-ffffffff81e6abbc: __cgroup_bpf_detach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:949
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_release
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81327ba0-ffffffff81328029: __cgroup_bpf_detach (STB_LOCAL)
ffffffff82061c41-ffffffff82061c64: __cgroup_bpf_detach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:949
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_release
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81357f00-ffffffff81358399: __cgroup_bpf_detach (STB_LOCAL)
ffffffff820e1379-ffffffff820e13a2: __cgroup_bpf_detach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, struct bpf_cgroup_link *link, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:950
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_release
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
**Symbols:**

```
ffffffff81380a80-ffffffff81380f18: __cgroup_bpf_detach (STB_LOCAL)
ffffffff821bdd88-ffffffff821bddb1: __cgroup_bpf_detach.cold (STB_LOCAL)
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
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028f5f8)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffff80001028f5f8-ffff80001028f75c: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bef28)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
c04bef28-c04bf0b8: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033c3c0)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
c00000000033c3c0-c00000000033c5e0: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c2680)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffe0001c2680-ffffffe0001c27c6: __cgroup_bpf_detach (STB_GLOBAL)
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
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fe990)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff811fe990-ffffffff811feac5: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f16e0)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff811f16e0-ffffffff811f1815: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fc760)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff811fc760-ffffffff811fc895: __cgroup_bpf_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_detach(struct cgroup *cgrp, struct bpf_prog *prog, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120b3d0)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_bpf_detach
```
**Symbols:**

```
ffffffff8120b3d0-ffffffff8120b505: __cgroup_bpf_detach (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 unused_flags</code>
</li>
</ul>
</details>
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
<code>struct bpf_cgroup_link *link</code>
</li>
<li>
<b>Param reordered. </b>
<code>cgrp, prog, type</code> ➡️ <code>cgrp, prog, link, type</code>
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
