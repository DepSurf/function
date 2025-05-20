# Function: <code>dma_fence_signal_timestamp_locked</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_fence_signal_timestamp_locked(struct dma_fence *fence, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181a520)
Location: drivers/dma-buf/dma-fence.c:357
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
**Symbols:**

```
ffffffff8181a520-ffffffff8181a604: dma_fence_signal_timestamp_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_fence_signal_timestamp_locked(struct dma_fence *fence, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a4a60)
Location: drivers/dma-buf/dma-fence.c:357
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
**Symbols:**

```
ffffffff818a4a60-ffffffff818a4b41: dma_fence_signal_timestamp_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_fence_signal_timestamp_locked(struct dma_fence *fence, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819ee3d0)
Location: drivers/dma-buf/dma-fence.c:358
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
**Symbols:**

```
ffffffff819ee3d0-ffffffff819ee4e7: dma_fence_signal_timestamp_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_fence_signal_timestamp_locked(struct dma_fence *fence, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6b830)
Location: drivers/dma-buf/dma-fence.c:366
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
**Symbols:**

```
ffffffff81b6b830-ffffffff81b6b947: dma_fence_signal_timestamp_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_fence_signal_timestamp_locked(struct dma_fence *fence, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbed50)
Location: drivers/dma-buf/dma-fence.c:367
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
**Symbols:**

```
ffffffff81bbed50-ffffffff81bbee67: dma_fence_signal_timestamp_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_fence_signal_timestamp_locked(struct dma_fence *fence, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c134a0)
Location: drivers/dma-buf/dma-fence.c:367
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
**Symbols:**

```
ffffffff81c134a0-ffffffff81c135b7: dma_fence_signal_timestamp_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
