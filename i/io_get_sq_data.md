# Function: <code>io_get_sq_data</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393f4a)
Location: fs/io_uring.c:7453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct io_sq_data *io_get_sq_data(struct io_uring_params *p, bool *attached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813921d0)
Location: fs/io_uring.c:7352
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff813921d0-ffffffff8139239c: io_get_sq_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct io_sq_data *io_get_sq_data(struct io_uring_params *p, bool *attached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e31c0)
Location: fs/io_uring.c:8053
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff813e31c0-ffffffff813e338c: io_get_sq_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct io_sq_data *io_get_sq_data(struct io_uring_params *p, bool *attached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e9039e)
Location: io_uring/io_uring.c:9403
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff81e9039e-ffffffff81e9050e: io_get_sq_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_sq_data *io_get_sq_data(struct io_uring_params *p, bool *attached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8179a010)
Location: io_uring/sqpoll.c:132
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff8179a010-ffffffff8179a1f7: io_get_sq_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_sq_data *io_get_sq_data(struct io_uring_params *p, bool *attached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff817db070)
Location: io_uring/sqpoll.c:132
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff817db070-ffffffff817db257: io_get_sq_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_sq_data *io_get_sq_data(struct io_uring_params *p, bool *attached);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8181f360)
Location: io_uring/sqpoll.c:132
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff8181f360-ffffffff8181f576: io_get_sq_data (STB_LOCAL)
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
