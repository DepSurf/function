# Function: <code>update_effective_progs</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e15c0)
Location: kernel/bpf/cgroup.c:186
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811e15c0-ffffffff811e16b6: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7310)
Location: kernel/bpf/cgroup.c:229
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811f7310-ffffffff811f7469: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812042d0)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff812042d0-ffffffff81204429: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122d2f0)
Location: kernel/bpf/cgroup.c:313
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8122d2f0-ffffffff8122d43e: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812355a0)
Location: kernel/bpf/cgroup.c:330
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff812355a0-ffffffff812356d4: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81238d20)
Location: kernel/bpf/cgroup.c:330
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81238d20-ffffffff81238e52: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81273990)
Location: kernel/bpf/cgroup.c:330
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81273990-ffffffff81273b07: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c32f0)
Location: kernel/bpf/cgroup.c:369
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff812c32f0-ffffffff812c3477: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81327a00)
Location: kernel/bpf/cgroup.c:504
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81327a00-ffffffff81327b88: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81357d60)
Location: kernel/bpf/cgroup.c:504
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81357d60-ffffffff81357ee8: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813808e0)
Location: kernel/bpf/cgroup.c:504
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff813808e0-ffffffff81380a67: update_effective_progs (STB_LOCAL)
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
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028cad8)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffff80001028cad8-ffff80001028cc3c: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bc1c8)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
c04bc1c8-c04bc318: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000339010)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
c000000000339010-c000000000339218: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c047e)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffe0001c047e-ffffffe0001c05c4: update_effective_progs (STB_LOCAL)
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
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fc8f0)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811fc8f0-ffffffff811fca49: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811ef640)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811ef640-ffffffff811ef799: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fa6c0)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff811fa6c0-ffffffff811fa819: update_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int update_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209180)
Location: kernel/bpf/cgroup.c:239
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81209180-ffffffff812092d9: update_effective_progs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
