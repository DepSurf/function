# Function: <code>generic_pipe_buf_confirm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81214910)
Location: fs/pipe.c:196
Inline: False
```
**Symbols:**

```
ffffffff81214910-ffffffff8121491d: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123b6a0)
Location: fs/pipe.c:211
Inline: False
```
**Symbols:**

```
ffffffff8123b6a0-ffffffff8123b6ad: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124e440)
Location: fs/pipe.c:211
Inline: False
```
**Symbols:**

```
ffffffff8124e440-ffffffff8124e44d: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125a3d0)
Location: fs/pipe.c:211
Inline: False
```
**Symbols:**

```
ffffffff8125a3d0-ffffffff8125a3dd: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127c6d0)
Location: fs/pipe.c:212
Inline: False
```
**Symbols:**

```
ffffffff8127c6d0-ffffffff8127c6dd: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a3660)
Location: fs/pipe.c:207
Inline: False
```
**Symbols:**

```
ffffffff812a3660-ffffffff812a366d: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b87b0)
Location: fs/pipe.c:207
Inline: False
```
**Symbols:**

```
ffffffff812b87b0-ffffffff812b87bd: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d5320)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffffffff812d5320-ffffffff812d532d: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e6e90)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffffffff812e6e90-ffffffff812e6e9d: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff80001038f7a0)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffff80001038f7a0-ffff80001038f7bc: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0576494)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
c0576494-c05764b0: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000486fa0)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
c000000000486fa0-c000000000486fb0: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe00025f442)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffffffe00025f442-ffffffe00025f45e: generic_pipe_buf_confirm (STB_GLOBAL)
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
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812df470)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffffffff812df470-ffffffff812df47d: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d00b0)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffffffff812d00b0-ffffffff812d00bd: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dd280)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffffffff812dd280-ffffffff812dd28d: generic_pipe_buf_confirm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_pipe_buf_confirm(struct pipe_inode_info *info, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ee210)
Location: fs/pipe.c:207
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
```
**Symbols:**

```
ffffffff812ee210-ffffffff812ee21d: generic_pipe_buf_confirm (STB_GLOBAL)
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
