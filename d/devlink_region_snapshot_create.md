# Function: <code>devlink_region_snapshot_create</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u64 data_len, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194a840)
Location: net/core/devlink.c:6792
Inline: False
```
**Symbols:**

```
ffffffff8194a840-ffffffff8194a93f: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81980b30)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
ffffffff81980b30-ffffffff81980c27: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a58460)
Location: net/core/devlink.c:8459
Inline: False
```
**Symbols:**

```
ffffffff81a58460-ffffffff81a584b2: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a602a0)
Location: net/core/devlink.c:9398
Inline: False
```
**Symbols:**

```
ffffffff81a602a0-ffffffff81a602f2: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a422f0)
Location: net/core/devlink.c:9661
Inline: False
```
**Symbols:**

```
ffffffff81a422f0-ffffffff81a42342: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afa9b0)
Location: net/core/devlink.c:10603
Inline: False
```
**Symbols:**

```
ffffffff81afa9b0-ffffffff81afaa02: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7f4e0)
Location: net/core/devlink.c:11195
Inline: False
```
**Symbols:**

```
ffffffff81c7f4e0-ffffffff81c7f53a: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e383e0)
Location: net/core/devlink.c:12010
Inline: False
```
**Symbols:**

```
ffffffff81e383e0-ffffffff81e38432: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82039300)
Location: net/devlink/leftover.c:8605
Inline: False
```
**Symbols:**

```
ffffffff82039300-ffffffff82039352: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff821100a0)
Location: net/devlink/region.c:1251
Inline: False
```
**Symbols:**

```
ffffffff821100a0-ffffffff821100f2: devlink_region_snapshot_create (STB_GLOBAL)
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
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c28be8)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
ffff800010c28be8-ffff800010c28d0c: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3fe28)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
c0d3fe28-c0d3ff2c: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1cf80)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
c000000000d1cf80-c000000000d1d10c: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a04a4)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
ffffffe0007a04a4-ffffffe0007a0590: devlink_region_snapshot_create (STB_GLOBAL)
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
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819209a0)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
ffffffff819209a0-ffffffff81920a97: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818da750)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
ffffffff818da750-ffffffff818da847: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81971b30)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
ffffffff81971b30-ffffffff81971c27: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_region_snapshot_create(struct devlink_region *region, u8 *data, u32 snapshot_id, devlink_snapshot_data_dest_t *data_destructor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81994020)
Location: net/core/devlink.c:7488
Inline: False
```
**Symbols:**

```
ffffffff81994020-ffffffff81994117: devlink_region_snapshot_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 data_len</code>
</li>
<li>
<b>Param reordered. </b>
<code>region, data_len, data, snapshot_id, data_destructor</code> ➡️ <code>region, data, snapshot_id, data_destructor</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>devlink_snapshot_data_dest_t *data_destructor</code>
</li>
</ul>
</details>
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
