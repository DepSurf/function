# Function: <code>signalfd_dequeue</code>

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
In fs/signalfd.c (ffffffff8125737d)
Location: fs/signalfd.c:159
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff8127fc7d)
Location: fs/signalfd.c:159
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff812937ed)
Location: fs/signalfd.c:159
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff812a0ad8)
Location: fs/signalfd.c:159
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff812c3e4e)
Location: fs/signalfd.c:154
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff812ed0f5)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff81301e4f)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff813233ea)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff8133614a)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8136fe10)
Location: fs/signalfd.c:166
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8136fe10-ffffffff8136ff9b: signalfd_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8137db70)
Location: fs/signalfd.c:166
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8137db70-ffffffff8137dd05: signalfd_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff813847f0)
Location: fs/signalfd.c:165
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff813847f0-ffffffff81384982: signalfd_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff813d1a90)
Location: fs/signalfd.c:155
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff813d1a90-ffffffff813d1c11: signalfd_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8145aaf0)
Location: fs/signalfd.c:155
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8145aaf0-ffffffff8145ac71: signalfd_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff814ea080)
Location: fs/signalfd.c:155
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff814ea080-ffffffff814ea201: signalfd_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81520e20)
Location: fs/signalfd.c:155
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81520e20-ffffffff81520fa1: signalfd_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t signalfd_dequeue(struct signalfd_ctx *ctx, kernel_siginfo_t *info, int nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81555460)
Location: fs/signalfd.c:155
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81555460-ffffffff815555e1: signalfd_dequeue (STB_LOCAL)
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
In fs/signalfd.c (ffff8000103f3f38)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (c05c8dec)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (c0000000004fbb88)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffe0002a5144)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff8132e72a)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff8131f384)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff8132c1fa)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
In fs/signalfd.c (ffffffff8133e76e)
Location: fs/signalfd.c:166
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
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
