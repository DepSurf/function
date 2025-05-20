# Function: <code>kernfs_destroy_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128acc0)
Location: fs/kernfs/dir.c:902
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8128acc0-ffffffff8128acd3: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b81e0)
Location: fs/kernfs/dir.c:950
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812b81e0-ffffffff812b81f3: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd980)
Location: fs/kernfs/dir.c:900
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812cd980-ffffffff812cd993: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812daf80)
Location: fs/kernfs/dir.c:910
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812daf80-ffffffff812daf93: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff870)
Location: fs/kernfs/dir.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff812ff870-ffffffff812ff883: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d520)
Location: fs/kernfs/dir.c:995
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8132d520-ffffffff8132d533: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813448c0)
Location: fs/kernfs/dir.c:995
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff813448c0-ffffffff813448d3: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136cae0)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8136cae0-ffffffff8136caf3: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384c90)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff81384c90-ffffffff81384ca3: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf250)
Location: fs/kernfs/dir.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff813cf250-ffffffff813cf29d: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0e80)
Location: fs/kernfs/dir.c:999
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff813e0e80-ffffffff813e0ecd: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7ab0)
Location: fs/kernfs/dir.c:999
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff813e7ab0-ffffffff813e7afd: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814397d0)
Location: fs/kernfs/dir.c:958
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff814397d0-ffffffff8143981d: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4e30)
Location: fs/kernfs/dir.c:969
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff814b4e30-ffffffff814b4e7a: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154be40)
Location: fs/kernfs/dir.c:989
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8154be40-ffffffff8154be8a: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583b00)
Location: fs/kernfs/dir.c:993
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff81583b00-ffffffff81583b4a: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc5e0)
Location: fs/kernfs/dir.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff815bc5e0-ffffffff815bc62a: kernfs_destroy_root (STB_GLOBAL)
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
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453be8)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffff800010453be8-ffff800010453c14: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0616708)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
c0616708-c0616728: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056d190)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
c00000000056d190-c00000000056d1a8: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e6122)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffe0002e6122-ffffffe0002e614c: kernfs_destroy_root (STB_GLOBAL)
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
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d270)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8137d270-ffffffff8137d283: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136dd30)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8136dd30-ffffffff8136dd43: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137ad40)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8137ad40-ffffffff8137ad53: kernfs_destroy_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernfs_destroy_root(struct kernfs_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e840)
Location: fs/kernfs/dir.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_exit
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - fs/sysfs/mount.c:sysfs_init
```
**Symbols:**

```
ffffffff8138e840-ffffffff8138e853: kernfs_destroy_root (STB_GLOBAL)
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
