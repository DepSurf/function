# Function: <code>io_poll_remove_all_table</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool io_poll_remove_all_table(struct task_struct *tsk, struct io_hash_table *table, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:739
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove_all
  - io_uring/poll.c:io_poll_remove_all
```
**Symbols:**

```
ffffffff8179cbd0-ffffffff8179cd38: io_poll_remove_all_table (STB_LOCAL)
ffffffff82077890-ffffffff820778a8: io_poll_remove_all_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool io_poll_remove_all_table(struct task_struct *tsk, struct io_hash_table *table, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:742
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove_all
  - io_uring/poll.c:io_poll_remove_all
```
**Symbols:**

```
ffffffff817dde00-ffffffff817ddf68: io_poll_remove_all_table (STB_LOCAL)
ffffffff820f7910-ffffffff820f7928: io_poll_remove_all_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool io_poll_remove_all_table(struct task_struct *tsk, struct io_hash_table *table, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/poll.c (0)
Location: io_uring/poll.c:763
Inline: False
Direct callers:
  - io_uring/poll.c:io_poll_remove_all
  - io_uring/poll.c:io_poll_remove_all
```
**Symbols:**

```
ffffffff818221a0-ffffffff81822308: io_poll_remove_all_table (STB_LOCAL)
ffffffff821d5303-ffffffff821d531b: io_poll_remove_all_table.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
