# Function: <code>watch_queue_set_filter</code>

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
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124d110)
Location: kernel/watch_queue.c:286
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff8124d110-ffffffff8124d333: watch_queue_set_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81257570)
Location: kernel/watch_queue.c:286
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff81257570-ffffffff8125779b: watch_queue_set_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125b9f0)
Location: kernel/watch_queue.c:286
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff8125b9f0-ffffffff8125bbfe: watch_queue_set_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812978a0)
Location: kernel/watch_queue.c:288
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff812978a0-ffffffff81297aa9: watch_queue_set_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812edb60)
Location: kernel/watch_queue.c:310
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff812edb60-ffffffff812edd7e: watch_queue_set_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81357f60)
Location: kernel/watch_queue.c:310
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff81357f60-ffffffff8135817e: watch_queue_set_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813897f0)
Location: kernel/watch_queue.c:307
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff813897f0-ffffffff813899ff: watch_queue_set_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int watch_queue_set_filter(struct pipe_inode_info *pipe, struct watch_notification_filter *_filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b3240)
Location: kernel/watch_queue.c:307
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff813b3240-ffffffff813b344f: watch_queue_set_filter (STB_GLOBAL)
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
