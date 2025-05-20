# Function: <code>splice_shrink_spd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff8123e760)
Location: fs/splice.c:294
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:vmsplice_to_pipe
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - mm/shmem.c:shmem_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff8123e760-ffffffff8123e781: splice_shrink_spd.part.13 (STB_LOCAL)
ffffffff8123f5b0-ffffffff8123f5c7: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/splice.c (ffffffff81267866)
Location: fs/splice.c:297
Inline: True
Inline callers:
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:__generic_file_splice_read
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - mm/shmem.c:shmem_file_splice_read
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:__generic_file_splice_read
```
**Symbols:**

```
ffffffff812664a0-ffffffff812664c1: splice_shrink_spd.part.16 (STB_LOCAL)
ffffffff812678f0-ffffffff81267907: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8127a850)
Location: fs/splice.c:276
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff8127a850-ffffffff8127a878: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81287ca0)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81287ca0-ffffffff81287cc9: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812aa7d0)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff812aa7d0-ffffffff812aa7f9: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d21a0)
Location: fs/splice.c:274
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff812d21a0-ffffffff812d21c8: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e7580)
Location: fs/splice.c:274
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff812e7580-ffffffff812e75a8: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81305e20)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81305e20-ffffffff81305e48: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81318eb0)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81318eb0-ffffffff81318ed8: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813522b0)
Location: fs/splice.c:277
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff813522b0-ffffffff813522db: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135ea10)
Location: fs/splice.c:276
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff8135ea10-ffffffff8135ea3b: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81365300)
Location: fs/splice.c:276
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81365300-ffffffff8136532b: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b3bf0)
Location: fs/splice.c:276
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff813b3bf0-ffffffff813b3c1b: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81438ed0)
Location: fs/splice.c:276
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81438ed0-ffffffff81438f07: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c7190)
Location: fs/splice.c:276
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff814c7190-ffffffff814c71c7: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fc9a0)
Location: fs/splice.c:294
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff814fc9a0-ffffffff814fc9d7: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff815315d0)
Location: fs/splice.c:292
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff815315d0-ffffffff81531607: splice_shrink_spd (STB_GLOBAL)
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
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cfcb0)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffff8000103cfcb0-ffff8000103cfcf0: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05aad08)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
c05aad08-c05aad40: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d22d0)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
c0000000004d22d0-c0000000004d232c: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028bd18)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffe00028bd18-ffffffe00028bd54: splice_shrink_spd (STB_GLOBAL)
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
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81311490)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81311490-ffffffff813114b8: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813020a0)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff813020a0-ffffffff813020c8: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130f280)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff8130f280-ffffffff8130f2a8: splice_shrink_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void splice_shrink_spd(struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81320a80)
Location: fs/splice.c:273
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
```
**Symbols:**

```
ffffffff81320a80-ffffffff81320aa8: splice_shrink_spd (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
