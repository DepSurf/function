# Function: <code>relay_subbufs_consumed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8113c740)
Location: kernel/relay.c:785
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_pipe_buf_release
Direct callers:
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_pipe_buf_release
```
**Symbols:**

```
ffffffff8113c740-ffffffff8113c77d: relay_subbufs_consumed.part.5 (STB_LOCAL)
ffffffff8113c780-ffffffff8113c79e: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81144e70)
Location: kernel/relay.c:816
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff81144cb0-ffffffff81144ce9: relay_subbufs_consumed.part.7 (STB_LOCAL)
ffffffff81144cf0-ffffffff81144d0e: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8114ef50)
Location: kernel/relay.c:806
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8114eac0-ffffffff8114eb04: relay_subbufs_consumed.part.10 (STB_LOCAL)
ffffffff8114eb10-ffffffff8114eb2e: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81151600)
Location: kernel/relay.c:806
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff81151170-ffffffff811511b4: relay_subbufs_consumed.part.8 (STB_LOCAL)
ffffffff811511c0-ffffffff811511df: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8115de00)
Location: kernel/relay.c:805
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8115d970-ffffffff8115d9b4: relay_subbufs_consumed.part.8 (STB_LOCAL)
ffffffff8115d9c0-ffffffff8115d9df: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8116cd56)
Location: kernel/relay.c:806
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8116c8e0-ffffffff8116c924: relay_subbufs_consumed.part.10 (STB_LOCAL)
ffffffff8116c930-ffffffff8116c94e: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8117aa76)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8117a600-ffffffff8117a644: relay_subbufs_consumed.part.10 (STB_LOCAL)
ffffffff8117a650-ffffffff8117a66e: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811878c6)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff81187450-ffffffff81187494: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffffffff811874a0-ffffffff811874be: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81193806)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff81193370-ffffffff811933b4: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffffffff811933c0-ffffffff811933de: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811a8570)
Location: kernel/relay.c:814
Inline: True
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff811a8570-ffffffff811a85c2: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811a5af0)
Location: kernel/relay.c:729
Inline: True
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff811a5af0-ffffffff811a5b42: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811a64d0)
Location: kernel/relay.c:729
Inline: True
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff811a64d0-ffffffff811a6522: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811cfc90)
Location: kernel/relay.c:729
Inline: True
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff811cfc90-ffffffff811cfd1a: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81204190)
Location: kernel/relay.c:729
Inline: True
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff81204190-ffffffff81204237: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8124c040)
Location: kernel/relay.c:726
Inline: True
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8124c040-ffffffff8124c0e7: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81262f60)
Location: kernel/relay.c:726
Inline: True
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff81262f60-ffffffff81263007: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8127d180)
Location: kernel/relay.c:726
Inline: True
Direct callers:
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8127d180-ffffffff8127d227: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffff80001020b274)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffff80001020b040-ffff80001020b0b0: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffff80001020b0b0-ffff80001020b100: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (c044a258)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
c0449cf0-c0449d48: relay_subbufs_consumed.part.0 (STB_LOCAL)
c0449d48-c0449d80: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (c000000000288880)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
c000000000288290-c0000000002882fc: relay_subbufs_consumed.part.0 (STB_LOCAL)
c000000000288300-c000000000288324: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffe00016cd5c)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffe00016c97e-ffffffe00016c9ee: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffffffe00016c9ee-ffffffe00016ca30: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8118be26)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8118b990-ffffffff8118b9d4: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffffffff8118b9e0-ffffffff8118b9fe: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8117ef06)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff8117ea70-ffffffff8117eab4: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffffffff8117eac0-ffffffff8117eade: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81189bf6)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff81189760-ffffffff811897a4: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffffffff811897b0-ffffffff811897ce: relay_subbufs_consumed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_subbufs_consumed(struct rchan *chan, unsigned int cpu, size_t subbufs_consumed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81197566)
Location: kernel/relay.c:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
Direct callers:
  - kernel/relay.c:relay_pipe_buf_release
  - kernel/relay.c:relay_file_read_consume
  - kernel/relay.c:relay_file_read_consume
```
**Symbols:**

```
ffffffff811970d0-ffffffff81197114: relay_subbufs_consumed.part.0 (STB_LOCAL)
ffffffff81197120-ffffffff8119713e: relay_subbufs_consumed (STB_GLOBAL)
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
