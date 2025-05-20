# Function: <code>cgroup_enable_threaded</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113396e)
Location: kernel/cgroup/cgroup.c:3174
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff81142056)
Location: kernel/cgroup/cgroup.c:3192
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff8114dac5)
Location: kernel/cgroup/cgroup.c:3237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff81159875)
Location: kernel/cgroup/cgroup.c:3377
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff811654e8)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_enable_threaded(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811751a0)
Location: kernel/cgroup/cgroup.c:3319
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
```
**Symbols:**

```
ffffffff811751a0-ffffffff811752e3: cgroup_enable_threaded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_enable_threaded(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171e50)
Location: kernel/cgroup/cgroup.c:3315
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
```
**Symbols:**

```
ffffffff81171e50-ffffffff81171f93: cgroup_enable_threaded (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff81173e45)
Location: kernel/cgroup/cgroup.c:3328
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff8119aed5)
Location: kernel/cgroup/cgroup.c:3383
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff811cb086)
Location: kernel/cgroup/cgroup.c:3394
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff8120e4b6)
Location: kernel/cgroup/cgroup.c:3495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff81223eb6)
Location: kernel/cgroup/cgroup.c:3464
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff8123bb96)
Location: kernel/cgroup/cgroup.c:3473
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffff8000101d6fa0)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (c0419c30)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (c0000000002434a4)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffe0001500dc)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff8115db08)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff81150de8)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff8115b8d8)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
In kernel/cgroup/cgroup.c (ffffffff81168998)
Location: kernel/cgroup/cgroup.c:3378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_write
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
</ul>
