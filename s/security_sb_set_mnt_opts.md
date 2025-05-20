# Function: <code>security_sb_set_mnt_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b3f0)
Location: security/security.c:321
Inline: False
```
**Symbols:**

```
ffffffff8133b3f0-ffffffff8133b455: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370960)
Location: security/security.c:322
Inline: False
```
**Symbols:**

```
ffffffff81370960-ffffffff813709c9: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387170)
Location: security/security.c:322
Inline: False
```
**Symbols:**

```
ffffffff81387170-ffffffff813871d9: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139be40)
Location: security/security.c:899
Inline: False
```
**Symbols:**

```
ffffffff8139be40-ffffffff8139bea7: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c1530)
Location: security/security.c:847
Inline: False
```
**Symbols:**

```
ffffffff813c1530-ffffffff813c159d: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2480)
Location: security/security.c:415
Inline: False
```
**Symbols:**

```
ffffffff813f2480-ffffffff813f24e3: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140d910)
Location: security/security.c:908
Inline: False
Direct callers:
  - fs/super.c:mount_fs
```
**Symbols:**

```
ffffffff8140d910-ffffffff8140d971: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143aaf0)
Location: security/security.c:917
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff8143aaf0-ffffffff8143ab53: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454910)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff81454910-ffffffff81454971: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a72a0)
Location: security/security.c:1099
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff814a72a0-ffffffff814a7301: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c4820)
Location: security/security.c:1101
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff814c4820-ffffffff814c4881: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cad10)
Location: security/security.c:1146
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff814cad10-ffffffff814cad71: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81523a10)
Location: security/security.c:1146
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff81523a10-ffffffff81523a71: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b7770)
Location: security/security.c:1158
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff815b7770-ffffffff815b77df: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81662ae0)
Location: security/security.c:1156
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff81662ae0-ffffffff81662b4f: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169afe0)
Location: security/security.c:1553
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff8169afe0-ffffffff8169b04f: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d7a50)
Location: security/security.c:1606
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff816d7a50-ffffffff816d7abf: security_sb_set_mnt_opts (STB_GLOBAL)
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
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff80001053fac0)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffff80001053fac0-ffff80001053fb40: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f5ba4)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
c06f5ba4-c06f5c18: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000690c70)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
c000000000690c70-c000000000690d3c: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ceac)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffe00039ceac-ffffffe00039cf0a: security_sb_set_mnt_opts (STB_GLOBAL)
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
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cef0)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff8144cef0-ffffffff8144cf51: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d940)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff8143d940-ffffffff8143d9a1: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81448f90)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff81448f90-ffffffff81448ff1: security_sb_set_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sb_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81460360)
Location: security/security.c:951
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
```
**Symbols:**

```
ffffffff81460360-ffffffff814603c1: security_sb_set_mnt_opts (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *mnt_opts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct security_mnt_opts *opts</code>
</li>
</ul>
</details>
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
