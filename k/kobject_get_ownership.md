# Function: <code>kobject_get_ownership</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d04e9)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff819d0ee0-ffffffff819d0f05: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a09a49)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81a0a440-ffffffff81a0a465: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a793c9)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81a79da0-ffffffff81a79dc5: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0729)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81ab1100-ffffffff81ab1125: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eab19)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff815eb640-ffffffff815eb665: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f439)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8160ff60-ffffffff8160ff85: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2b79)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff815f36a0-ffffffff815f36c5: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165fd59)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81660870-ffffffff81660895: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779939)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8177a380-ffffffff8177a3bd: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(const struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820228f9)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff82023480-ffffffff820234bd: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(const struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2969)
Location: lib/kobject.c:50
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff820a34f0-ffffffff820a352d: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(const struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217a9e9)
Location: lib/kobject.c:50
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8217b570-ffffffff8217b5ad: kobject_get_ownership (STB_GLOBAL)
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
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8a488)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffff800010d8b498-ffff800010d8b4c4: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e84d30)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c0e857b8-c0e857e8: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecb554)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c000000000ecc7a0-c000000000ecc7f0: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b3afa)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffe0008b453e-ffffffe0008b4560: kobject_get_ownership (STB_GLOBAL)
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
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4f579)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81a4ff50-ffffffff81a4ff75: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0c679)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81a0d050-ffffffff81a0d075: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abb969)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81abc340-ffffffff81abc365: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kobject_get_ownership(struct kobject *kobj, kuid_t *uid, kgid_t *gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac7de9)
Location: lib/kobject.c:48
Inline: True
Inline callers:
  - lib/kobject.c:kset_get_ownership
Direct callers:
  - fs/sysfs/file.c:sysfs_create_bin_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_create_file_ns
  - fs/sysfs/dir.c:sysfs_create_dir_ns
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81ac87c0-ffffffff81ac87e5: kobject_get_ownership (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject *kobj</code> ➡️ <code>const struct kobject *kobj</code>
</li>
</ul>
</details>
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
