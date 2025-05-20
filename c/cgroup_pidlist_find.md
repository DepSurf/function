# Function: <code>cgroup_pidlist_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113010)
Location: kernel/cgroup.c:4373
Inline: False
Direct callers:
  - kernel/cgroup.c:pidlist_array_load
  - kernel/cgroup.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81113010-ffffffff81113070: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111a6a0)
Location: kernel/cgroup.c:4568
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff8111a6a0-ffffffff8111a703: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81122210)
Location: kernel/cgroup.c:4581
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81122210-ffffffff81122273: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811291b0)
Location: kernel/cgroup/cgroup-v1.c:288
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff811291b0-ffffffff81129213: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81135e10)
Location: kernel/cgroup/cgroup-v1.c:293
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81135e10-ffffffff81135e73: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81144630)
Location: kernel/cgroup/cgroup-v1.c:293
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81144630-ffffffff81144693: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81150140)
Location: kernel/cgroup/cgroup-v1.c:296
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81150140-ffffffff811501a3: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c040)
Location: kernel/cgroup/cgroup-v1.c:300
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff8115c040-ffffffff8115c0a0: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81167c60)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81167c60-ffffffff81167cc0: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81179d63)
Location: kernel/cgroup/cgroup-v1.c:276
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81176ad3)
Location: kernel/cgroup/cgroup-v1.c:276
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
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
In kernel/cgroup/cgroup-v1.c (ffffffff8117779c)
Location: kernel/cgroup/cgroup-v1.c:276
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
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
In kernel/cgroup/cgroup-v1.c (ffffffff8119f090)
Location: kernel/cgroup/cgroup-v1.c:280
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
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
In kernel/cgroup/cgroup-v1.c (ffffffff811cfb10)
Location: kernel/cgroup/cgroup-v1.c:277
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
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
In kernel/cgroup/cgroup-v1.c (ffffffff81213500)
Location: kernel/cgroup/cgroup-v1.c:277
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
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
In kernel/cgroup/cgroup-v1.c (ffffffff81228e10)
Location: kernel/cgroup/cgroup-v1.c:277
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
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
In kernel/cgroup/cgroup-v1.c (ffffffff81240c60)
Location: kernel/cgroup/cgroup-v1.c:277
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
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
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffff8000101da740)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffff8000101da740-ffff8000101da7c4: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c041cfb0)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
c041cfb0-c041d03c: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c000000000247ad0)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
c000000000247ad0-c000000000247b8c: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffe000152d40)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffe000152d40-ffffffe000152da8: cgroup_pidlist_find (STB_LOCAL)
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
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81160280)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff81160280-ffffffff811602e0: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811534f0)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff811534f0-ffffffff81153550: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e050)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff8115e050-ffffffff8115e0b0: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_pidlist *cgroup_pidlist_find(struct cgroup *cgrp, enum cgroup_filetype type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b480)
Location: kernel/cgroup/cgroup-v1.c:281
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
**Symbols:**

```
ffffffff8116b480-ffffffff8116b4e0: cgroup_pidlist_find (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
