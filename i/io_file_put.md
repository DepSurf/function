# Function: <code>io_file_put</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d350)
Location: fs/io_uring.c:946
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff8132d350-ffffffff8132d383: io_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813402d0)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff813402d0-ffffffff81340303: io_file_put (STB_LOCAL)
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
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010400400)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffff800010400400-ffff800010400444: io_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d2758)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
c05d2758-c05d27a0: io_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509b20)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
c000000000509b20-c000000000509b8c: io_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002acb14)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffe0002acb14-ffffffe0002acb50: io_file_put (STB_LOCAL)
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
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813388b0)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff813388b0-ffffffff813388e3: io_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813295e0)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff813295e0-ffffffff81329613: io_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336380)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81336380-ffffffff813363b3: io_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_file_put(struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81349450)
Location: fs/io_uring.c:1016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_state_end
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81349450-ffffffff81349483: io_file_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
