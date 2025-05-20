# Function: <code>pipe_double_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81214c60)
Location: fs/pipe.c:94
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_tee
```
**Symbols:**

```
ffffffff81214c60-ffffffff81214cc4: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123baf0)
Location: fs/pipe.c:95
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
```
**Symbols:**

```
ffffffff8123baf0-ffffffff8123bb60: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124e890)
Location: fs/pipe.c:95
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
```
**Symbols:**

```
ffffffff8124e890-ffffffff8124e900: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125a7c0)
Location: fs/pipe.c:95
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
```
**Symbols:**

```
ffffffff8125a7c0-ffffffff8125a830: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127cb50)
Location: fs/pipe.c:96
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
```
**Symbols:**

```
ffffffff8127cb50-ffffffff8127cbc0: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a3ad0)
Location: fs/pipe.c:91
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812a3ad0-ffffffff812a3b47: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b8c20)
Location: fs/pipe.c:91
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812b8c20-ffffffff812b8c97: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d5820)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812d5820-ffffffff812d588e: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e7390)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812e7390-ffffffff812e73fe: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8131f970)
Location: fs/pipe.c:95
Inline: False
Direct callers:
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff8131f970-ffffffff8131f9de: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132aeb0)
Location: fs/pipe.c:95
Inline: False
Direct callers:
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff8132aeb0-ffffffff8132af1e: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81330ec0)
Location: fs/pipe.c:110
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff81330ec0-ffffffff81330f2e: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137e640)
Location: fs/pipe.c:110
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff8137e640-ffffffff8137e6ae: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813fe660)
Location: fs/pipe.c:111
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff813fe660-ffffffff813fe702: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81488310)
Location: fs/pipe.c:111
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff81488310-ffffffff814883b2: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bd220)
Location: fs/pipe.c:111
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff814bd220-ffffffff814bd2c2: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814ef6c0)
Location: fs/pipe.c:111
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
**Symbols:**

```
ffffffff814ef6c0-ffffffff814ef762: pipe_double_lock (STB_GLOBAL)
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
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff800010390068)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffff800010390068-ffff800010390100: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0576af4)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
c0576af4-c0576b7c: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000487a10)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
c000000000487a10-c000000000487b30: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe00025fa98)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffe00025fa98-ffffffe00025fb20: pipe_double_lock (STB_GLOBAL)
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
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812df970)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812df970-ffffffff812df9de: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d05b0)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812d05b0-ffffffff812d061e: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dd780)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812dd780-ffffffff812dd7ee: pipe_double_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pipe_double_lock(struct pipe_inode_info *pipe1, struct pipe_inode_info *pipe2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ee700)
Location: fs/pipe.c:92
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812ee700-ffffffff812ee76e: pipe_double_lock (STB_GLOBAL)
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
