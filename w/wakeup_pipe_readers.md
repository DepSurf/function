# Function: <code>wakeup_pipe_readers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123d790)
Location: fs/splice.c:163
Inline: False
Direct callers:
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_tee
```
**Symbols:**

```
ffffffff8123d790-ffffffff8123d7d5: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81265850)
Location: fs/splice.c:163
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:splice_to_pipe
```
**Symbols:**

```
ffffffff81265850-ffffffff81265898: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81279220)
Location: fs/splice.c:164
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff81279220-ffffffff81279268: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81286790)
Location: fs/splice.c:166
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff81286790-ffffffff812867d8: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a9250)
Location: fs/splice.c:166
Inline: False
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff812a9250-ffffffff812a929b: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812cfd90)
Location: fs/splice.c:166
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812cfd90-ffffffff812cfddb: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e51a0)
Location: fs/splice.c:166
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812e51a0-ffffffff812e51eb: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813039a0)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff813039a0-ffffffff813039eb: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81316a20)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81316a20-ffffffff81316a6b: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81351115)
Location: fs/splice.c:164
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:do_splice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135e385)
Location: fs/splice.c:163
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffff81365dbd)
Location: fs/splice.c:163
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
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
In fs/splice.c (ffffffff813b46ad)
Location: fs/splice.c:163
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
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
In fs/splice.c (ffffffff81439ab2)
Location: fs/splice.c:163
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
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
In fs/splice.c (ffffffff814c7de2)
Location: fs/splice.c:163
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
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
In fs/splice.c (ffffffff814fddc8)
Location: fs/splice.c:181
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
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
In fs/splice.c (ffffffff81532a43)
Location: fs/splice.c:178
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
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
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cd3a8)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffff8000103cd3a8-ffff8000103cd404: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a8f08)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
c05a8f08-c05a8f5c: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004cf1d0)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
c0000000004cf1d0-c0000000004cf248: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028a754)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffe00028a754-ffffffe00028a7a4: wakeup_pipe_readers (STB_LOCAL)
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
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130f000)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8130f000-ffffffff8130f04b: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812ffc10)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812ffc10-ffffffff812ffc5b: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130cdf0)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8130cdf0-ffffffff8130ce3b: wakeup_pipe_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_pipe_readers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131e600)
Location: fs/splice.c:165
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8131e600-ffffffff8131e64b: wakeup_pipe_readers (STB_LOCAL)
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
