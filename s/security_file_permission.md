# Function: <code>security_file_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c9e0)
Location: security/security.c:737
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff8133c9e0-ffffffff8133ca99: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372010)
Location: security/security.c:759
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff81372010-ffffffff813720c9: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388940)
Location: security/security.c:780
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff81388940-ffffffff813889f2: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d870)
Location: security/security.c:1385
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff8139d870-ffffffff8139d922: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3150)
Location: security/security.c:1334
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff813c3150-ffffffff813c3208: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3d20)
Location: security/security.c:876
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff813f3d20-ffffffff813f3dcc: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f250)
Location: security/security.c:1397
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff8140f250-ffffffff8140f33c: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c650)
Location: security/security.c:1416
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff8143c650-ffffffff8143c766: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814561d0)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff814561d0-ffffffff814562db: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8dd0)
Location: security/security.c:1626
Inline: True
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff814a8dd0-ffffffff814a8f2b: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c63d0)
Location: security/security.c:1628
Inline: True
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/remap_range.c:remap_verify_area
```
**Symbols:**

```
ffffffff814c63d0-ffffffff814c6522: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cddb0)
Location: security/security.c:1679
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:kernel_read
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff814cddb0-ffffffff814cdf0b: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525760)
Location: security/security.c:1686
Inline: True
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:kernel_read
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81525760-ffffffff815257b5: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bb780)
Location: security/security.c:1692
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:kernel_read
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff815bb780-ffffffff815bb7ee: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667560)
Location: security/security.c:1733
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:kernel_read
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81667560-ffffffff816675ce: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169fb80)
Location: security/security.c:2702
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:kernel_read
  - fs/readdir.c:iterate_dir
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff8169fb80-ffffffff8169fbee: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc480)
Location: security/security.c:2768
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff816dc480-ffffffff816dc4dd: security_file_permission (STB_GLOBAL)
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
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105419c0)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffff8000105419c0-ffff800010541aec: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7990)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
c06f7990-c06f7ac0: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006942a0)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
c0000000006942a0-c000000000694464: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e5e6)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffe00039e5e6-ffffffe00039e6d2: security_file_permission (STB_GLOBAL)
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
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e7b0)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff8144e7b0-ffffffff8144e8bb: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f200)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff8143f200-ffffffff8143f30b: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a850)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff8144a850-ffffffff8144a95b: security_file_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_file_permission(struct file *file, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461c20)
Location: security/security.c:1456
Inline: False
Direct callers:
  - fs/open.c:vfs_fallocate
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/readdir.c:iterate_dir
  - fs/readdir.c:iterate_dir
```
**Symbols:**

```
ffffffff81461c20-ffffffff81461d2b: security_file_permission (STB_GLOBAL)
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
