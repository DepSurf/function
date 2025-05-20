# Function: <code>iattr_to_fattr</code>

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
In fs/fuse/dir.c (ffffffff813148dc)
Location: fs/fuse/dir.c:1458
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
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
In fs/fuse/dir.c (ffffffff81348f39)
Location: fs/fuse/dir.c:1465
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
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
In fs/fuse/dir.c (ffffffff8135e751)
Location: fs/fuse/dir.c:1481
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81373263)
Location: fs/fuse/dir.c:1481
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81397f73)
Location: fs/fuse/dir.c:1478
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c7231)
Location: fs/fuse/dir.c:1488
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813e0666)
Location: fs/fuse/dir.c:1317
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140c04e)
Location: fs/fuse/dir.c:1304
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81425bb0)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814723a0)
Location: fs/fuse/dir.c:1360
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff814723a0-ffffffff81472515: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148cb90)
Location: fs/fuse/dir.c:1463
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff8148cb90-ffffffff8148cd05: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814923f0)
Location: fs/fuse/dir.c:1482
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff814923f0-ffffffff81492565: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814e9f70)
Location: fs/fuse/dir.c:1430
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff814e9f70-ffffffff814ea0e5: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81578890)
Location: fs/fuse/dir.c:1510
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81578890-ffffffff81578a12: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8161de40)
Location: fs/fuse/dir.c:1543
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff8161de40-ffffffff8161dfc2: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81655f70)
Location: fs/fuse/dir.c:1609
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81655f70-ffffffff816560f2: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iattr_to_fattr(struct fuse_conn *fc, struct iattr *iattr, struct fuse_setattr_in *arg, bool trust_local_cmtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8168f7f0)
Location: fs/fuse/dir.c:1710
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff8168f7f0-ffffffff8168f972: iattr_to_fattr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff8000105093c8)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c52c8)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064f15c)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000374e8c)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141e190)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140ec10)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141a330)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81431090)
Location: fs/fuse/dir.c:1360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
