# Function: <code>cgroup_root_from_kf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811143d5)
Location: kernel/cgroup.c:1093
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_show_options
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111c302)
Location: kernel/cgroup.c:1138
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_path
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124632)
Location: kernel/cgroup.c:1141
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_remount
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_path
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81123452)
Location: kernel/cgroup/cgroup.c:1034
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81124380-ffffffff81124399: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112f1a2)
Location: kernel/cgroup/cgroup.c:1203
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff811304e0-ffffffff811304f9: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113d512)
Location: kernel/cgroup/cgroup.c:1206
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff8113ebb0-ffffffff8113ebc9: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149042)
Location: kernel/cgroup/cgroup.c:1241
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff8114a5c0-ffffffff8114a5d9: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154494)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81155ce0-ffffffff81155cf9: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811600c4)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81161940-ffffffff81161959: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170844)
Location: kernel/cgroup/cgroup.c:1274
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81172f20-ffffffff81172f39: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116d354)
Location: kernel/cgroup/cgroup.c:1271
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff8116fbe0-ffffffff8116fbf9: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116dfd4)
Location: kernel/cgroup/cgroup.c:1271
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81170810-ffffffff81170829: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81193fb4)
Location: kernel/cgroup/cgroup.c:1302
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81196d40-ffffffff81196d59: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c4857)
Location: kernel/cgroup/cgroup.c:1305
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff811c6cf0-ffffffff811c6d11: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81206f47)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81209800-ffffffff81209821: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121c957)
Location: kernel/cgroup/cgroup.c:1294
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff8121ef50-ffffffff8121ef71: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812344e7)
Location: kernel/cgroup/cgroup.c:1274
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81236be0-ffffffff81236c01: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d1950)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffff8000101d2be0-ffff8000101d2c10: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04146b0)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
c0415a4c-c0415a70: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023bf04)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
c00000000023dae0-c00000000023daf8: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014ac3a)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffe00014c448-ffffffe00014c470: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811586e4)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81159f60-ffffffff81159f79: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ba04)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff8114d250-ffffffff8114d269: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811564b4)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81157d30-ffffffff81157d49: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_root *cgroup_root_from_kf(struct kernfs_root *kf_root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81163bc4)
Location: kernel/cgroup/cgroup.c:1282
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_show_path
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
**Symbols:**

```
ffffffff81164d80-ffffffff81164d99: cgroup_root_from_kf (STB_GLOBAL)
```
</details>
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
