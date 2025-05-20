# Function: <code>io_disarm_next</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_disarm_next(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813938c0)
Location: fs/io_uring.c:1848
Inline: False
Direct callers:
  - fs/io_uring.c:__io_req_find_next
  - fs/io_uring.c:io_req_complete_post
```
**Symbols:**

```
ffffffff813938c0-ffffffff813939b7: io_disarm_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_disarm_next(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e7940)
Location: fs/io_uring.c:2095
Inline: False
Direct callers:
  - fs/io_uring.c:__io_req_find_next
  - fs/io_uring.c:io_req_complete_post
```
**Symbols:**

```
ffffffff813e7940-ffffffff813e7b2b: io_disarm_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_disarm_next(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cfdd0)
Location: io_uring/io_uring.c:2582
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_put
```
**Symbols:**

```
ffffffff816cfdd0-ffffffff816cff94: io_disarm_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_disarm_next(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817994b0)
Location: io_uring/timeout.c:152
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_complete_post
```
**Symbols:**

```
ffffffff817994b0-ffffffff817996d8: io_disarm_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_disarm_next(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817da580)
Location: io_uring/timeout.c:192
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_complete_post
```
**Symbols:**

```
ffffffff817da580-ffffffff817da7a2: io_disarm_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_disarm_next(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181e870)
Location: io_uring/timeout.c:192
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_complete_post
```
**Symbols:**

```
ffffffff8181e870-ffffffff8181ea92: io_disarm_next (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
