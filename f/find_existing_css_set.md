# Function: <code>find_existing_css_set</code>

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
In kernel/cgroup.c (ffffffff811156e7)
Location: kernel/cgroup.c:896
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
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
In kernel/cgroup.c (ffffffff8111c3bc)
Location: kernel/cgroup.c:941
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
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
In kernel/cgroup.c (ffffffff811246ec)
Location: kernel/cgroup.c:944
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81123a6c)
Location: kernel/cgroup/cgroup.c:837
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8112fedc)
Location: kernel/cgroup/cgroup.c:982
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8113e599)
Location: kernel/cgroup/cgroup.c:985
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81149fc9)
Location: kernel/cgroup/cgroup.c:1020
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff811553ec)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8116101c)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116f5b0)
Location: kernel/cgroup/cgroup.c:1052
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff8116f5b0-ffffffff8116f70f: find_existing_css_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116c0c0)
Location: kernel/cgroup/cgroup.c:1049
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff8116c0c0-ffffffff8116c221: find_existing_css_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116cbe0)
Location: kernel/cgroup/cgroup.c:1049
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff8116cbe0-ffffffff8116cddf: find_existing_css_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1080
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff81192810-ffffffff81192ac5: find_existing_css_set (STB_LOCAL)
ffffffff81cb2de4-ffffffff81cb2e15: find_existing_css_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1082
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff811c2e50-ffffffff811c3136: find_existing_css_set (STB_LOCAL)
ffffffff81e63c15-ffffffff81e63c46: find_existing_css_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1087
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff81205020-ffffffff81205305: find_existing_css_set (STB_LOCAL)
ffffffff8205c0c0-ffffffff8205c0f1: find_existing_css_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1071
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff8121a8f0-ffffffff8121abd5: find_existing_css_set (STB_LOCAL)
ffffffff820da8b6-ffffffff820da8e7: find_existing_css_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct css_set *find_existing_css_set(struct css_set *old_cset, struct cgroup *cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1051
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
**Symbols:**

```
ffffffff81232660-ffffffff81232945: find_existing_css_set (STB_LOCAL)
ffffffff821b6520-ffffffff821b6551: find_existing_css_set.cold (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffff8000101d2404)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (c041524c)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (c00000000023d00c)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffe00014bcd6)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8115963c)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8114c94c)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8115740c)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8116446c)
Location: kernel/cgroup/cgroup.c:1060
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
