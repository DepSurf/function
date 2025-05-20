# Function: <code>pidlist_array_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81118b10)
Location: kernel/cgroup.c:4422
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81118b10-ffffffff81118e67: pidlist_array_load (STB_LOCAL)
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
In kernel/cgroup.c (ffffffff811207b2)
Location: kernel/cgroup.c:4617
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
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
In kernel/cgroup.c (ffffffff81128c9f)
Location: kernel/cgroup.c:4630
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff8112a23d)
Location: kernel/cgroup/cgroup-v1.c:353
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81136f10)
Location: kernel/cgroup/cgroup-v1.c:358
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81136f10-ffffffff81137189: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811456f0)
Location: kernel/cgroup/cgroup-v1.c:358
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff811456f0-ffffffff8114598f: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811512b0)
Location: kernel/cgroup/cgroup-v1.c:361
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff811512b0-ffffffff8115154f: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c580)
Location: kernel/cgroup/cgroup-v1.c:349
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff8115c580-ffffffff8115c81c: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81167d50)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81167d50-ffffffff81167fc8: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81179b50)
Location: kernel/cgroup/cgroup-v1.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81179b50-ffffffff81179cf9: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811768c0)
Location: kernel/cgroup/cgroup-v1.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff811768c0-ffffffff81176a69: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811772d0)
Location: kernel/cgroup/cgroup-v1.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff811772d0-ffffffff811775ed: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8119ea40)
Location: kernel/cgroup/cgroup-v1.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff8119ea40-ffffffff8119ed5d: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf1e0)
Location: kernel/cgroup/cgroup-v1.c:326
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff811cf1e0-ffffffff811cf4ed: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81212b70)
Location: kernel/cgroup/cgroup-v1.c:326
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81212b70-ffffffff81212e7d: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81228480)
Location: kernel/cgroup/cgroup-v1.c:326
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81228480-ffffffff8122878d: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81240280)
Location: kernel/cgroup/cgroup-v1.c:326
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81240280-ffffffff81240598: pidlist_array_load (STB_LOCAL)
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
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffff8000101da860)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffff8000101da860-ffff8000101daae0: pidlist_array_load (STB_LOCAL)
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
In kernel/cgroup/cgroup-v1.c (c041d1cc)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c0000000002488d0)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
c0000000002488d0-c000000000248c3c: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffe000152e38)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffe000152e38-ffffffe000153038: pidlist_array_load (STB_LOCAL)
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
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81160370)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff81160370-ffffffff811605e8: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811535e0)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff811535e0-ffffffff81153858: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e140)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff8115e140-ffffffff8115e3b8: pidlist_array_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pidlist_array_load(struct cgroup *cgrp, enum cgroup_filetype type, struct cgroup_pidlist **lp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b570)
Location: kernel/cgroup/cgroup-v1.c:330
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
**Symbols:**

```
ffffffff8116b570-ffffffff8116b7e8: pidlist_array_load (STB_LOCAL)
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
