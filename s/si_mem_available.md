# Function: <code>si_mem_available</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a62b0)
Location: mm/page_alloc.c:4006
Inline: False
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811a62b0-ffffffff811a6386: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b6630)
Location: mm/page_alloc.c:4162
Inline: False
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811b6630-ffffffff811b6706: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811be4f0)
Location: mm/page_alloc.c:4450
Inline: False
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811be4f0-ffffffff811be5c6: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3260)
Location: mm/page_alloc.c:4569
Inline: False
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811d3260-ffffffff811d3336: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f45a0)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811f45a0-ffffffff811f4687: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812069f0)
Location: mm/page_alloc.c:4872
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff812069f0-ffffffff81206abd: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126ca20)
Location: mm/page_alloc.c:5058
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8126ca20-ffffffff8126caf9: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127b830)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8127b830-ffffffff8127b909: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ad960)
Location: mm/page_alloc.c:5179
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff812ad960-ffffffff812ada45: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b9320)
Location: mm/page_alloc.c:5345
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff812b9320-ffffffff812b9405: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812be7f0)
Location: mm/page_alloc.c:5548
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff812be7f0-ffffffff812be8d7: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81301100)
Location: mm/page_alloc.c:5729
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81301100-ffffffff81301239: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813686f0)
Location: mm/page_alloc.c:5784
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff813686f0-ffffffff8136885d: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e49b0)
Location: mm/page_alloc.c:5927
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff813e49b0-ffffffff813e4b1d: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/show_mem.c (ffffffff813dd8c0)
Location: mm/show_mem.c:32
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff813dd8c0-ffffffff813dda2d: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/show_mem.c (ffffffff81407830)
Location: mm/show_mem.c:32
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81407830-ffffffff81407900: si_mem_available (STB_GLOBAL)
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
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010312d78)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffff800010312d78-ffff800010312e58: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052dc0c)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
c052dc0c-c052dce4: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e3f80)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
c0000000003e3f80-c0000000003e40c8: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a31e)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffe00021a31e-ffffffe00021a3f0: si_mem_available (STB_GLOBAL)
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
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273e80)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81273e80-ffffffff81273f59: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81265df0)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff81265df0-ffffffff81265ec9: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81271c20)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81271c20-ffffffff81271cf9: si_mem_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int si_mem_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281680)
Location: mm/page_alloc.c:5076
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - fs/proc/meminfo.c:meminfo_proc_show
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81281680-ffffffff81281759: si_mem_available (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
