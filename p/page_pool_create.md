# Function: <code>page_pool_create</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818bd890)
Location: net/core/page_pool.c:49
Inline: False
```
**Symbols:**

```
ffffffff818bd890-ffffffff818bda06: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818e4be0)
Location: net/core/page_pool.c:49
Inline: False
```
**Symbols:**

```
ffffffff818e4be0-ffffffff818e4d58: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81934430)
Location: net/core/page_pool.c:61
Inline: False
```
**Symbols:**

```
ffffffff81934430-ffffffff819345f3: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81967060)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
ffffffff81967060-ffffffff81967223: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:81
Inline: False
```
**Symbols:**

```
ffffffff81a3b2f9-ffffffff81a3b31e: page_pool_create.cold (STB_LOCAL)
ffffffff81a3a520-ffffffff81a3a580: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:83
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_page_pool
```
**Symbols:**

```
ffffffff81c317b1-ffffffff81c317d6: page_pool_create.cold (STB_LOCAL)
ffffffff81a3cab0-ffffffff81a3cb10: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a23890)
Location: net/core/page_pool.c:83
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81a23890-ffffffff81a23a2f: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad7ec0)
Location: net/core/page_pool.c:90
Inline: False
```
**Symbols:**

```
ffffffff81ad7ec0-ffffffff81ad805f: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:203
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81f041b6-ffffffff81f041db: page_pool_create.cold (STB_LOCAL)
ffffffff81c58db0-ffffffff81c58e13: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e0ecb0)
Location: net/core/page_pool.c:203
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e0ecb0-ffffffff81e0ed43: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e82330)
Location: net/core/page_pool.c:227
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e82330-ffffffff81e823c3: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f43320)
Location: net/core/page_pool.c:259
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81f43320-ffffffff81f4341e: page_pool_create (STB_GLOBAL)
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
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0c700)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
ffff800010c0c700-ffff800010c0c884: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d24da4)
Location: net/core/page_pool.c:64
Inline: False
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_create_xdp_rxqs
```
**Symbols:**

```
c0d24da4-c0d24f2c: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf7de0)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
c000000000cf7de0-c000000000cf7ffc: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789ab4)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
ffffffe000789ab4-ffffffe000789bdc: page_pool_create (STB_GLOBAL)
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
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81907030)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
ffffffff81907030-ffffffff819071f3: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c0e40)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
ffffffff818c0e40-ffffffff818c1003: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81958060)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
ffffffff81958060-ffffffff81958223: page_pool_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page_pool *page_pool_create(const struct page_pool_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8197a170)
Location: net/core/page_pool.c:64
Inline: False
```
**Symbols:**

```
ffffffff8197a170-ffffffff8197a333: page_pool_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
