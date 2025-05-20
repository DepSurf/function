# Function: <code>cgroup_favor_dynmods</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cgroup_favor_dynmods(struct cgroup_root *root, bool favor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120684b)
Location: kernel/cgroup/cgroup.c:1317
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81209840-ffffffff812098ad: cgroup_favor_dynmods (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cgroup_favor_dynmods(struct cgroup_root *root, bool favor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121c25b)
Location: kernel/cgroup/cgroup.c:1301
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff8121ef90-ffffffff8121effd: cgroup_favor_dynmods (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_favor_dynmods(struct cgroup_root *root, bool favor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81233f8b)
Location: kernel/cgroup/cgroup.c:1281
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81236c20-ffffffff81236c8d: cgroup_favor_dynmods (STB_GLOBAL)
```
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
