# Function: <code>cgroup_add_file</code>

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
In kernel/cgroup.c (ffffffff81113a84)
Location: kernel/cgroup.c:3449
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup.c (ffffffff8111bc9e)
Location: kernel/cgroup.c:3636
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup.c (ffffffff81123fde)
Location: kernel/cgroup.c:3647
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff811235a1)
Location: kernel/cgroup/cgroup.c:3154
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff8112f441)
Location: kernel/cgroup/cgroup.c:3524
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff8113d8e8)
Location: kernel/cgroup/cgroup.c:3548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff811492e4)
Location: kernel/cgroup/cgroup.c:3611
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff8115470c)
Location: kernel/cgroup/cgroup.c:3867
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff8116033c)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_add_file(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811717d0)
Location: kernel/cgroup/cgroup.c:3810
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff811717d0-ffffffff81171955: cgroup_add_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_add_file(struct cgroup_subsys_state *css, struct cgroup *cgrp, struct cftype *cft);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116e440)
Location: kernel/cgroup/cgroup.c:3811
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
**Symbols:**

```
ffffffff8116e440-ffffffff8116e5c5: cgroup_add_file (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff8116f37c)
Location: kernel/cgroup/cgroup.c:3824
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff81195553)
Location: kernel/cgroup/cgroup.c:3994
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff811c1ccc)
Location: kernel/cgroup/cgroup.c:4005
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff81204330)
Location: kernel/cgroup/cgroup.c:4174
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff81219871)
Location: kernel/cgroup/cgroup.c:4151
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff81231396)
Location: kernel/cgroup/cgroup.c:4191
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffff8000101d0ef0)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (c04125d4)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (c00000000023b718)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffe00014ad12)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff8115895c)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff8114bb5c)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff8115672c)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
In kernel/cgroup/cgroup.c (ffffffff81161b36)
Location: kernel/cgroup/cgroup.c:3869
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
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
