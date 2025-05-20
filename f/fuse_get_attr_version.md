# Function: <code>fuse_get_attr_version</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 fuse_get_attr_version(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81312de0)
Location: fs/fuse/dir.c:163
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81312de0-ffffffff81312e09: fuse_get_attr_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 fuse_get_attr_version(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81347360)
Location: fs/fuse/dir.c:165
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81347360-ffffffff81347389: fuse_get_attr_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 fuse_get_attr_version(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135cc70)
Location: fs/fuse/dir.c:157
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8135cc70-ffffffff8135cc99: fuse_get_attr_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 fuse_get_attr_version(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81371660)
Location: fs/fuse/dir.c:157
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81371660-ffffffff81371689: fuse_get_attr_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 fuse_get_attr_version(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81396360)
Location: fs/fuse/dir.c:157
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81396360-ffffffff81396389: fuse_get_attr_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_attr_version(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c5e39)
Location: fs/fuse/dir.c:157
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff813c64e0-ffffffff813c6509: fuse_get_attr_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_attr_version(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813de438)
Location: fs/fuse/dir.c:152
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813df6b0-ffffffff813df6d9: fuse_get_attr_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814099a8)
Location: fs/fuse/fuse_i.h:789
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8140e5a1)
Location: fs/fuse/fuse_i.h:789
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff81416476)
Location: fs/fuse/fuse_i.h:789
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814240b8)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814273b7)
Location: fs/fuse/fuse_i.h:784
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81430394)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814735f8)
Location: fs/fuse/fuse_i.h:785
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81477d5e)
Location: fs/fuse/fuse_i.h:785
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff814808a4)
Location: fs/fuse/fuse_i.h:785
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148e008)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81492602)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8149bf8a)
Location: fs/fuse/fuse_i.h:859
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81493908)
Location: fs/fuse/fuse_i.h:868
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814976e6)
Location: fs/fuse/fuse_i.h:868
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff814a10a1)
Location: fs/fuse/fuse_i.h:868
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ead68)
Location: fs/fuse/fuse_i.h:873
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814ef246)
Location: fs/fuse/fuse_i.h:873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff814f9151)
Location: fs/fuse/fuse_i.h:873
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff815798ac)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8157efce)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff81588bf4)
Location: fs/fuse/fuse_i.h:894
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8161ef4c)
Location: fs/fuse/fuse_i.h:897
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81624c8f)
Location: fs/fuse/fuse_i.h:897
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8162f0e4)
Location: fs/fuse/fuse_i.h:897
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8165736c)
Location: fs/fuse/fuse_i.h:902
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8165d02d)
Location: fs/fuse/fuse_i.h:902
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff81667347)
Location: fs/fuse/fuse_i.h:902
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81690fbc)
Location: fs/fuse/fuse_i.h:929
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81696d8a)
Location: fs/fuse/fuse_i.h:929
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff816a1697)
Location: fs/fuse/fuse_i.h:929
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010507860)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffff80001050be10)
Location: fs/fuse/fuse_i.h:784
Inline: True
```
```
In fs/fuse/readdir.c (ffff800010514ed8)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c3724)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (c06c70c8)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (c06cfc14)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064ceb8)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (c000000000651990)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (c00000000065d678)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe0003736b4)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffe00037663e)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffe00037e5cc)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141c698)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8141f997)
Location: fs/fuse/fuse_i.h:784
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81428974)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140d118)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81410417)
Location: fs/fuse/fuse_i.h:784
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff814193f4)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81418838)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8141bb37)
Location: fs/fuse/fuse_i.h:784
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81424b14)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142f5a8)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81432aeb)
Location: fs/fuse/fuse_i.h:784
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff8143b9a4)
Location: fs/fuse/fuse_i.h:784
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
</ul>
