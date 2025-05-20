# Function: <code>kernfs_root_from_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81288580)
Location: fs/kernfs/mount.c:59
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kill_sb
```
**Symbols:**

```
ffffffff81288580-ffffffff812885a2: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812b5a20)
Location: fs/kernfs/mount.c:74
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kill_sb
```
**Symbols:**

```
ffffffff812b5a20-ffffffff812b5a42: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812cb2b0)
Location: fs/kernfs/mount.c:74
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_kill_sb
```
**Symbols:**

```
ffffffff812cb2b0-ffffffff812cb2d2: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812d8720)
Location: fs/kernfs/mount.c:74
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
**Symbols:**

```
ffffffff812d8720-ffffffff812d8744: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff812fcfa0)
Location: fs/kernfs/mount.c:147
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
**Symbols:**

```
ffffffff812fcfa0-ffffffff812fcfc4: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132abb0)
Location: fs/kernfs/mount.c:147
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
**Symbols:**

```
ffffffff8132abb0-ffffffff8132abd4: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81341f00)
Location: fs/kernfs/mount.c:147
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
**Symbols:**

```
ffffffff81341f00-ffffffff81341f24: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136a320)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8136a320-ffffffff8136a344: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81382510)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81382510-ffffffff81382534: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813ccd10)
Location: fs/kernfs/mount.c:158
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff813ccd10-ffffffff813ccd34: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813de960)
Location: fs/kernfs/mount.c:158
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff813de960-ffffffff813de984: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813e55a0)
Location: fs/kernfs/mount.c:158
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff813e55a0-ffffffff813e55c4: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81437170)
Location: fs/kernfs/mount.c:158
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff81437170-ffffffff81437194: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff814b1df0)
Location: fs/kernfs/mount.c:158
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff814b1df0-ffffffff814b1e20: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81548910)
Location: fs/kernfs/mount.c:159
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
**Symbols:**

```
ffffffff81548910-ffffffff81548940: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815804c0)
Location: fs/kernfs/mount.c:159
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
**Symbols:**

```
ffffffff815804c0-ffffffff815804f0: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815b8f10)
Location: fs/kernfs/mount.c:166
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
**Symbols:**

```
ffffffff815b8f10-ffffffff815b8f40: kernfs_root_from_sb (STB_GLOBAL)
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
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffff800010450948)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffff800010450948-ffff800010450998: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c0613918)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
c0613918-c061394c: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (c000000000568b80)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
c000000000568b80-c000000000568bbc: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffe0002e38d6)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffe0002e38d6-ffffffe0002e390c: kernfs_root_from_sb (STB_GLOBAL)
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
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8137aaf0)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8137aaf0-ffffffff8137ab14: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8136b5c0)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8136b5c0-ffffffff8136b5e4: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813785c0)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff813785c0-ffffffff813785e4: kernfs_root_from_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_root *kernfs_root_from_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8138c070)
Location: fs/kernfs/mount.c:135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
```
**Symbols:**

```
ffffffff8138c070-ffffffff8138c094: kernfs_root_from_sb (STB_GLOBAL)
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
