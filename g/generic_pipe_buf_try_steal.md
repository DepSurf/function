# Function: <code>generic_pipe_buf_try_steal</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8131e830)
Location: fs/pipe.c:149
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff8131e830-ffffffff8131e89a: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81329d90)
Location: fs/pipe.c:149
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff81329d90-ffffffff81329dfa: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132fd50)
Location: fs/pipe.c:164
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff8132fd50-ffffffff8132fdba: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137d510)
Location: fs/pipe.c:164
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff8137d510-ffffffff8137d57a: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813fe310)
Location: fs/pipe.c:165
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff813fe310-ffffffff813fe3c1: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81487f80)
Location: fs/pipe.c:165
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff81487f80-ffffffff81488031: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bce70)
Location: fs/pipe.c:165
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff814bce70-ffffffff814bcf29: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool generic_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814ef310)
Location: fs/pipe.c:165
Inline: False
Direct callers:
  - fs/splice.c:user_page_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff814ef310-ffffffff814ef3c3: generic_pipe_buf_try_steal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
