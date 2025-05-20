# Function: <code>sync_timeline_put</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8162c75c)
Location: drivers/dma-buf/sw_sync.c:123
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sync_timeline_put(struct sync_timeline *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816417e0)
Location: drivers/dma-buf/sw_sync.c:123
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffffffff816417e0-ffffffff81641804: sync_timeline_put (STB_LOCAL)
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
In drivers/dma-buf/sw_sync.c (ffffffff816aaa37)
Location: drivers/dma-buf/sw_sync.c:123
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff816e6fe4)
Location: drivers/dma-buf/sw_sync.c:123
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8170a2a4)
Location: drivers/dma-buf/sw_sync.c:123
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff81745af5)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff81769fe2)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8182bae1)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8183cca1)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff818200c1)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff818aa781)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff819f4888)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff81b71da8)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff81bc54f8)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff81c1a058)
Location: drivers/dma-buf/sw_sync.c:135
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
void sync_timeline_put(struct sync_timeline *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffff80001096ade0)
Location: drivers/dma-buf/sw_sync.c:114
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
ffff80001096ade0-ffff80001096ae24: sync_timeline_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_timeline_put(struct sync_timeline *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (c0a40da0)
Location: drivers/dma-buf/sw_sync.c:114
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
c0a40da0-c0a40dd8: sync_timeline_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_timeline_put(struct sync_timeline *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (c000000000a23730)
Location: drivers/dma-buf/sw_sync.c:114
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
**Symbols:**

```
c000000000a23730-c000000000a237a0: sync_timeline_put (STB_LOCAL)
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
In drivers/dma-buf/sw_sync.c (ffffffe0005d6a50)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8171e6d2)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff816f7b1c)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff8175d4a2)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
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
In drivers/dma-buf/sw_sync.c (ffffffff81778b35)
Location: drivers/dma-buf/sw_sync.c:114
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
