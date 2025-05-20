# Function: <code>splice_from_pipe_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int splice_from_pipe_next(struct pipe_inode_info *pipe, struct splice_desc *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123e090)
Location: fs/splice.c:810
Inline: True
Direct callers:
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:iter_file_splice_write
```
**Symbols:**

```
ffffffff8123e090-ffffffff8123e14b: splice_from_pipe_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int splice_from_pipe_next(struct pipe_inode_info *pipe, struct splice_desc *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81266160)
Location: fs/splice.c:811
Inline: True
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81266160-ffffffff8126621b: splice_from_pipe_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff8127a444)
Location: fs/splice.c:559
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81279a10-ffffffff81279ad9: splice_from_pipe_next.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff81287916)
Location: fs/splice.c:555
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81286f70-ffffffff81287029: splice_from_pipe_next.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff812aa446)
Location: fs/splice.c:539
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812a9760-ffffffff812a980e: splice_from_pipe_next.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff812d1af2)
Location: fs/splice.c:540
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812d04c0-ffffffff812d056e: splice_from_pipe_next.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff812e6ed2)
Location: fs/splice.c:540
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff812e56e0-ffffffff812e578e: splice_from_pipe_next.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff813041f3)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81303ef0-ffffffff81303f9f: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff81317273)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81316f70-ffffffff8131701f: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff8135181f)
Location: fs/splice.c:539
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff813509b0-ffffffff81350aa6: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff8135e62f)
Location: fs/splice.c:471
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff8135da80-ffffffff8135dbb0: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff813646bc)
Location: fs/splice.c:471
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff813644d0-ffffffff813645fc: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff813b34ac)
Location: fs/splice.c:471
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff813b2d90-ffffffff813b2ecd: splice_from_pipe_next.part.0 (STB_LOCAL)
ffffffff81cc4140-ffffffff81cc4155: splice_from_pipe_next.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int splice_from_pipe_next(struct pipe_inode_info *pipe, struct splice_desc *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/splice.c (0)
Location: fs/splice.c:471
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81437cb0-ffffffff81437e1c: splice_from_pipe_next (STB_LOCAL)
ffffffff81e76a50-ffffffff81e76a65: splice_from_pipe_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int splice_from_pipe_next(struct pipe_inode_info *pipe, struct splice_desc *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/splice.c (0)
Location: fs/splice.c:468
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff814c5b10-ffffffff814c5c7c: splice_from_pipe_next (STB_LOCAL)
ffffffff82068d77-ffffffff82068d8c: splice_from_pipe_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int splice_from_pipe_next(struct pipe_inode_info *pipe, struct splice_desc *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/splice.c (0)
Location: fs/splice.c:522
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff814fb4e0-ffffffff814fb64c: splice_from_pipe_next (STB_LOCAL)
ffffffff820e869b-ffffffff820e86b0: splice_from_pipe_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int splice_from_pipe_next(struct pipe_inode_info *pipe, struct splice_desc *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/splice.c (0)
Location: fs/splice.c:520
Inline: False
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81530370-ffffffff815304dc: splice_from_pipe_next (STB_LOCAL)
ffffffff821c5485-ffffffff821c549a: splice_from_pipe_next.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffff8000103cf634)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffff8000103cd9c0-ffff8000103cda9c: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int splice_from_pipe_next(struct pipe_inode_info *pipe, struct splice_desc *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a9570)
Location: fs/splice.c:537
Inline: True
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
c05a9570-c05a9658: splice_from_pipe_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (c0000000004cffe0)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
c0000000004cfad0-c0000000004cfc5c: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffe00028b84c)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffe00028ac24-ffffffe00028accc: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff8130f853)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff8130f550-ffffffff8130f5ff: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff81300463)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff81300160-ffffffff8130020f: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff8130d643)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff8130d340-ffffffff8130d3ef: splice_from_pipe_next.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff8131ee43)
Location: fs/splice.c:537
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
Direct callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
**Symbols:**

```
ffffffff8131eb30-ffffffff8131ebdf: splice_from_pipe_next.part.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
