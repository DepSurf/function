# Function: <code>blk_trace_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_trace_cleanup(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115ae70)
Location: kernel/trace/blktrace.c:303
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_shutdown
```
**Symbols:**

```
ffffffff8115ae70-ffffffff8115ae8b: blk_trace_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_trace_cleanup(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81165750)
Location: kernel/trace/blktrace.c:309
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
```
**Symbols:**

```
ffffffff81165750-ffffffff8116576b: blk_trace_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_trace_cleanup(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81170bb0)
Location: kernel/trace/blktrace.c:309
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
```
**Symbols:**

```
ffffffff81170bb0-ffffffff81170bcb: blk_trace_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_trace_cleanup(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81173c40)
Location: kernel/trace/blktrace.c:308
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
```
**Symbols:**

```
ffffffff81173c40-ffffffff81173c5b: blk_trace_cleanup (STB_LOCAL)
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
In kernel/trace/blktrace.c (ffffffff81180e3a)
Location: kernel/trace/blktrace.c:349
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff8118ffda)
Location: kernel/trace/blktrace.c:349
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff8119d7ea)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811ab52f)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811b6d21)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811d0a1c)
Location: kernel/trace/blktrace.c:339
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811cde3c)
Location: kernel/trace/blktrace.c:339
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811d0afb)
Location: kernel/trace/blktrace.c:338
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811fd74f)
Location: kernel/trace/blktrace.c:348
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff81238058)
Location: kernel/trace/blktrace.c:348
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff81284e04)
Location: kernel/trace/blktrace.c:380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff812a1a94)
Location: kernel/trace/blktrace.c:380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff812bd1c4)
Location: kernel/trace/blktrace.c:380
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_remove
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
In kernel/trace/blktrace.c (ffff800010235c5c)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (c0471ca4)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (c0000000002c0540)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffe00018c612)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811af341)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811a2191)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811ad111)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
In kernel/trace/blktrace.c (ffffffff811bafe1)
Location: kernel/trace/blktrace.c:337
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_remove
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
</ul>
