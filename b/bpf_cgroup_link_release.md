# Function: <code>bpf_cgroup_link_release</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122de20)
Location: kernel/bpf/cgroup.c:802
Inline: True
```
**Symbols:**

```
ffffffff8122de20-ffffffff8122deb7: bpf_cgroup_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81236395)
Location: kernel/bpf/cgroup.c:813
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
```
**Symbols:**

```
ffffffff812362c0-ffffffff81236367: bpf_cgroup_link_release.part.0 (STB_LOCAL)
ffffffff81236370-ffffffff81236388: bpf_cgroup_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123a5f5)
Location: kernel/bpf/cgroup.c:813
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
```
**Symbols:**

```
ffffffff8123a520-ffffffff8123a5c7: bpf_cgroup_link_release.part.0 (STB_LOCAL)
ffffffff8123a5d0-ffffffff8123a5e8: bpf_cgroup_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81275135)
Location: kernel/bpf/cgroup.c:843
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
```
**Symbols:**

```
ffffffff81275060-ffffffff81275107: bpf_cgroup_link_release.part.0 (STB_LOCAL)
ffffffff81275110-ffffffff81275128: bpf_cgroup_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c3b40)
Location: kernel/bpf/cgroup.c:968
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
```
**Symbols:**

```
ffffffff812c3b40-ffffffff812c3c37: bpf_cgroup_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813285f0)
Location: kernel/bpf/cgroup.c:1180
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
```
**Symbols:**

```
ffffffff813285f0-ffffffff813286f8: bpf_cgroup_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81358950)
Location: kernel/bpf/cgroup.c:1180
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
```
**Symbols:**

```
ffffffff81358950-ffffffff81358a58: bpf_cgroup_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813814d0)
Location: kernel/bpf/cgroup.c:1181
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_detach
```
**Symbols:**

```
ffffffff813814d0-ffffffff813815d8: bpf_cgroup_link_release (STB_LOCAL)
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
