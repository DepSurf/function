# Function: <code>kernfs_generic_poll</code>

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
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8136e0b0)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff8136e0b0-ffffffff8136e115: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81386270)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff81386270-ffffffff813862d5: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813d0e70)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff813d0e70-ffffffff813d0ed5: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e2a80)
Location: fs/kernfs/file.c:815
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff813e2a80-ffffffff813e2ae5: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e9690)
Location: fs/kernfs/file.c:815
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff813e9690-ffffffff813e96f5: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8143b400)
Location: fs/kernfs/file.c:815
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff8143b400-ffffffff8143b465: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff814b6690)
Location: fs/kernfs/file.c:815
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff814b6690-ffffffff814b66fe: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154d758)
Location: fs/kernfs/file.c:876
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
```
**Symbols:**

```
ffffffff8154da00-ffffffff8154da5e: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815853fb)
Location: fs/kernfs/file.c:876
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
Direct callers:
  - kernel/sched/build_utility.c:psi_trigger_poll
  - kernel/cgroup/cgroup.c:cgroup_file_poll
```
**Symbols:**

```
ffffffff815856c0-ffffffff8158571e: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815bdeab)
Location: fs/kernfs/file.c:827
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
Direct callers:
  - kernel/sched/build_utility.c:psi_trigger_poll
  - kernel/cgroup/cgroup.c:cgroup_file_poll
```
**Symbols:**

```
ffffffff815be170-ffffffff815be1ce: kernfs_generic_poll (STB_GLOBAL)
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
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffff800010455b80)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffff800010455b80-ffff800010455c00: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (c0617e04)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
c0617e04-c0617e88: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (c00000000056f790)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
c00000000056f790-c00000000056f834: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffe0002e7680)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffe0002e7680-ffffffe0002e76e2: kernfs_generic_poll (STB_GLOBAL)
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
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8137e850)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff8137e850-ffffffff8137e8b5: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8136f2e0)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff8136f2e0-ffffffff8136f345: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8137c320)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff8137c320-ffffffff8137c385: kernfs_generic_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file *of, poll_table *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8138fe00)
Location: fs/kernfs/file.c:834
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - fs/kernfs/file.c:kernfs_fop_poll
```
**Symbols:**

```
ffffffff8138fe00-ffffffff8138fe65: kernfs_generic_poll (STB_GLOBAL)
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
