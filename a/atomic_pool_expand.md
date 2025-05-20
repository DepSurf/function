# Function: <code>atomic_pool_expand</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113f670)
Location: kernel/dma/pool.c:83
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff8113f670-ffffffff8113f7d5: atomic_pool_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113ac50)
Location: kernel/dma/pool.c:79
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff8113ac50-ffffffff8113adc3: atomic_pool_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/pool.c (ffffffff8113bf80)
Location: kernel/dma/pool.c:79
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff8113bf80-ffffffff8113c0f2: atomic_pool_expand (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/pool.c (0)
Location: kernel/dma/pool.c:79
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff8115f090-ffffffff8115f21f: atomic_pool_expand (STB_LOCAL)
ffffffff81cb06cb-ffffffff81cb074d: atomic_pool_expand.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/pool.c (0)
Location: kernel/dma/pool.c:79
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff811892a0-ffffffff81189473: atomic_pool_expand (STB_LOCAL)
ffffffff81e613ca-ffffffff81e61447: atomic_pool_expand.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/pool.c (0)
Location: kernel/dma/pool.c:79
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff811c56a0-ffffffff811c5873: atomic_pool_expand (STB_LOCAL)
ffffffff8205aa5f-ffffffff8205aadc: atomic_pool_expand.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/pool.c (0)
Location: kernel/dma/pool.c:79
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff811d8280-ffffffff811d8421: atomic_pool_expand (STB_LOCAL)
ffffffff820d92c6-ffffffff820d934e: atomic_pool_expand.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int atomic_pool_expand(struct gen_pool *pool, size_t pool_size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/pool.c (0)
Location: kernel/dma/pool.c:79
Inline: False
Direct callers:
  - kernel/dma/pool.c:__dma_atomic_pool_init
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
  - kernel/dma/pool.c:atomic_pool_work_fn
```
**Symbols:**

```
ffffffff811edd70-ffffffff811edf32: atomic_pool_expand (STB_LOCAL)
ffffffff821b4b51-ffffffff821b4bcf: atomic_pool_expand.cold (STB_LOCAL)
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
