# Function: <code>watch_queue_clear</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124d380)
Location: kernel/watch_queue.c:560
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff8124d380-ffffffff8124d4f9: watch_queue_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812577e0)
Location: kernel/watch_queue.c:560
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff812577e0-ffffffff8125796b: watch_queue_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125bc40)
Location: kernel/watch_queue.c:560
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff8125bc40-ffffffff8125bdcb: watch_queue_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81297af0)
Location: kernel/watch_queue.c:563
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff81297af0-ffffffff81297c7b: watch_queue_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812eddc0)
Location: kernel/watch_queue.c:597
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff812eddc0-ffffffff812edf5a: watch_queue_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813581e0)
Location: kernel/watch_queue.c:597
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff813581e0-ffffffff8135837a: watch_queue_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81389a60)
Location: kernel/watch_queue.c:594
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff81389a60-ffffffff81389c0f: watch_queue_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void watch_queue_clear(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b34b0)
Location: kernel/watch_queue.c:594
Inline: False
Direct callers:
  - fs/pipe.c:free_pipe_info
```
**Symbols:**

```
ffffffff813b34b0-ffffffff813b365f: watch_queue_clear (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
