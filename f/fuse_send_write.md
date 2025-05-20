# Function: <code>fuse_send_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81317c30)
Location: fs/fuse/file.c:948
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81317c30-ffffffff81317d2f: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134c550)
Location: fs/fuse/file.c:961
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8134c550-ffffffff8134c64f: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81361e60)
Location: fs/fuse/file.c:962
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81361e60-ffffffff81361f5f: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81376820)
Location: fs/fuse/file.c:957
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81376820-ffffffff81376923: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139b5c0)
Location: fs/fuse/file.c:960
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8139b5c0-ffffffff8139b6f1: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813ca4f0)
Location: fs/fuse/file.c:961
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813ca4f0-ffffffff813ca65b: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e3b70)
Location: fs/fuse/file.c:966
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813e3b70-ffffffff813e3c93: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t fuse_send_write(struct fuse_req *req, struct fuse_io_priv *io, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140f570)
Location: fs/fuse/file.c:978
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8140f570-ffffffff8140f6af: fuse_send_write (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff8142996e)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_send_write(struct fuse_io_args *ia, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814791c0)
Location: fs/fuse/file.c:1026
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff814791c0-ffffffff814792dc: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_send_write(struct fuse_io_args *ia, loff_t pos, size_t count, fl_owner_t owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81493f00)
Location: fs/fuse/file.c:1049
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff81493f00-ffffffff8149401f: fuse_send_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149954c)
Location: fs/fuse/file.c:1044
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f0da1)
Location: fs/fuse/file.c:1048
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8158065c)
Location: fs/fuse/file.c:1066
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816263ed)
Location: fs/fuse/file.c:1066
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165e7da)
Location: fs/fuse/file.c:1067
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169857c)
Location: fs/fuse/file.c:1068
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffff80001050d8ec)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (c06c9010)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (c000000000654710)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffffffe0003786c8)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffffffff81421f4e)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffffffff814129ce)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffffffff8141e0ee)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffffffff81434e4e)
Location: fs/fuse/file.c:1053
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
