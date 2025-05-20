# Function: <code>eventfd_ctx_remove_wait_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81259000)
Location: fs/eventfd.c:156
Inline: False
```
**Symbols:**

```
ffffffff81259000-ffffffff812590bc: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812819e0)
Location: fs/eventfd.c:194
Inline: False
```
**Symbols:**

```
ffffffff812819e0-ffffffff81281a9f: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81295510)
Location: fs/eventfd.c:194
Inline: False
```
**Symbols:**

```
ffffffff81295510-ffffffff812955cf: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812a27d0)
Location: fs/eventfd.c:194
Inline: False
```
**Symbols:**

```
ffffffff812a27d0-ffffffff812a288f: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812c5ae0)
Location: fs/eventfd.c:194
Inline: False
```
**Symbols:**

```
ffffffff812c5ae0-ffffffff812c5b9f: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812eed10)
Location: fs/eventfd.c:181
Inline: False
```
**Symbols:**

```
ffffffff812eed10-ffffffff812eedc2: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813036a0)
Location: fs/eventfd.c:181
Inline: False
```
**Symbols:**

```
ffffffff813036a0-ffffffff81303752: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81324c10)
Location: fs/eventfd.c:188
Inline: False
```
**Symbols:**

```
ffffffff81324c10-ffffffff81324cc0: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813379a0)
Location: fs/eventfd.c:203
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff813379a0-ffffffff81337a50: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813715b0)
Location: fs/eventfd.c:204
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff813715b0-ffffffff81371660: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8137f370)
Location: fs/eventfd.c:207
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff8137f370-ffffffff8137f420: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81385ff0)
Location: fs/eventfd.c:207
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff81385ff0-ffffffff813860a0: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813d32c0)
Location: fs/eventfd.c:205
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff813d32c0-ffffffff813d3370: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8145c800)
Location: fs/eventfd.c:205
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff8145c800-ffffffff8145c8ba: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff814ebeb0)
Location: fs/eventfd.c:210
Inline: False
```
**Symbols:**

```
ffffffff814ebeb0-ffffffff814ebf6a: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81522c50)
Location: fs/eventfd.c:210
Inline: False
```
**Symbols:**

```
ffffffff81522c50-ffffffff81522d10: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81557350)
Location: fs/eventfd.c:198
Inline: False
```
**Symbols:**

```
ffffffff81557350-ffffffff81557410: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
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
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffff8000103f5fe0)
Location: fs/eventfd.c:203
Inline: False
Direct callers:
  - virt/kvm/eventfd.c:irqfd_shutdown
```
**Symbols:**

```
ffff8000103f5fe0-ffff8000103f610c: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c05ca698)
Location: fs/eventfd.c:203
Inline: False
```
**Symbols:**

```
c05ca698-c05ca764: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (c0000000004fdb60)
Location: fs/eventfd.c:203
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
c0000000004fdb60-c0000000004fdc98: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffe0002a64ec)
Location: fs/eventfd.c:203
Inline: False
```
**Symbols:**

```
ffffffe0002a64ec-ffffffe0002a6594: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
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
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8132ff80)
Location: fs/eventfd.c:203
Inline: False
```
**Symbols:**

```
ffffffff8132ff80-ffffffff81330030: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81320ba0)
Location: fs/eventfd.c:203
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff81320ba0-ffffffff81320c50: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff8132da50)
Location: fs/eventfd.c:203
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff8132da50-ffffffff8132db00: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int eventfd_ctx_remove_wait_queue(struct eventfd_ctx *ctx, wait_queue_entry_t *wait, __u64 *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff813403c0)
Location: fs/eventfd.c:203
Inline: False
Direct callers:
  - drivers/vfio/virqfd.c:virqfd_shutdown
```
**Symbols:**

```
ffffffff813403c0-ffffffff81340470: eventfd_ctx_remove_wait_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>wait_queue_t *wait</code> ➡️ <code>wait_queue_entry_t *wait</code>
</li>
</ul>
</details>
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
