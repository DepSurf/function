# Function: <code>hugetlb_cgroup_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81200e60)
Location: mm/hugetlb_cgroup.c:272
Inline: False
```
**Symbols:**

```
ffffffff81200e60-ffffffff81200f42: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812255d0)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff812255d0-ffffffff812256d2: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81237bb0)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff81237bb0-ffffffff81237cb2: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81243820)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff81243820-ffffffff8124391b: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81263670)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff81263670-ffffffff8126376b: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81287960)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff81287960-ffffffff81287a6d: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8129c8b0)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff8129c8b0-ffffffff8129c9bd: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812b7a70)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff812b7a70-ffffffff812b7b7a: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812c9950)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff812c9950-ffffffff812c9a5a: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812ff1f0)
Location: mm/hugetlb_cgroup.c:494
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff812ff1f0-ffffffff812ff32d: hugetlb_cgroup_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff8130b530)
Location: mm/hugetlb_cgroup.c:498
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff8130b530-ffffffff8130b66d: hugetlb_cgroup_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff81311b90)
Location: mm/hugetlb_cgroup.c:498
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff81311b90-ffffffff81311cd1: hugetlb_cgroup_write.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (0)
Location: mm/hugetlb_cgroup.c:498
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff8135d050-ffffffff8135d1f5: hugetlb_cgroup_write.constprop.0 (STB_LOCAL)
ffffffff81cc2c82-ffffffff81cc2cab: hugetlb_cgroup_write.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (0)
Location: mm/hugetlb_cgroup.c:596
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff813d6d50-ffffffff813d6f09: hugetlb_cgroup_write.constprop.0 (STB_LOCAL)
ffffffff81e751f9-ffffffff81e75222: hugetlb_cgroup_write.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (0)
Location: mm/hugetlb_cgroup.c:598
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff8145cba0-ffffffff8145cd4b: hugetlb_cgroup_write.constprop.0 (STB_LOCAL)
ffffffff820682a2-ffffffff820682d0: hugetlb_cgroup_write.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (0)
Location: mm/hugetlb_cgroup.c:594
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff81492920-ffffffff81492ad2: hugetlb_cgroup_write.isra.0 (STB_LOCAL)
ffffffff820e7b87-ffffffff820e7bb5: hugetlb_cgroup_write.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb_cgroup.c (0)
Location: mm/hugetlb_cgroup.c:585
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_dfl
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write_legacy
```
**Symbols:**

```
ffffffff814c2680-ffffffff814c2832: hugetlb_cgroup_write.isra.0 (STB_LOCAL)
ffffffff821c48d1-ffffffff821c48ff: hugetlb_cgroup_write.isra.0.cold (STB_LOCAL)
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
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffff80001036d0a8)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffff80001036d0a8-ffff80001036d1e0: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (c00000000045d060)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
c00000000045d060-c00000000045d1e8: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffe000249e84)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffe000249e84-ffffffe000249f78: hugetlb_cgroup_write (STB_LOCAL)
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
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812c1f30)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff812c1f30-ffffffff812c203a: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812b2f80)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff812b2f80-ffffffff812b308a: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812bfd40)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff812bfd40-ffffffff812bfe4a: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t hugetlb_cgroup_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb_cgroup.c (ffffffff812d0780)
Location: mm/hugetlb_cgroup.c:288
Inline: False
```
**Symbols:**

```
ffffffff812d0780-ffffffff812d088a: hugetlb_cgroup_write (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
