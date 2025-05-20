# Function: <code>watch_queue_set_size</code>

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
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124cf30)
Location: kernel/watch_queue.c:216
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff8124cf30-ffffffff8124d106: watch_queue_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81257390)
Location: kernel/watch_queue.c:216
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff81257390-ffffffff81257566: watch_queue_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125b810)
Location: kernel/watch_queue.c:216
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff8125b810-ffffffff8125b9e6: watch_queue_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:217
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff81cb9ca6-ffffffff81cb9cc4: watch_queue_set_size.cold (STB_LOCAL)
ffffffff81297680-ffffffff8129789b: watch_queue_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:242
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff81e6b2e3-ffffffff81e6b301: watch_queue_set_size.cold (STB_LOCAL)
ffffffff812ed920-ffffffff812edb59: watch_queue_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:242
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff82062054-ffffffff82062072: watch_queue_set_size.cold (STB_LOCAL)
ffffffff81357d10-ffffffff81357f49: watch_queue_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:238
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff820e1827-ffffffff820e1845: watch_queue_set_size.cold (STB_LOCAL)
ffffffff813895a0-ffffffff813897d9: watch_queue_set_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int watch_queue_set_size(struct pipe_inode_info *pipe, unsigned int nr_notes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:238
Inline: False
Direct callers:
  - fs/pipe.c:pipe_ioctl
```
**Symbols:**

```
ffffffff821be28a-ffffffff821be2a8: watch_queue_set_size.cold (STB_LOCAL)
ffffffff813b2ff0-ffffffff813b3229: watch_queue_set_size (STB_GLOBAL)
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
