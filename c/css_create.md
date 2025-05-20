# Function: <code>css_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111d173)
Location: kernel/cgroup.c:5154
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811254a3)
Location: kernel/cgroup.c:5171
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81125b6f)
Location: kernel/cgroup/cgroup.c:4124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131f4f)
Location: kernel/cgroup/cgroup.c:4719
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81140682)
Location: kernel/cgroup/cgroup.c:4757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c102)
Location: kernel/cgroup/cgroup.c:4844
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157ce9)
Location: kernel/cgroup/cgroup.c:5146
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
In kernel/cgroup/cgroup.c (ffffffff8116395f)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:5118
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff81170210-ffffffff81170422: css_create (STB_LOCAL)
ffffffff811787dc-ffffffff81178835: css_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116cd50)
Location: kernel/cgroup/cgroup.c:5119
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff8116cd50-ffffffff8116cf36: css_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116d9b0)
Location: kernel/cgroup/cgroup.c:5103
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff8116d9b0-ffffffff8116db96: css_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81193280)
Location: kernel/cgroup/cgroup.c:5293
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff81193280-ffffffff81193487: css_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c4540)
Location: kernel/cgroup/cgroup.c:5304
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff811c4540-ffffffff811c476f: css_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81206950)
Location: kernel/cgroup/cgroup.c:5521
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff81206950-ffffffff81206b7e: css_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121c510)
Location: kernel/cgroup/cgroup.c:5502
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff8121c510-ffffffff8121c73e: css_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_create(struct cgroup *cgrp, struct cgroup_subsys *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812340a0)
Location: kernel/cgroup/cgroup.c:5538
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
**Symbols:**

```
ffffffff812340a0-ffffffff812342ce: css_create (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffff8000101d5140)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0417ca8)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
In kernel/cgroup/cgroup.c (c0000000002406a0)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
In kernel/cgroup/cgroup.c (ffffffe00014e3ca)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
In kernel/cgroup/cgroup.c (ffffffff8115bf7f)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
In kernel/cgroup/cgroup.c (ffffffff8114f26f)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
In kernel/cgroup/cgroup.c (ffffffff81159d4f)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
In kernel/cgroup/cgroup.c (ffffffff81166dbf)
Location: kernel/cgroup/cgroup.c:5161
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
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
