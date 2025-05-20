# Function: <code>parse_cgroup_root_flags</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_cgroup_root_flags(char *data, unsigned int *root_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81121e70)
Location: kernel/cgroup/cgroup.c:1550
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff81121e70-ffffffff81121ee3: parse_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_cgroup_root_flags(char *data, unsigned int *root_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112d860)
Location: kernel/cgroup/cgroup.c:1721
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff8112d860-ffffffff8112d8d3: parse_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int parse_cgroup_root_flags(char *data, unsigned int *root_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1737
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff8113ba50-ffffffff8113babb: parse_cgroup_root_flags (STB_LOCAL)
ffffffff81143a28-ffffffff81143a41: parse_cgroup_root_flags.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int parse_cgroup_root_flags(char *data, unsigned int *root_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1775
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff81147250-ffffffff811472be: parse_cgroup_root_flags (STB_LOCAL)
ffffffff8114f538-ffffffff8114f551: parse_cgroup_root_flags.cold.49 (STB_LOCAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
