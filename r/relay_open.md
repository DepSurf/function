# Function: <code>relay_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8113d810)
Location: kernel/relay.c:566
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8113d810-ffffffff8113daa1: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81146010)
Location: kernel/relay.c:577
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81146010-ffffffff811462a8: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8114fd50)
Location: kernel/relay.c:560
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8114fd50-ffffffff8115000a: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81152360)
Location: kernel/relay.c:560
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81152360-ffffffff81152628: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8115ebd0)
Location: kernel/relay.c:560
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8115ebd0-ffffffff8115ee6d: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8116d9b0)
Location: kernel/relay.c:561
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8116d9b0-ffffffff8116dc33: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8117b3f0)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8117b3f0-ffffffff8117b676: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81188300)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81188300-ffffffff81188587: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81194240)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81194240-ffffffff811944c7: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811a9240)
Location: kernel/relay.c:564
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff811a9240-ffffffff811a9502: relay_open.part.0 (STB_LOCAL)
ffffffff811a9510-ffffffff811a9549: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811a6940)
Location: kernel/relay.c:477
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff811a6940-ffffffff811a6b6e: relay_open.part.0 (STB_LOCAL)
ffffffff811a6b70-ffffffff811a6ba2: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811a7480)
Location: kernel/relay.c:477
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff811a7480-ffffffff811a76ab: relay_open.part.0 (STB_LOCAL)
ffffffff811a76b0-ffffffff811a76e2: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/relay.c (ffffffff811d0d30)
Location: kernel/relay.c:477
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff811d0d30-ffffffff811d0fa5: relay_open.part.0 (STB_LOCAL)
ffffffff811d0fb0-ffffffff811d0fe2: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff812051f0)
Location: kernel/relay.c:477
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff812051f0-ffffffff81205533: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8124d300)
Location: kernel/relay.c:474
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8124d300-ffffffff8124d617: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81264680)
Location: kernel/relay.c:474
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81264680-ffffffff81264997: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, const struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8127e470)
Location: kernel/relay.c:474
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8127e470-ffffffff8127e7be: relay_open (STB_GLOBAL)
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
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffff80001020bd28)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffff80001020bd28-ffff80001020c018: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (c044acfc)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
c044acfc-c044af78: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (c000000000289d40)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
c000000000289d40-c00000000028a108: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffe00016d728)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffe00016d728-ffffffe00016d990: relay_open (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8118c860)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8118c860-ffffffff8118cae7: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8117f940)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8117f940-ffffffff8117fbc7: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff8118a630)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8118a630-ffffffff8118a8b7: relay_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct rchan *relay_open(const char *base_filename, struct dentry *parent, size_t subbuf_size, size_t n_subbufs, struct rchan_callbacks *cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/relay.c (ffffffff81197fa0)
Location: kernel/relay.c:563
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81197fa0-ffffffff81198227: relay_open (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rchan_callbacks *cb</code> ➡️ <code>const struct rchan_callbacks *cb</code>
</li>
</ul>
</details>
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
