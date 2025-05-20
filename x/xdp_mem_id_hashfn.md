# Function: <code>xdp_mem_id_hashfn</code>

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
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818ba530)
Location: net/core/xdp.c:40
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff818ba530-ffffffff818ba540: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e13b0)
Location: net/core/xdp.c:43
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff818e13b0-ffffffff818e13bd: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8192fb90)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:__mem_id_disconnect
```
**Symbols:**

```
ffffffff8192fb90-ffffffff8192fb9d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81961e00)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff81961e00-ffffffff81961e0d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35580)
Location: net/core/xdp.c:36
Inline: False
```
**Symbols:**

```
ffffffff81a35580-ffffffff81a3558d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37910)
Location: net/core/xdp.c:36
Inline: False
```
**Symbols:**

```
ffffffff81a37910-ffffffff81a3791d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1ea70)
Location: net/core/xdp.c:36
Inline: False
```
**Symbols:**

```
ffffffff81a1ea70-ffffffff81a1ea7d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad2b10)
Location: net/core/xdp.c:36
Inline: False
```
**Symbols:**

```
ffffffff81ad2b10-ffffffff81ad2b1d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c505d0)
Location: net/core/xdp.c:36
Inline: True
```
**Symbols:**

```
ffffffff81c505d0-ffffffff81c505e3: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e059c0)
Location: net/core/xdp.c:36
Inline: True
```
**Symbols:**

```
ffffffff81e059c0-ffffffff81e059d3: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e78ab8)
Location: net/core/xdp.c:38
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
**Symbols:**

```
ffffffff81e780a0-ffffffff81e780b3: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f38988)
Location: net/core/xdp.c:38
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_unreg_mem_model
```
**Symbols:**

```
ffffffff81f38060-ffffffff81f38073: xdp_mem_id_hashfn (STB_LOCAL)
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
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c05bf0)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
**Symbols:**

```
ffff800010c05bf0-ffff800010c05c18: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1ec4c)
Location: net/core/xdp.c:34
Inline: False
```
**Symbols:**

```
c0d1ec4c-c0d1ec68: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cefef0)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
c000000000cefef0-c000000000ceff00: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000784364)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffe000784364-ffffffe000784386: xdp_mem_id_hashfn (STB_LOCAL)
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
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81901dd0)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff81901dd0-ffffffff81901ddd: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bbc00)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff818bbc00-ffffffff818bbc0d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81952e00)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_id_disconnect
```
**Symbols:**

```
ffffffff81952e00-ffffffff81952e0d: xdp_mem_id_hashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 xdp_mem_id_hashfn(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819748f0)
Location: net/core/xdp.c:34
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff819748f0-ffffffff819748fd: xdp_mem_id_hashfn (STB_LOCAL)
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
