# Function: <code>dma_fence_signal_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81629160)
Location: drivers/dma-buf/dma-fence.c:66
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81629160-ffffffff81629263: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163ece0)
Location: drivers/dma-buf/dma-fence.c:68
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff8163ece0-ffffffff8163edcc: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a7aa0)
Location: drivers/dma-buf/dma-fence.c:67
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff816a7aa0-ffffffff816a7b92: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e3b80)
Location: drivers/dma-buf/dma-fence.c:67
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff816e3b80-ffffffff816e3c73: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81707020)
Location: drivers/dma-buf/dma-fence.c:136
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81707020-ffffffff81707113: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence.c (0)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81742f80-ffffffff81742f99: dma_fence_signal_locked.cold (STB_LOCAL)
ffffffff81742190-ffffffff81742268: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81765ec0)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81765ec0-ffffffff81765fbe: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81826850)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81826850-ffffffff8182694e: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81837370)
Location: drivers/dma-buf/dma-fence.c:330
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81837370-ffffffff8183745c: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181a7e5)
Location: drivers/dma-buf/dma-fence.c:432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff8181a660-ffffffff8181a684: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a4c85)
Location: drivers/dma-buf/dma-fence.c:432
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff818a4ba0-ffffffff818a4bc4: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819ee8bd)
Location: drivers/dma-buf/dma-fence.c:433
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff819ee550-ffffffff819ee57b: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6bfad)
Location: drivers/dma-buf/dma-fence.c:441
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81b6b9d0-ffffffff81b6b9fb: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf43d)
Location: drivers/dma-buf/dma-fence.c:442
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81bbeef0-ffffffff81bbef1b: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c13bbd)
Location: drivers/dma-buf/dma-fence.c:442
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81c13640-ffffffff81c1366b: dma_fence_signal_locked (STB_GLOBAL)
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
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff8000109667a8)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffff8000109667a8-ffff800010966924: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3ced0)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
c0a3ced0-c0a3d03c: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1da20)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
c000000000a1da20-c000000000a1dbe0: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2e06)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffe0005d2e06-ffffffe0005d2ef2: dma_fence_signal_locked (STB_GLOBAL)
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
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171a5b0)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff8171a5b0-ffffffff8171a6ae: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f3a10)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff816f3a10-ffffffff816f3b0e: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81759380)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81759380-ffffffff8175947e: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_fence_signal_locked(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81774860)
Location: drivers/dma-buf/dma-fence.c:129
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
**Symbols:**

```
ffffffff81774860-ffffffff81774977: dma_fence_signal_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
