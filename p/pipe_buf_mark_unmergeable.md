# Function: <code>pipe_buf_mark_unmergeable</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b94c0)
Location: fs/pipe.c:253
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812b94c0-ffffffff812b94df: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d6110)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812d6110-ffffffff812d612f: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e7c80)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812e7c80-ffffffff812e7c9f: pipe_buf_mark_unmergeable (STB_GLOBAL)
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
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff800010390968)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffff800010390968-ffff8000103909b8: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c057749c)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
c057749c-c05774cc: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0000000004887d0)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
c0000000004887d0-c000000000488808: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe0002601fe)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffe0002601fe-ffffffe000260240: pipe_buf_mark_unmergeable (STB_GLOBAL)
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
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e0260)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812e0260-ffffffff812e027f: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d0ea0)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812d0ea0-ffffffff812d0ebf: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812de070)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812de070-ffffffff812de08f: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pipe_buf_mark_unmergeable(struct pipe_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812eeff0)
Location: fs/pipe.c:260
Inline: False
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812eeff0-ffffffff812ef00f: pipe_buf_mark_unmergeable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
