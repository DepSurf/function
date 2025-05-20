# Function: <code>splice_pipe_to_pipe</code>

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
In fs/splice.c (ffffffff8123fa70)
Location: fs/splice.c:1798
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff81267db0)
Location: fs/splice.c:1802
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff8127ad20)
Location: fs/splice.c:1512
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff81288153)
Location: fs/splice.c:1513
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (ffffffff812aac83)
Location: fs/splice.c:1497
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
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
In fs/splice.c (0)
Location: fs/splice.c:1510
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (0)
Location: fs/splice.c:1514
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffff813046c7)
Location: fs/splice.c:1520
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffff81317747)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81350fa0)
Location: fs/splice.c:1508
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81350fa0-ffffffff813512ff: splice_pipe_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135e210)
Location: fs/splice.c:1432
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8135e210-ffffffff8135e56f: splice_pipe_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81364f20)
Location: fs/splice.c:1437
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81364f20-ffffffff8136527f: splice_pipe_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b3810)
Location: fs/splice.c:1439
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff813b3810-ffffffff813b3b6f: splice_pipe_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81438ae0)
Location: fs/splice.c:1435
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81438ae0-ffffffff81438e3a: splice_pipe_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c6c10)
Location: fs/splice.c:1435
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff814c6c10-ffffffff814c6f6a: splice_pipe_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fc590)
Location: fs/splice.c:1676
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff814fc590-ffffffff814fc8ea: splice_pipe_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int splice_pipe_to_pipe(struct pipe_inode_info *ipipe, struct pipe_inode_info *opipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff815311c0)
Location: fs/splice.c:1739
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff815311c0-ffffffff8153151a: splice_pipe_to_pipe (STB_LOCAL)
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
In fs/splice.c (ffff8000103cee3c)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (c05aa074)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (c0000000004d0758)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffe00028afd8)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffff8130fd27)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffff81300937)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffff8130db17)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
In fs/splice.c (ffffffff8131f317)
Location: fs/splice.c:1528
Inline: True
Inline callers:
  - fs/splice.c:do_splice
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
