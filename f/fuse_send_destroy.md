# Function: <code>fuse_send_destroy</code>

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
In fs/fuse/inode.c (ffffffff8131b543)
Location: fs/fuse/inode.c:364
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
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
In fs/fuse/inode.c (ffffffff81350013)
Location: fs/fuse/inode.c:374
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
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
In fs/fuse/inode.c (ffffffff81365943)
Location: fs/fuse/inode.c:377
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
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
In fs/fuse/inode.c (ffffffff8137a073)
Location: fs/fuse/inode.c:377
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
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
In fs/fuse/inode.c (ffffffff8139ef13)
Location: fs/fuse/inode.c:377
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_put_super
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
In fs/fuse/inode.c (ffffffff813cd9f8)
Location: fs/fuse/inode.c:383
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
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
In fs/fuse/inode.c (ffffffff813e6de8)
Location: fs/fuse/inode.c:382
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
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
In fs/fuse/inode.c (ffffffff81412e18)
Location: fs/fuse/inode.c:380
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142d5d0)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffff8142d5d0-ffffffff8142d633: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147c860)
Location: fs/fuse/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff8147c860-ffffffff8147c8c3: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81497880)
Location: fs/fuse/inode.c:449
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_conn_destroy
```
**Symbols:**

```
ffffffff81497880-ffffffff814978e6: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149cab0)
Location: fs/fuse/inode.c:449
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_conn_destroy
```
**Symbols:**

```
ffffffff8149cab0-ffffffff8149cb16: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f45a0)
Location: fs/fuse/inode.c:451
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_conn_destroy
```
**Symbols:**

```
ffffffff814f45a0-ffffffff814f4606: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81584150)
Location: fs/fuse/inode.c:489
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_conn_destroy
```
**Symbols:**

```
ffffffff81584150-ffffffff815841c4: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162a1e0)
Location: fs/fuse/inode.c:502
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_conn_destroy
```
**Symbols:**

```
ffffffff8162a1e0-ffffffff8162a254: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff816623f0)
Location: fs/fuse/inode.c:502
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_conn_destroy
```
**Symbols:**

```
ffffffff816623f0-ffffffff81662467: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_mount *fm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169c300)
Location: fs/fuse/inode.c:571
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_conn_destroy
```
**Symbols:**

```
ffffffff8169c300-ffffffff8169c377: fuse_send_destroy (STB_LOCAL)
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
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff8000105113c0)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffff8000105113c0-ffff800010511450: fuse_send_destroy (STB_LOCAL)
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
In fs/fuse/inode.c (c06cce8c)
Location: fs/fuse/inode.c:373
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c0000000006592f0)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
c0000000006592f0-c0000000006593a8: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037bb8a)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffe00037bb8a-ffffffe00037bc10: fuse_send_destroy (STB_LOCAL)
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
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81425bb0)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffff81425bb0-ffffffff81425c13: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81416630)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffff81416630-ffffffff81416693: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81421d50)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffff81421d50-ffffffff81421db3: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_send_destroy(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81438bd0)
Location: fs/fuse/inode.c:373
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_sb_destroy
```
**Symbols:**

```
ffffffff81438bd0-ffffffff81438c33: fuse_send_destroy (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_mount *fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn *fc</code>
</li>
</ul>
</details>
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
