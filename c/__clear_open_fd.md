# Function: <code>__clear_open_fd</code>

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
In fs/file.c (ffffffff81229b64)
Location: fs/file.c:264
Inline: True
Inline callers:
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff81253272)
Location: fs/file.c:265
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff812664c2)
Location: fs/file.c:265
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff81273ca2)
Location: fs/file.c:251
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff81296572)
Location: fs/file.c:252
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff812bc945)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff812d1c05)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff812eec23)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff813006e3)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff8133988f)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff813454bf)
Location: fs/file.c:252
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff8134b85f)
Location: fs/file.c:252
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff8139969f)
Location: fs/file.c:252
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff8141c014)
Location: fs/file.c:268
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff814a814c)
Location: fs/file.c:268
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff814dd12c)
Location: fs/file.c:268
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:pick_file
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff8150fa6c)
Location: fs/file.c:268
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:file_close_fd_locked
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffff8000103b2430)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (c059180c)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (c0000000004ae324)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff812f8cc3)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff812e98e3)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff812f6ad3)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
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
In fs/file.c (ffffffff81307d24)
Location: fs/file.c:247
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:dup_fd
```
</details>
</li>
</ul>

## Differences
