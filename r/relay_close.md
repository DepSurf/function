# Function: <code>relay_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8113d2a0)
Location: kernel/relay.c:812
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8113d2a0-ffffffff8113d39a: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff811457e0)
Location: kernel/relay.c:843
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff811457e0-ffffffff811458dc: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8114fc40)
Location: kernel/relay.c:832
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8114fc40-ffffffff8114fd50: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81151cc0)
Location: kernel/relay.c:832
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff81151cc0-ffffffff81151dbf: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8115ead0)
Location: kernel/relay.c:831
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8115ead0-ffffffff8115ebc4: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (0)
Location: kernel/relay.c:832
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8116dde7-ffffffff8116ddfd: relay_close.cold.20 (STB_LOCAL)
ffffffff8116dc40-ffffffff8116dd2f: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8117b708)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8117b827-ffffffff8117b83d: relay_close.cold.20 (STB_LOCAL)
ffffffff8117b680-ffffffff8117b76f: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81187f38)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff81188645-ffffffff8118865a: relay_close.cold (STB_LOCAL)
ffffffff81187f20-ffffffff81187ffe: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81193e78)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff81194585-ffffffff8119459a: relay_close.cold (STB_LOCAL)
ffffffff81193e60-ffffffff81193f3e: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811a8d60)
Location: kernel/relay.c:840
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff811a8c60-ffffffff811a8d57: relay_close.part.0 (STB_LOCAL)
ffffffff811a9608-ffffffff811a961d: relay_close.part.0.cold (STB_LOCAL)
ffffffff811a8d60-ffffffff811a8d76: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811a6550)
Location: kernel/relay.c:755
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff811a6450-ffffffff811a6547: relay_close.part.0 (STB_LOCAL)
ffffffff81be5081-ffffffff81be5096: relay_close.part.0.cold (STB_LOCAL)
ffffffff811a6550-ffffffff811a6566: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811a7387)
Location: kernel/relay.c:755
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_remove
```
**Symbols:**

```
ffffffff81bd6e71-ffffffff81bd6e86: relay_close.cold (STB_LOCAL)
ffffffff811a7370-ffffffff811a7471: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811d0c19)
Location: kernel/relay.c:755
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff81cb3fd1-ffffffff81cb3fe6: relay_close.cold (STB_LOCAL)
ffffffff811d0c00-ffffffff811d0d28: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff812050c9)
Location: kernel/relay.c:755
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff81e64f1b-ffffffff81e64f30: relay_close.cold (STB_LOCAL)
ffffffff812050b0-ffffffff812051ec: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8124d170)
Location: kernel/relay.c:752
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8124d170-ffffffff8124d2e2: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff812644f0)
Location: kernel/relay.c:752
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff812644f0-ffffffff81264662: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8127e2e0)
Location: kernel/relay.c:752
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8127e2e0-ffffffff8127e452: relay_close (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffff80001020c060)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffff80001020c060-ffff80001020c194: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (c044a928)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
c044a928-c044aa3c: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (c000000000289320)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
c000000000289320-c0000000002894f8: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffe00016d60e)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffe00016d60e-ffffffe00016d728: relay_close (STB_GLOBAL)
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
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8118c498)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8118cba5-ffffffff8118cbba: relay_close.cold (STB_LOCAL)
ffffffff8118c480-ffffffff8118c55e: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8117f578)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8117fc85-ffffffff8117fc9a: relay_close.cold (STB_LOCAL)
ffffffff8117f560-ffffffff8117f63e: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff8118a268)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff8118a975-ffffffff8118a98a: relay_close.cold (STB_LOCAL)
ffffffff8118a250-ffffffff8118a32e: relay_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void relay_close(struct rchan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff81197bd8)
Location: kernel/relay.c:834
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_free
```
**Symbols:**

```
ffffffff811982e5-ffffffff811982fa: relay_close.cold (STB_LOCAL)
ffffffff81197bc0-ffffffff81197c9e: relay_close (STB_GLOBAL)
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
