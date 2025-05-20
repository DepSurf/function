# Function: <code>sync_timeline_create</code>

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
In drivers/dma-buf/sw_sync.c (ffffffff8162c6b4)
Location: drivers/dma-buf/sw_sync.c:87
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff81641c48)
Location: drivers/dma-buf/sw_sync.c:87
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff816aa66d)
Location: drivers/dma-buf/sw_sync.c:87
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff816e6b7d)
Location: drivers/dma-buf/sw_sync.c:87
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff81709d8d)
Location: drivers/dma-buf/sw_sync.c:87
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff8174559d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff8176971d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sync_timeline *sync_timeline_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8182b970)
Location: drivers/dma-buf/sw_sync.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8182b970-ffffffff8182b9f7: sync_timeline_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sync_timeline *sync_timeline_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8183c7d0)
Location: drivers/dma-buf/sw_sync.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff8183c7d0-ffffffff8183c8f4: sync_timeline_create (STB_LOCAL)
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
In drivers/dma-buf/sw_sync.c (ffffffff8181fb1d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff818aa1dd)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff819f4a0d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff81b71e6d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sync_timeline *sync_timeline_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5570)
Location: drivers/dma-buf/sw_sync.c:78
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81bc5570-ffffffff81bc5637: sync_timeline_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sync_timeline *sync_timeline_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81c19d60)
Location: drivers/dma-buf/sw_sync.c:99
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
**Symbols:**

```
ffffffff81c19d60-ffffffff81c19e56: sync_timeline_create (STB_LOCAL)
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
In drivers/dma-buf/sw_sync.c (ffff80001096ae64)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (c0a40e24)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (c000000000a23c18)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffe0005d63e4)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff8171de0d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff816f726d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff8175cbdd)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
In drivers/dma-buf/sw_sync.c (ffffffff8177827d)
Location: drivers/dma-buf/sw_sync.c:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
