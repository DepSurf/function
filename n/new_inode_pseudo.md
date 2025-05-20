# Function: <code>new_inode_pseudo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81228fd0)
Location: fs/inode.c:876
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:ns_get_path
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81228fd0-ffffffff8122902a: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812516d0)
Location: fs/inode.c:885
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:ns_get_path
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812516d0-ffffffff8125172a: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812647d0)
Location: fs/inode.c:887
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812647d0-ffffffff8126482a: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81272000)
Location: fs/inode.c:888
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81272000-ffffffff8127205a: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81294920)
Location: fs/inode.c:888
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81294920-ffffffff8129497a: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812baa20)
Location: fs/inode.c:893
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812baa20-ffffffff812baa7a: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cfd60)
Location: fs/inode.c:901
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812cfd60-ffffffff812cfdba: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eccb0)
Location: fs/inode.c:914
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812eccb0-ffffffff812ecd10: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fe840)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812fe840-ffffffff812fe8a0: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335ef5)
Location: fs/inode.c:926
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:get_pipe_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81337910-ffffffff81337970: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341885)
Location: fs/inode.c:925
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:get_pipe_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81343250-ffffffff813432b0: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347d15)
Location: fs/inode.c:932
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81349510-ffffffff81349570: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395925)
Location: fs/inode.c:936
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81397260-ffffffff813972c0: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417e53)
Location: fs/inode.c:1017
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81419380-ffffffff814193de: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a3623)
Location: fs/inode.c:1016
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff814a4db0-ffffffff814a4df9: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d8785)
Location: fs/inode.c:1018
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff814d9f40-ffffffff814d9f89: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150b015)
Location: fs/inode.c:1003
Inline: True
Inline callers:
  - fs/inode.c:new_inode
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff8150c6c0-ffffffff8150c709: new_inode_pseudo (STB_GLOBAL)
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
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103af6a8)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffff8000103af6a8-ffff8000103af748: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058f474)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:__ns_get_path
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
c058f474-c058f4d0: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004ab1f0)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
c0000000004ab1f0-c0000000004ab28c: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000274156)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffe000274156-ffffffe0002741e2: new_inode_pseudo (STB_GLOBAL)
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
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6e20)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812f6e20-ffffffff812f6e80: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e7a40)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812e7a40-ffffffff812e7aa0: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4c30)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff812f4c30-ffffffff812f4c90: new_inode_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *new_inode_pseudo(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305dc0)
Location: fs/inode.c:925
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:new_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - net/socket.c:sock_alloc
```
**Symbols:**

```
ffffffff81305dc0-ffffffff81305e1e: new_inode_pseudo (STB_GLOBAL)
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
