# Function: <code>__dma_fence_enable_signaling</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818269a0)
Location: drivers/dma-buf/dma-fence.c:276
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
```
**Symbols:**

```
ffffffff818269a0-ffffffff81826a26: __dma_fence_enable_signaling.part.0 (STB_LOCAL)
ffffffff81826a30-ffffffff81826a6b: __dma_fence_enable_signaling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818374b0)
Location: drivers/dma-buf/dma-fence.c:486
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
```
**Symbols:**

```
ffffffff818374b0-ffffffff81837524: __dma_fence_enable_signaling.part.0 (STB_LOCAL)
ffffffff81837530-ffffffff8183756b: __dma_fence_enable_signaling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181aa80)
Location: drivers/dma-buf/dma-fence.c:567
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
```
**Symbols:**

```
ffffffff8181aa80-ffffffff8181ab21: __dma_fence_enable_signaling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a4f20)
Location: drivers/dma-buf/dma-fence.c:567
Inline: True
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
```
**Symbols:**

```
ffffffff818a4f20-ffffffff818a4fbe: __dma_fence_enable_signaling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819eea60)
Location: drivers/dma-buf/dma-fence.c:568
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
```
**Symbols:**

```
ffffffff819eea60-ffffffff819eeb34: __dma_fence_enable_signaling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c170)
Location: drivers/dma-buf/dma-fence.c:578
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
```
**Symbols:**

```
ffffffff81b6c170-ffffffff81b6c244: __dma_fence_enable_signaling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf950)
Location: drivers/dma-buf/dma-fence.c:579
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
```
**Symbols:**

```
ffffffff81bbf950-ffffffff81bbfa24: __dma_fence_enable_signaling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __dma_fence_enable_signaling(struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c140d0)
Location: drivers/dma-buf/dma-fence.c:579
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
```
**Symbols:**

```
ffffffff81c140d0-ffffffff81c141a4: __dma_fence_enable_signaling (STB_LOCAL)
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
