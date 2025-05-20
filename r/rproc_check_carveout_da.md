# Function: <code>rproc_check_carveout_da</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:282
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff818f3fb0-ffffffff818f3ff5: rproc_check_carveout_da.isra.0 (STB_LOCAL)
ffffffff818f556a-ffffffff818f55af: rproc_check_carveout_da.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:286
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff819c9050-ffffffff819c909d: rproc_check_carveout_da (STB_LOCAL)
ffffffff819cb005-ffffffff819cb04a: rproc_check_carveout_da.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:286
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff819c8bf0-ffffffff819c8c3d: rproc_check_carveout_da (STB_LOCAL)
ffffffff81c2ddc5-ffffffff81c2de0a: rproc_check_carveout_da.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:289
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff819adb40-ffffffff819adb8d: rproc_check_carveout_da (STB_LOCAL)
ffffffff81c1ff38-ffffffff81c1ff7d: rproc_check_carveout_da.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:291
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81a5c0a0-ffffffff81a5c0ed: rproc_check_carveout_da (STB_LOCAL)
ffffffff81d3189a-ffffffff81d318df: rproc_check_carveout_da.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:291
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81bcc040-ffffffff81bcc09e: rproc_check_carveout_da (STB_LOCAL)
ffffffff81efdd71-ffffffff81efdda4: rproc_check_carveout_da.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d75c10)
Location: drivers/remoteproc/remoteproc_core.c:290
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81d75c10-ffffffff81d75c7c: rproc_check_carveout_da (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de3b50)
Location: drivers/remoteproc/remoteproc_core.c:290
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81de3b50-ffffffff81de3bbc: rproc_check_carveout_da (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e99c40)
Location: drivers/remoteproc/remoteproc_core.c:290
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81e99c40-ffffffff81e99cac: rproc_check_carveout_da (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7ffd0)
Location: drivers/remoteproc/remoteproc_core.c:282
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffff800010b7ffd0-ffff800010b80084: rproc_check_carveout_da.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_check_carveout_da(struct rproc *rproc, struct rproc_mem_entry *mem, u32 da, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c62be8)
Location: drivers/remoteproc/remoteproc_core.c:282
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
c0c62be8-c0c62c6c: rproc_check_carveout_da (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5baf0)
Location: drivers/remoteproc/remoteproc_core.c:282
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
c000000000c5baf0-c000000000c5bbac: rproc_check_carveout_da.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:282
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff818952e0-ffffffff81895325: rproc_check_carveout_da.isra.0 (STB_LOCAL)
ffffffff8189689a-ffffffff818968df: rproc_check_carveout_da.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:282
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81905a40-ffffffff81905a85: rproc_check_carveout_da.isra.0 (STB_LOCAL)
ffffffff81906ffa-ffffffff8190703f: rproc_check_carveout_da.isra.0.cold (STB_LOCAL)
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
</ul>
