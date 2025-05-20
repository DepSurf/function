# Function: <code>process_init_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8131b620)
Location: fs/fuse/inode.c:867
Inline: False
```
**Symbols:**

```
ffffffff8131b620-ffffffff8131b958: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813501c0)
Location: fs/fuse/inode.c:873
Inline: False
```
**Symbols:**

```
ffffffff813501c0-ffffffff81350507: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81365af0)
Location: fs/fuse/inode.c:874
Inline: False
```
**Symbols:**

```
ffffffff81365af0-ffffffff81365e6d: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8137a190)
Location: fs/fuse/inode.c:867
Inline: False
```
**Symbols:**

```
ffffffff8137a190-ffffffff8137a52b: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8139f030)
Location: fs/fuse/inode.c:867
Inline: False
```
**Symbols:**

```
ffffffff8139f030-ffffffff8139f3cb: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813ce340)
Location: fs/fuse/inode.c:870
Inline: False
```
**Symbols:**

```
ffffffff813ce340-ffffffff813ce6fb: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e7630)
Location: fs/fuse/inode.c:875
Inline: False
```
**Symbols:**

```
ffffffff813e7630-ffffffff813e7a3e: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814135a0)
Location: fs/fuse/inode.c:873
Inline: False
```
**Symbols:**

```
ffffffff814135a0-ffffffff814139fa: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142caf0)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8142caf0-ffffffff8142cf4c: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147d20a)
Location: fs/fuse/inode.c:898
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8147d6f0-ffffffff8147db3e: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_mount *fm, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81498409)
Location: fs/fuse/inode.c:974
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81498970-ffffffff81498ea2: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_mount *fm, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149d639)
Location: fs/fuse/inode.c:1014
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8149db30-ffffffff8149e070: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_mount *fm, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f50e9)
Location: fs/fuse/inode.c:1066
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff814f5660-ffffffff814f5ba0: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_mount *fm, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8158501b)
Location: fs/fuse/inode.c:1108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81585740-ffffffff81585c53: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_mount *fm, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162b1cb)
Location: fs/fuse/inode.c:1121
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8162b960-ffffffff8162be64: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_mount *fm, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff816633f5)
Location: fs/fuse/inode.c:1121
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81663b90-ffffffff816640ab: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void process_init_reply(struct fuse_mount *fm, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169d574)
Location: fs/fuse/inode.c:1198
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff8169dcf0-ffffffff8169e219: process_init_reply (STB_LOCAL)
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
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010511be8)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffff800010511be8-ffff800010512018: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cc224)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
c06cc224-c06cc638: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c000000000658540)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
c000000000658540-c000000000658a6c: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037b1f4)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffe00037b1f4-ffffffe00037b626: process_init_reply (STB_LOCAL)
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
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814250d0)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff814250d0-ffffffff8142552c: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81415b50)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81415b50-ffffffff81415fac: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81421270)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff81421270-ffffffff814216cc: process_init_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void process_init_reply(struct fuse_conn *fc, struct fuse_args *args, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814380f0)
Location: fs/fuse/inode.c:884
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_send_init
```
**Symbols:**

```
ffffffff814380f0-ffffffff8143854a: process_init_reply (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_args *args</code>
</li>
<li>
<b>Param added. </b>
<code>int error</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_req *req</code>
</li>
</ul>
</details>
</li>
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
