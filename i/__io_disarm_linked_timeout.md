# Function: <code>__io_disarm_linked_timeout</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct io_kiocb *__io_disarm_linked_timeout(struct io_kiocb *req, struct io_kiocb *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff81799664)
Location: io_uring/timeout.c:178
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
**Symbols:**

```
ffffffff817996f0-ffffffff81799778: __io_disarm_linked_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct io_kiocb *__io_disarm_linked_timeout(struct io_kiocb *req, struct io_kiocb *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817da72e)
Location: io_uring/timeout.c:218
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
**Symbols:**

```
ffffffff817da7c0-ffffffff817da848: __io_disarm_linked_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct io_kiocb *__io_disarm_linked_timeout(struct io_kiocb *req, struct io_kiocb *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181ea1e)
Location: io_uring/timeout.c:218
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
**Symbols:**

```
ffffffff8181eab0-ffffffff8181eb38: __io_disarm_linked_timeout (STB_GLOBAL)
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
