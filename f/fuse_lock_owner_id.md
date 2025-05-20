# Function: <code>fuse_lock_owner_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81317710)
Location: fs/fuse/file.c:314
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_getlk
```
**Symbols:**

```
ffffffff81317710-ffffffff8131778a: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134c030)
Location: fs/fuse/file.c:314
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8134c030-ffffffff8134c0a8: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81361940)
Location: fs/fuse/file.c:315
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81361940-ffffffff813619b8: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81376320)
Location: fs/fuse/file.c:310
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81376320-ffffffff81376398: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139b0c0)
Location: fs/fuse/file.c:310
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8139b0c0-ffffffff8139b138: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813ca000)
Location: fs/fuse/file.c:310
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_send_read
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff813ca000-ffffffff813ca078: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e3650)
Location: fs/fuse/file.c:314
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff813e3650-ffffffff813e36c8: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140f400)
Location: fs/fuse/file.c:320
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8140f400-ffffffff8140f472: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81429000)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81429000-ffffffff81429072: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81479060)
Location: fs/fuse/file.c:341
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81479060-ffffffff814790d2: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81493d90)
Location: fs/fuse/file.c:364
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81493d90-ffffffff81493e02: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81498d20)
Location: fs/fuse/file.c:368
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff81498d20-ffffffff81498d95: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f07b0)
Location: fs/fuse/file.c:371
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff814f07b0-ffffffff814f0825: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157ffe0)
Location: fs/fuse/file.c:377
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff8157ffe0-ffffffff81580067: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81625d40)
Location: fs/fuse/file.c:377
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff81625d40-ffffffff81625dc7: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165e130)
Location: fs/fuse/file.c:378
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff8165e130-ffffffff8165e1b7: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81697e70)
Location: fs/fuse/file.c:379
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff81697e70-ffffffff81697ef7: fuse_lock_owner_id (STB_GLOBAL)
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
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050d028)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffff80001050d028-ffff80001050d0c4: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c86b4)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_lk_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
c06c86b4-c06c8740: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000653b40)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
c000000000653b40-c000000000653bd0: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000377ee2)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffe000377ee2-ffffffe000377f78: fuse_lock_owner_id (STB_GLOBAL)
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
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814215e0)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff814215e0-ffffffff81421652: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81412060)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81412060-ffffffff814120d2: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141d780)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8141d780-ffffffff8141d7f2: fuse_lock_owner_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn *fc, fl_owner_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814344e0)
Location: fs/fuse/file.c:340
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff814344e0-ffffffff81434552: fuse_lock_owner_id (STB_GLOBAL)
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
