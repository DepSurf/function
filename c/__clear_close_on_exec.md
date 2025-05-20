# Function: <code>__clear_close_on_exec</code>

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
In fs/file.c (ffffffff81229fdc)
Location: fs/file.c:250
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:__alloc_fd
  - fs/file.c:__close_fd
  - fs/file.c:set_close_on_exec
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
In fs/file.c (ffffffff8125270d)
Location: fs/file.c:251
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812659a5)
Location: fs/file.c:251
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812730f0)
Location: fs/file.c:237
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__close_fd
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff81295a20)
Location: fs/file.c:238
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812bbcb0)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812d0f30)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812edf3b)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812ff9fb)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff81338b31)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff813445b1)
Location: fs/file.c:238
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
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
In fs/file.c (ffffffff8134a951)
Location: fs/file.c:238
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
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
In fs/file.c (ffffffff81398701)
Location: fs/file.c:238
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
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
In fs/file.c (ffffffff8141ae67)
Location: fs/file.c:254
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
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
In fs/file.c (ffffffff814a702b)
Location: fs/file.c:254
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
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
In fs/file.c (ffffffff814dc008)
Location: fs/file.c:254
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
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
In fs/file.c (ffffffff8150e228)
Location: fs/file.c:254
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
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
In fs/file.c (ffff8000103b1068)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (c0590b40)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (c0000000004accbc)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffe00027554c)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812f7fdb)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812e8bfb)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff812f5deb)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
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
In fs/file.c (ffffffff81306f0f)
Location: fs/file.c:233
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
```
</details>
</li>
</ul>

## Differences
