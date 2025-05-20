# Function: <code>check_cgroupfs_options</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c150)
Location: kernel/cgroup/cgroup-v1.c:1005
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8115c150-ffffffff8115c278: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811680f0)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff811680f0-ffffffff81168218: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811796b0)
Location: kernel/cgroup/cgroup-v1.c:981
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff811796b0-ffffffff8117980b: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81176420)
Location: kernel/cgroup/cgroup-v1.c:986
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81176420-ffffffff8117657b: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81176f80)
Location: kernel/cgroup/cgroup-v1.c:992
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81176f80-ffffffff811770db: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1013
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8119eeb0-ffffffff8119f02d: check_cgroupfs_options (STB_LOCAL)
ffffffff81cb30e8-ffffffff81cb3125: check_cgroupfs_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1004
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff811cf660-ffffffff811cf7cc: check_cgroupfs_options (STB_LOCAL)
ffffffff81e63edd-ffffffff81e63f19: check_cgroupfs_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1016
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81212e90-ffffffff81212ffc: check_cgroupfs_options (STB_LOCAL)
ffffffff8205c37b-ffffffff8205c3b7: check_cgroupfs_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1016
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff812287a0-ffffffff8122890c: check_cgroupfs_options (STB_LOCAL)
ffffffff820dab8e-ffffffff820dabca: check_cgroupfs_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1015
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff812405b0-ffffffff8124071c: check_cgroupfs_options (STB_LOCAL)
ffffffff821b6821-ffffffff821b685d: check_cgroupfs_options.cold (STB_LOCAL)
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
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffff8000101dac50)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffff8000101dac50-ffff8000101dadb4: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c041d438)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
c041d438-c041d5b0: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (c000000000247cf0)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
c000000000247cf0-c000000000247ed0: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffe000153158)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffe000153158-ffffffe000153290: check_cgroupfs_options (STB_LOCAL)
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
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81160710)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81160710-ffffffff81160838: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81153980)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81153980-ffffffff81153aa8: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e4e0)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8115e4e0-ffffffff8115e608: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_cgroupfs_options(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b910)
Location: kernel/cgroup/cgroup-v1.c:987
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8116b910-ffffffff8116ba38: check_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
