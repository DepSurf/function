# Function: <code>compute_effective_progs</code>

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
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b2330)
Location: kernel/bpf/cgroup.c:94
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff811b2330-ffffffff811b243a: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d18c0)
Location: kernel/bpf/cgroup.c:94
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff811d18c0-ffffffff811d19b2: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e14a0)
Location: kernel/bpf/cgroup.c:99
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff811e14a0-ffffffff811e15bc: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f71e0)
Location: kernel/bpf/cgroup.c:135
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff811f71e0-ffffffff811f730b: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812041a0)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff812041a0-ffffffff812042c4: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122d1b0)
Location: kernel/bpf/cgroup.c:212
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff8122d1b0-ffffffff8122d2e9: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81235450)
Location: kernel/bpf/cgroup.c:227
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff81235450-ffffffff81235591: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81238bd0)
Location: kernel/bpf/cgroup.c:227
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff81238bd0-ffffffff81238d11: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812736f0)
Location: kernel/bpf/cgroup.c:227
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff812736f0-ffffffff81273990: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c3030)
Location: kernel/bpf/cgroup.c:266
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff812c3030-ffffffff812c32e8: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81327800)
Location: kernel/bpf/cgroup.c:401
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff81327800-ffffffff813279e9: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81357b40)
Location: kernel/bpf/cgroup.c:401
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff81357b40-ffffffff81357d4c: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813806c0)
Location: kernel/bpf/cgroup.c:401
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff813806c0-ffffffff813808cb: compute_effective_progs (STB_LOCAL)
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
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028c978)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffff80001028c978-ffff80001028cad4: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bc070)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
c04bc070-c04bc1c8: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000338e40)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
c000000000338e40-c000000000339008: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c037a)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffe0001c037a-ffffffe0001c047e: compute_effective_progs (STB_LOCAL)
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
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fc7c0)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff811fc7c0-ffffffff811fc8e4: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811ef510)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff811ef510-ffffffff811ef634: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fa590)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff811fa590-ffffffff811fa6b4: compute_effective_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compute_effective_progs(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_prog_array **array);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209050)
Location: kernel/bpf/cgroup.c:138
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
**Symbols:**

```
ffffffff81209050-ffffffff81209174: compute_effective_progs (STB_LOCAL)
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
