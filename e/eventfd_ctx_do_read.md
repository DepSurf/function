# Function: <code>eventfd_ctx_do_read</code>

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
In fs/eventfd.c (ffffffff81259029)
Location: fs/eventfd.c:137
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_ctx_read
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
In fs/eventfd.c (ffffffff81282176)
Location: fs/eventfd.c:175
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff81295ca4)
Location: fs/eventfd.c:175
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff812a2e50)
Location: fs/eventfd.c:175
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff812c61df)
Location: fs/eventfd.c:175
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff812ef3b7)
Location: fs/eventfd.c:162
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff81303d47)
Location: fs/eventfd.c:162
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff813252d7)
Location: fs/eventfd.c:169
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff81338067)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff81371dca)
Location: fs/eventfd.c:185
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_do_read(struct eventfd_ctx *ctx, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8137fbc2)
Location: fs/eventfd.c:185
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
**Symbols:**

```
ffffffff8137f290-ffffffff8137f2b1: eventfd_ctx_do_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_do_read(struct eventfd_ctx *ctx, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81386842)
Location: fs/eventfd.c:185
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
**Symbols:**

```
ffffffff81385f10-ffffffff81385f31: eventfd_ctx_do_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_do_read(struct eventfd_ctx *ctx, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813d3ad2)
Location: fs/eventfd.c:183
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
**Symbols:**

```
ffffffff813d31d0-ffffffff813d31f1: eventfd_ctx_do_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_do_read(struct eventfd_ctx *ctx, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8145d0a2)
Location: fs/eventfd.c:183
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
**Symbols:**

```
ffffffff8145c700-ffffffff8145c72b: eventfd_ctx_do_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_do_read(struct eventfd_ctx *ctx, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff814ec842)
Location: fs/eventfd.c:188
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
**Symbols:**

```
ffffffff814ebe70-ffffffff814ebe9b: eventfd_ctx_do_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_do_read(struct eventfd_ctx *ctx, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81522e71)
Location: fs/eventfd.c:188
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
**Symbols:**

```
ffffffff81522c10-ffffffff81522c3f: eventfd_ctx_do_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void eventfd_ctx_do_read(struct eventfd_ctx *ctx, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81557571)
Location: fs/eventfd.c:176
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
**Symbols:**

```
ffffffff81557230-ffffffff8155725f: eventfd_ctx_do_read (STB_GLOBAL)
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
In fs/eventfd.c (ffff8000103f6790)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (c05ca958)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (c0000000004fe2bc)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffe0002a6942)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff81330647)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff81321247)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff8132e117)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
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
In fs/eventfd.c (ffffffff813405c3)
Location: fs/eventfd.c:184
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
