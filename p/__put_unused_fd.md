# Function: <code>__put_unused_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229b60)
Location: fs/file.c:565
Inline: True
Inline callers:
  - fs/file.c:put_unused_fd
  - fs/file.c:__close_fd
  - fs/file.c:do_close_on_exec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8125326a)
Location: fs/file.c:566
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812664ba)
Location: fs/file.c:566
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273c9a)
Location: fs/file.c:552
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8129656a)
Location: fs/file.c:553
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc93d)
Location: fs/file.c:548
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1bfd)
Location: fs/file.c:548
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eec1b)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff813006db)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff8133988b)
Location: fs/file.c:554
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff813454bb)
Location: fs/file.c:539
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff8134b85b)
Location: fs/file.c:539
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff8139969b)
Location: fs/file.c:539
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff8141c00f)
Location: fs/file.c:568
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
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
In fs/file.c (ffffffff814a8148)
Location: fs/file.c:568
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff814dd128)
Location: fs/file.c:568
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff8150fa68)
Location: fs/file.c:568
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:file_close_fd_locked
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffff8000103b2420)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (c0591804)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (c0000000004ae320)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffe000276450)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff812f8cbb)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff812e98db)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff812f6acb)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
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
In fs/file.c (ffffffff81307d1c)
Location: fs/file.c:549
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
```
</details>
</li>
</ul>

## Differences
