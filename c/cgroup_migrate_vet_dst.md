# Function: <code>cgroup_migrate_vet_dst</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811316e2)
Location: kernel/cgroup/cgroup.c:2369
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8112e230-ffffffff8112e2ab: cgroup_migrate_vet_dst.part.27 (STB_LOCAL)
ffffffff81130a70-ffffffff81130a90: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113fe75)
Location: kernel/cgroup/cgroup.c:2387
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8113deb0-ffffffff8113df35: cgroup_migrate_vet_dst.part.30 (STB_LOCAL)
ffffffff8113f140-ffffffff8113f160: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114b895)
Location: kernel/cgroup/cgroup.c:2428
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811498a0-ffffffff81149925: cgroup_migrate_vet_dst.part.31 (STB_LOCAL)
ffffffff8114ab60-ffffffff8114ab80: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811562e0)
Location: kernel/cgroup/cgroup.c:2571
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811562e0-ffffffff81156353: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161f40)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81161f40-ffffffff81161fb3: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117802c)
Location: kernel/cgroup/cgroup.c:2498
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8116f8d0-ffffffff8116f960: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
ffffffff81173380-ffffffff81173417: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174d4b)
Location: kernel/cgroup/cgroup.c:2494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8116c380-ffffffff8116c410: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
ffffffff81170080-ffffffff81170117: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ce50)
Location: kernel/cgroup/cgroup.c:2507
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8116ce50-ffffffff8116cede: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
ffffffff81170cb0-ffffffff81170d45: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81192b40)
Location: kernel/cgroup/cgroup.c:2562
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81192b40-ffffffff81192bce: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
ffffffff81197380-ffffffff81197415: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c33d0)
Location: kernel/cgroup/cgroup.c:2566
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811c33d0-ffffffff811c344c: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
ffffffff811c73d0-ffffffff811c73fc: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812055b7)
Location: kernel/cgroup/cgroup.c:2668
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8120a250-ffffffff8120a2e6: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121adc7)
Location: kernel/cgroup/cgroup.c:2637
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8121f830-ffffffff8121f8c9: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81232b37)
Location: kernel/cgroup/cgroup.c:2646
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81237580-ffffffff81237619: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d43b8)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffff8000101d1c40-ffff8000101d1cd8: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
ffff8000101d3340-ffff8000101d3390: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c0417014)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c0414bd8-c0414c5c: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
c04160ec-c0416124: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023e4d0)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c00000000023e4d0-c00000000023e5b8: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014d8f0)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffe00014b6e6-ffffffe00014b74c: cgroup_migrate_vet_dst.part.0 (STB_LOCAL)
ffffffe00014cb84-ffffffe00014cbc0: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a560)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8115a560-ffffffff8115a5d3: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d850)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114d850-ffffffff8114d8c3: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158330)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81158330-ffffffff811583a3: cgroup_migrate_vet_dst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cgroup_migrate_vet_dst(struct cgroup *dst_cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165380)
Location: kernel/cgroup/cgroup.c:2572
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81165380-ffffffff811653f3: cgroup_migrate_vet_dst (STB_GLOBAL)
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
