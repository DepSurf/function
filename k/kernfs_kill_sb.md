# Function: <code>kernfs_kill_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81288910)
Location: fs/kernfs/mount.c:266
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff81288910-ffffffff81288992: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812b5dd0)
Location: fs/kernfs/mount.c:282
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff812b5dd0-ffffffff812b5e52: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812cb660)
Location: fs/kernfs/mount.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff812cb660-ffffffff812cb6e2: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812d8ac0)
Location: fs/kernfs/mount.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff812d8ac0-ffffffff812d8b3e: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fd330)
Location: fs/kernfs/mount.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff812fd330-ffffffff812fd39a: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132af70)
Location: fs/kernfs/mount.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff8132af70-ffffffff8132afda: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813422e0)
Location: fs/kernfs/mount.c:364
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff813422e0-ffffffff8134234a: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136a6c0)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff8136a6c0-ffffffff8136a72e: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813828a0)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff813828a0-ffffffff8138290e: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813ccfc0)
Location: fs/kernfs/mount.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff813ccfc0-ffffffff813cd02e: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813dec10)
Location: fs/kernfs/mount.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff813dec10-ffffffff813dec7e: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813e5930)
Location: fs/kernfs/mount.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff813e5930-ffffffff813e599e: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81437500)
Location: fs/kernfs/mount.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff81437500-ffffffff8143756e: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff814b2160)
Location: fs/kernfs/mount.c:373
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff814b2160-ffffffff814b21d6: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81548cd0)
Location: fs/kernfs/mount.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff81548cd0-ffffffff81548d46: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815808a0)
Location: fs/kernfs/mount.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff815808a0-ffffffff81580919: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815b9330)
Location: fs/kernfs/mount.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff815b9330-ffffffff815b93a9: kernfs_kill_sb (STB_GLOBAL)
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
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffff800010450d50)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffff800010450d50-ffff800010450dc8: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c0613d24)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
c0613d24-c0613d8c: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c000000000569110)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
c000000000569110-c0000000005691cc: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffe0002e3c6e)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffe0002e3c6e-ffffffe0002e3cde: kernfs_kill_sb (STB_GLOBAL)
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
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8137ae80)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff8137ae80-ffffffff8137aeee: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136b950)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff8136b950-ffffffff8136b9be: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81378950)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff81378950-ffffffff813789be: kernfs_kill_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernfs_kill_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8138c400)
Location: fs/kernfs/mount.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - fs/sysfs/mount.c:sysfs_kill_sb
```
**Symbols:**

```
ffffffff8138c400-ffffffff8138c46e: kernfs_kill_sb (STB_GLOBAL)
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
