# Function: <code>too_many_pipe_buffers_soft</code>

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
In fs/pipe.c (ffffffff8121563e)
Location: fs/pipe.c:598
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:pipe_fcntl
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
In fs/pipe.c (ffffffff8123d0a0)
Location: fs/pipe.c:613
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff8124fd66)
Location: fs/pipe.c:610
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff8125bc92)
Location: fs/pipe.c:610
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff8127e047)
Location: fs/pipe.c:611
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812a4f94)
Location: fs/pipe.c:606
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812ba064)
Location: fs/pipe.c:620
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812d6cec)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812e885c)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81320aca)
Location: fs/pipe.c:747
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff8131fa00-ffffffff8131fa20: too_many_pipe_buffers_soft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132c02c)
Location: fs/pipe.c:747
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff8132af40-ffffffff8132af60: too_many_pipe_buffers_soft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8133206c)
Location: fs/pipe.c:761
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff81330f50-ffffffff81330f70: too_many_pipe_buffers_soft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137f7fc)
Location: fs/pipe.c:762
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff8137e6d0-ffffffff8137e6f0: too_many_pipe_buffers_soft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813ff965)
Location: fs/pipe.c:763
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff813fe740-ffffffff813fe768: too_many_pipe_buffers_soft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81489765)
Location: fs/pipe.c:763
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff81488410-ffffffff81488438: too_many_pipe_buffers_soft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814be693)
Location: fs/pipe.c:765
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff814bd320-ffffffff814bd348: too_many_pipe_buffers_soft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool too_many_pipe_buffers_soft(long unsigned int user_bufs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814f0b2f)
Location: fs/pipe.c:781
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
```
**Symbols:**

```
ffffffff814ef7c0-ffffffff814ef7e8: too_many_pipe_buffers_soft (STB_GLOBAL)
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
In fs/pipe.c (ffff8000103918f0)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (c05781ac)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (c0000000004899c0)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffe000260d8a)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812e0e3c)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812d1a7c)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812dec4c)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
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
In fs/pipe.c (ffffffff812efbbc)
Location: fs/pipe.c:632
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
```
</details>
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
