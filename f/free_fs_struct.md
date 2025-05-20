# Function: <code>free_fs_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81241600)
Location: fs/fs_struct.c:86
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:unshare_fs_struct
```
**Symbols:**

```
ffffffff81241600-ffffffff81241631: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81269940)
Location: fs/fs_struct.c:86
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
```
**Symbols:**

```
ffffffff81269940-ffffffff81269971: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8127c8f0)
Location: fs/fs_struct.c:86
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
```
**Symbols:**

```
ffffffff8127c8f0-ffffffff8127c921: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81289fa0)
Location: fs/fs_struct.c:87
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
```
**Symbols:**

```
ffffffff81289fa0-ffffffff81289fd1: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812acae0)
Location: fs/fs_struct.c:87
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
```
**Symbols:**

```
ffffffff812acae0-ffffffff812acb11: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812d46c0)
Location: fs/fs_struct.c:87
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
```
**Symbols:**

```
ffffffff812d46c0-ffffffff812d46f1: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff812e9a90)
Location: fs/fs_struct.c:87
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
```
**Symbols:**

```
ffffffff812e9a90-ffffffff812e9ac1: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81308490)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
```
**Symbols:**

```
ffffffff81308490-ffffffff813084c4: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8131b530)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
ffffffff8131b530-ffffffff8131b564: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813553f8)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:__io_req_aux_free
```
**Symbols:**

```
ffffffff813551e0-ffffffff81355216: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81361d18)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
  - fs/io_uring.c:io_req_clean_work
```
**Symbols:**

```
ffffffff81361b00-ffffffff81361b36: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813687f8)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
```
**Symbols:**

```
ffffffff813685e0-ffffffff81368616: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff813b74f8)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
```
**Symbols:**

```
ffffffff813b72e0-ffffffff813b7316: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff8143cbb5)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
```
**Symbols:**

```
ffffffff8143c980-ffffffff8143c9bc: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff814cb315)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
```
**Symbols:**

```
ffffffff814cb0b0-ffffffff814cb0ec: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81501555)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
```
**Symbols:**

```
ffffffff815012f0-ffffffff8150132c: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff815361a5)
Location: fs/fs_struct.c:88
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:put_nsset
```
**Symbols:**

```
ffffffff81535f40-ffffffff81535f7c: free_fs_struct (STB_GLOBAL)
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
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffff8000103d2a50)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
ffff8000103d2a50-ffff8000103d2a94: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c05ad5fc)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
c05ad5fc-c05ad63c: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (c0000000004d55e0)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
c0000000004d55e0-c0000000004d5648: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffe00028dc9e)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
ffffffe00028dc9e-ffffffe00028dce8: free_fs_struct (STB_GLOBAL)
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
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81313b10)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
ffffffff81313b10-ffffffff81313b44: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81304720)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
ffffffff81304720-ffffffff81304754: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81311900)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
ffffffff81311900-ffffffff81311934: free_fs_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_fs_struct(struct fs_struct *fs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_struct.c (ffffffff81323150)
Location: fs/fs_struct.c:88
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/io_uring.c:io_send_recvmsg
```
**Symbols:**

```
ffffffff81323150-ffffffff81323184: free_fs_struct (STB_GLOBAL)
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
