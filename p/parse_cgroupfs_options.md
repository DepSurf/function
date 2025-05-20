# Function: <code>parse_cgroupfs_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int parse_cgroupfs_options(char *data, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81112520)
Location: kernel/cgroup.c:1658
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81112520-ffffffff811128b3: parse_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int parse_cgroupfs_options(char *data, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81119cc0)
Location: kernel/cgroup.c:1693
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff81119cc0-ffffffff8111a017: parse_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int parse_cgroupfs_options(char *data, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811217a0)
Location: kernel/cgroup.c:1698
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff811217a0-ffffffff81121af7: parse_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_cgroupfs_options(char *data, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81129480)
Location: kernel/cgroup/cgroup-v1.c:863
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff81129480-ffffffff811297ea: parse_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_cgroupfs_options(char *data, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff811360e0)
Location: kernel/cgroup/cgroup-v1.c:918
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff811360e0-ffffffff8113646f: parse_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int parse_cgroupfs_options(char *data, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81144840)
Location: kernel/cgroup/cgroup-v1.c:906
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff81144840-ffffffff81144bf9: parse_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_cgroupfs_options(char *data, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff81150260)
Location: kernel/cgroup/cgroup-v1.c:909
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
```
**Symbols:**

```
ffffffff81150260-ffffffff81150637: parse_cgroupfs_options (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
