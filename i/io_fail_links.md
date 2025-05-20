# Function: <code>io_fail_links</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:645
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
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
In fs/io_uring.c (ffffffff813845d7)
Location: fs/io_uring.c:1577
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_fail_links(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390c00)
Location: fs/io_uring.c:2087
Inline: False
Direct callers:
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
```
**Symbols:**

```
ffffffff81390c00-ffffffff81390e87: io_fail_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_fail_links(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813937b0)
Location: fs/io_uring.c:1831
Inline: False
Direct callers:
  - fs/io_uring.c:io_disarm_next
```
**Symbols:**

```
ffffffff813937b0-ffffffff813938bf: io_fail_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_fail_links(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e1090)
Location: fs/io_uring.c:2073
Inline: False
Direct callers:
  - fs/io_uring.c:io_disarm_next
```
**Symbols:**

```
ffffffff813e1090-ffffffff813e1166: io_fail_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_fail_links(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d0150)
Location: io_uring/io_uring.c:2554
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_disarm_next
```
**Symbols:**

```
ffffffff816d0150-ffffffff816d0291: io_fail_links (STB_LOCAL)
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
In io_uring/timeout.c (ffffffff8179952e)
Location: io_uring/timeout.c:120
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
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
In io_uring/timeout.c (ffffffff817da5fe)
Location: io_uring/timeout.c:160
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
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
In io_uring/timeout.c (ffffffff8181e8ee)
Location: io_uring/timeout.c:160
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ada7a)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
