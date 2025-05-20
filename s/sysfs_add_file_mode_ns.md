# Function: <code>sysfs_add_file_mode_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8128c8b0)
Location: fs/sysfs/file.c:240
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8128c8b0-ffffffff8128ca2f: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812b9f40)
Location: fs/sysfs/file.c:246
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812b9f40-ffffffff812ba0bf: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812cf670)
Location: fs/sysfs/file.c:246
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812cf670-ffffffff812cf7ef: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812dcd90)
Location: fs/sysfs/file.c:248
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812dcd90-ffffffff812dcf05: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813016c0)
Location: fs/sysfs/file.c:248
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813016c0-ffffffff81301835: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8132f400)
Location: fs/sysfs/file.c:246
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8132f400-ffffffff8132f583: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813467a0)
Location: fs/sysfs/file.c:246
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813467a0-ffffffff81346923: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136eab0)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136eab0-ffffffff8136ec2d: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81386dc0)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81386dc0-ffffffff81386f3d: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d1aa0)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff813d1aa0-ffffffff813d1c15: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e3800)
Location: fs/sysfs/file.c:246
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff813e3800-ffffffff813e3975: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813ea420)
Location: fs/sysfs/file.c:257
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff813ea420-ffffffff813ea58c: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143c1a0)
Location: fs/sysfs/file.c:257
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff8143c1a0-ffffffff8143c30c: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b7680)
Location: fs/sysfs/file.c:254
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff814b7680-ffffffff814b77c7: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154eae0)
Location: fs/sysfs/file.c:254
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff8154eae0-ffffffff8154ec27: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815867b0)
Location: fs/sysfs/file.c:254
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff815867b0-ffffffff815868f7: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bf310)
Location: fs/sysfs/file.c:267
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
```
**Symbols:**

```
ffffffff815bf310-ffffffff815bf457: sysfs_add_file_mode_ns (STB_GLOBAL)
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
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff800010456ab8)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffff800010456ab8-ffff800010456c6c: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618a98)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c0618a98-c0618c4c: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000570bb0)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c000000000570bb0-c000000000570df4: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e81bc)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffe0002e81bc-ffffffe0002e8314: sysfs_add_file_mode_ns (STB_GLOBAL)
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
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f3a0)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137f3a0-ffffffff8137f51d: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136fe30)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136fe30-ffffffff8136ffad: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137ce70)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137ce70-ffffffff8137cfed: sysfs_add_file_mode_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_add_file_mode_ns(struct kernfs_node *parent, const struct attribute *attr, bool is_bin, umode_t mode, kuid_t uid, kgid_t gid, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81390950)
Location: fs/sysfs/file.c:245
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81390950-ffffffff81390acd: sysfs_add_file_mode_ns (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>kuid_t uid</code>
</li>
<li>
<b>Param added. </b>
<code>kgid_t gid</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, attr, is_bin, mode, ns</code> ➡️ <code>parent, attr, is_bin, mode, uid, gid, ns</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_bin</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, attr, is_bin, mode, uid, gid, ns</code> ➡️ <code>parent, attr, mode, uid, gid, ns</code>
</li>
</ul>
</details>
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
