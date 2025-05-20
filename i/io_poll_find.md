# Function: <code>io_poll_find</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813914d0)
Location: fs/io_uring.c:5319
Inline: True
Direct callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
```
**Symbols:**

```
ffffffff813914d0-ffffffff8139152b: io_poll_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:5778
Inline: True
Direct callers:
  - fs/io_uring.c:io_try_cancel_userdata
```
**Symbols:**

```
ffffffff813df2c0-ffffffff813df33d: io_poll_find.isra.0 (STB_LOCAL)
ffffffff81cc58c0-ffffffff81cc58dc: io_poll_find.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:7070
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_poll_remove
```
**Symbols:**

```
ffffffff816ca970-ffffffff816caa30: io_poll_find.isra.0 (STB_LOCAL)
ffffffff81e907b6-ffffffff81e907d2: io_poll_find.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:779
Inline: True
Direct callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
```
**Symbols:**

```
ffffffff8179c940-ffffffff8179ca1a: io_poll_find.constprop.0 (STB_LOCAL)
ffffffff82077874-ffffffff82077890: io_poll_find.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:782
Inline: True
Direct callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
```
**Symbols:**

```
ffffffff817ddb70-ffffffff817ddc4a: io_poll_find.isra.0 (STB_LOCAL)
ffffffff820f78f4-ffffffff820f7910: io_poll_find.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:803
Inline: True
Direct callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
```
**Symbols:**

```
ffffffff81821f10-ffffffff81821fea: io_poll_find.isra.0 (STB_LOCAL)
ffffffff821d52e7-ffffffff821d5303: io_poll_find.isra.0.cold (STB_LOCAL)
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
