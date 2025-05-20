# Function: <code>devlink_region_create</code>

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
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194a6b0)
Location: net/core/devlink.c:6695
Inline: False
```
**Symbols:**

```
ffffffff8194a6b0-ffffffff8194a79a: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819809a0)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
ffffffff819809a0-ffffffff81980a8a: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a584c0)
Location: net/core/devlink.c:8338
Inline: False
```
**Symbols:**

```
ffffffff81a584c0-ffffffff81a5860c: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60300)
Location: net/core/devlink.c:9226
Inline: False
```
**Symbols:**

```
ffffffff81a60300-ffffffff81a6044c: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a42350)
Location: net/core/devlink.c:9489
Inline: False
```
**Symbols:**

```
ffffffff81a42350-ffffffff81a4249c: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afaa10)
Location: net/core/devlink.c:10431
Inline: False
```
**Symbols:**

```
ffffffff81afaa10-ffffffff81afab4e: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7f540)
Location: net/core/devlink.c:11023
Inline: False
```
**Symbols:**

```
ffffffff81c7f540-ffffffff81c7f68a: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e386b0)
Location: net/core/devlink.c:11848
Inline: False
```
**Symbols:**

```
ffffffff81e386b0-ffffffff81e38713: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82039820)
Location: net/devlink/leftover.c:8443
Inline: False
```
**Symbols:**

```
ffffffff82039820-ffffffff82039875: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const struct devlink_region_ops *ops, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/region.c (ffffffff82110450)
Location: net/devlink/region.c:1089
Inline: False
```
**Symbols:**

```
ffffffff82110450-ffffffff821104a5: devlink_region_create (STB_GLOBAL)
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
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c28a50)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
ffff800010c28a50-ffff800010c28b3c: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3fcbc)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
c0d3fcbc-c0d3fd90: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1cd20)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
c000000000d1cd20-c000000000d1ce78: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a033e)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
ffffffe0007a033e-ffffffe0007a0406: devlink_region_create (STB_GLOBAL)
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
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81920810)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
ffffffff81920810-ffffffff819208fa: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818da5c0)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
ffffffff818da5c0-ffffffff818da6aa: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819719a0)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
ffffffff819719a0-ffffffff81971a8a: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_region *devlink_region_create(struct devlink *devlink, const char *region_name, u32 region_max_snapshots, u64 region_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81993e90)
Location: net/core/devlink.c:7392
Inline: False
```
**Symbols:**

```
ffffffff81993e90-ffffffff81993f7a: devlink_region_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct devlink_region_ops *ops</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *region_name</code>
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
