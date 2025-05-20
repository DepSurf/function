# Function: <code>dma_fence_remove_callback</code>

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
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81628ae0)
Location: drivers/dma-buf/dma-fence.c:300
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_free
```
**Symbols:**

```
ffffffff81628ae0-ffffffff81628b35: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163e690)
Location: drivers/dma-buf/dma-fence.c:324
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff8163e690-ffffffff8163e6e5: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a7510)
Location: drivers/dma-buf/dma-fence.c:323
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff816a7510-ffffffff816a7565: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e38f0)
Location: drivers/dma-buf/dma-fence.c:324
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff816e38f0-ffffffff816e3945: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81706ba0)
Location: drivers/dma-buf/dma-fence.c:420
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81706ba0-ffffffff81706bf5: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81741d70)
Location: drivers/dma-buf/dma-fence.c:430
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81741d70-ffffffff81741dc5: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81765dc0)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81765dc0-ffffffff81765e13: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818272dd)
Location: drivers/dma-buf/dma-fence.c:420
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81826350-ffffffff818263a3: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81837d7d)
Location: drivers/dma-buf/dma-fence.c:630
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81836e90-ffffffff81836ee3: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181b068)
Location: drivers/dma-buf/dma-fence.c:711
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff8181a050-ffffffff8181a0a3: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a54e8)
Location: drivers/dma-buf/dma-fence.c:711
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff818a4500-ffffffff818a4553: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819ef103)
Location: drivers/dma-buf/dma-fence.c:709
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff819ede50-ffffffff819edead: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c633)
Location: drivers/dma-buf/dma-fence.c:716
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81b6b220-ffffffff81b6b27d: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfcc3)
Location: drivers/dma-buf/dma-fence.c:717
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81bbe690-ffffffff81bbe6ed: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c14443)
Location: drivers/dma-buf/dma-fence.c:717
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81c12de0-ffffffff81c12e3d: dma_fence_remove_callback (STB_GLOBAL)
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
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff800010966d50)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffff800010966d50-ffff800010966e18: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3cb6c)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
c0a3cb6c-c0a3cbc8: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1d840)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
c000000000a1d840-c000000000a1d8dc: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2c80)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffe0005d2c80-ffffffe0005d2ce0: dma_fence_remove_callback (STB_GLOBAL)
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
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171a4b0)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff8171a4b0-ffffffff8171a503: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f3910)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff816f3910-ffffffff816f3963: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81759280)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81759280-ffffffff817592d3: dma_fence_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dma_fence_remove_callback(struct dma_fence *fence, struct dma_fence_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81774760)
Location: drivers/dma-buf/dma-fence.c:415
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/sync_file.c:sync_file_release
```
**Symbols:**

```
ffffffff81774760-ffffffff817747b3: dma_fence_remove_callback (STB_GLOBAL)
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
