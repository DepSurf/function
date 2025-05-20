# Function: <code>wakeup_pipe_writers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123da10)
Location: fs/splice.c:724
Inline: False
Direct callers:
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:SyS_splice
```
**Symbols:**

```
ffffffff8123da10-ffffffff8123da55: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81265ae0)
Location: fs/splice.c:725
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81265ae0-ffffffff81265b28: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812791d0)
Location: fs/splice.c:475
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812791d0-ffffffff81279218: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81286740)
Location: fs/splice.c:471
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81286740-ffffffff81286788: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a9200)
Location: fs/splice.c:455
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812a9200-ffffffff812a924b: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812cfd40)
Location: fs/splice.c:456
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812cfd40-ffffffff812cfd8b: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e5150)
Location: fs/splice.c:456
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812e5150-ffffffff812e519b: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81303950)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81303950-ffffffff8130399b: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813169d0)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff813169d0-ffffffff81316a1b: wakeup_pipe_writers (STB_LOCAL)
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
In fs/splice.c (ffffffff813511de)
Location: fs/splice.c:452
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
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
In fs/splice.c (ffffffff8135e44e)
Location: fs/splice.c:368
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
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
In fs/splice.c (ffffffff8136515e)
Location: fs/splice.c:368
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
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
In fs/splice.c (ffffffff813b3a4e)
Location: fs/splice.c:368
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
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
In fs/splice.c (ffffffff81438dbb)
Location: fs/splice.c:368
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
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
In fs/splice.c (ffffffff814c6eeb)
Location: fs/splice.c:365
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
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
In fs/splice.c (ffffffff814fc86b)
Location: fs/splice.c:419
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
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
In fs/splice.c (ffffffff8153149b)
Location: fs/splice.c:417
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cd348)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffff8000103cd348-ffff8000103cd3a4: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a8eb4)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
c05a8eb4-c05a8f08: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004cf150)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
c0000000004cf150-c0000000004cf1c8: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028a704)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffe00028a704-ffffffe00028a754: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130efb0)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff8130efb0-ffffffff8130effb: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812ffbc0)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812ffbc0-ffffffff812ffc0b: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130cda0)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff8130cda0-ffffffff8130cdeb: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_pipe_writers(struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131e5b0)
Location: fs/splice.c:453
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff8131e5b0-ffffffff8131e5fb: wakeup_pipe_writers (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
