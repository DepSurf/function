# Function: <code>dma_fence_wait_timeout</code>

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
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81629030)
Location: drivers/dma-buf/dma-fence.c:157
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff81629030-ffffffff8162911d: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8163eae0)
Location: drivers/dma-buf/dma-fence.c:154
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff8163eae0-ffffffff8163ebc3: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816a7800)
Location: drivers/dma-buf/dma-fence.c:153
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff816a7800-ffffffff816a78ef: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816e3800)
Location: drivers/dma-buf/dma-fence.c:153
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff816e3800-ffffffff816e38ee: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81707420)
Location: drivers/dma-buf/dma-fence.c:227
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff81707420-ffffffff81707524: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-fence.c (0)
Location: drivers/dma-buf/dma-fence.c:220
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff81742f99-ffffffff81742fb3: dma_fence_wait_timeout.cold (STB_LOCAL)
ffffffff817426a0-ffffffff8174278f: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff817666a0)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff817666a0-ffffffff8176679d: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81826ef0)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff81826ef0-ffffffff81826ff5: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818378c0)
Location: drivers/dma-buf/dma-fence.c:410
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff818378c0-ffffffff81837995: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181ae10)
Location: drivers/dma-buf/dma-fence.c:491
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff8181ae10-ffffffff8181aee5: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a52a0)
Location: drivers/dma-buf/dma-fence.c:491
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
```
**Symbols:**

```
ffffffff818a52a0-ffffffff818a536f: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819eee90)
Location: drivers/dma-buf/dma-fence.c:492
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
```
**Symbols:**

```
ffffffff819eee90-ffffffff819eefa5: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c390)
Location: drivers/dma-buf/dma-fence.c:500
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
```
**Symbols:**

```
ffffffff81b6c390-ffffffff81b6c4cd: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfe10)
Location: drivers/dma-buf/dma-fence.c:501
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
```
**Symbols:**

```
ffffffff81bbfe10-ffffffff81bbff4d: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c14590)
Location: drivers/dma-buf/dma-fence.c:501
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences
```
**Symbols:**

```
ffffffff81c14590-ffffffff81c146cd: dma_fence_wait_timeout (STB_GLOBAL)
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
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffff800010967818)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffff800010967818-ffff800010967984: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c0a3d778)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
c0a3d778-c0a3d8e8: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (c000000000a1e8b0)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
c000000000a1e8b0-c000000000a1ea60: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffe0005d349a)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffe0005d349a-ffffffe0005d35a0: dma_fence_wait_timeout (STB_GLOBAL)
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
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8171ad90)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff8171ad90-ffffffff8171ae8d: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff816f41f0)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff816f41f0-ffffffff816f42ed: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81759b60)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff81759b60-ffffffff81759c5d: dma_fence_wait_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int dma_fence_wait_timeout(struct dma_fence *fence, bool intr, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff817750a0)
Location: drivers/dma-buf/dma-fence.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
```
**Symbols:**

```
ffffffff817750a0-ffffffff817751c7: dma_fence_wait_timeout (STB_GLOBAL)
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
