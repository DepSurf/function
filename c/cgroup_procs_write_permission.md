# Function: <code>cgroup_procs_write_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111701d)
Location: kernel/cgroup.c:2778
Inline: True
Inline callers:
  - kernel/cgroup.c:__cgroup_procs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111e3e3)
Location: kernel/cgroup.c:2836
Inline: True
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
In kernel/cgroup.c (ffffffff81126773)
Location: kernel/cgroup.c:2845
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff8112740f)
Location: kernel/cgroup/cgroup.c:2418
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112e520)
Location: kernel/cgroup/cgroup.c:4318
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8112e520-ffffffff8112e65c: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113bc40)
Location: kernel/cgroup/cgroup.c:4355
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8113bc40-ffffffff8113bd66: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81147440)
Location: kernel/cgroup/cgroup.c:4424
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81147440-ffffffff81147566: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811526b0)
Location: kernel/cgroup/cgroup.c:4714
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff811526b0-ffffffff811527d8: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e300)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8115e300-ffffffff8115e428: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f470)
Location: kernel/cgroup/cgroup.c:4679
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8116f470-ffffffff8116f5a2: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116bf80)
Location: kernel/cgroup/cgroup.c:4680
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff8116bf80-ffffffff8116c0b2: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116cf07)
Location: kernel/cgroup/cgroup.c:4693
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81192bee)
Location: kernel/cgroup/cgroup.c:4865
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff811c346b)
Location: kernel/cgroup/cgroup.c:4876
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81205538)
Location: kernel/cgroup/cgroup.c:5073
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff8121ad48)
Location: kernel/cgroup/cgroup.c:5050
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81232ab8)
Location: kernel/cgroup/cgroup.c:5086
Inline: True
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
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101ceaf0)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffff8000101ceaf0-ffff8000101cec40: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0411fc8)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
c0411fc8-c041210c: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000238b40)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
c000000000238b40-c000000000238cc8: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014938e)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffe00014938e-ffffffe000149490: cgroup_procs_write_permission (STB_LOCAL)
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
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156920)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81156920-ffffffff81156a48: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149c40)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff81149c40-ffffffff81149d68: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811546f0)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff811546f0-ffffffff81154818: cgroup_procs_write_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811615f0)
Location: kernel/cgroup/cgroup.c:4729
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
**Symbols:**

```
ffffffff811615f0-ffffffff81161718: cgroup_procs_write_permission (STB_LOCAL)
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
