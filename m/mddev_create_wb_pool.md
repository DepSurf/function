# Function: <code>mddev_create_wb_pool</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81861ac2)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff8186e6b9-ffffffff8186e6ca: mddev_create_wb_pool.cold (STB_LOCAL)
ffffffff81861a60-ffffffff81861b51: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff818936f2)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff818a04b9-ffffffff818a04ca: mddev_create_wb_pool.cold (STB_LOCAL)
ffffffff81893690-ffffffff81893781: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae9fa0)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffff800010ae9fa0-ffff800010aea0cc: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bcbf94)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
c0bcbf94-c0bcc0dc: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd1190)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
c000000000bd1190-c000000000bd1304: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006dd8d0)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffe0006dd8d0-ffffffe0006dd9e8: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81839572)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81846339-ffffffff8184634a: mddev_create_wb_pool.cold (STB_LOCAL)
ffffffff81839510-ffffffff81839601: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81800be2)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff8180d999-ffffffff8180d9aa: mddev_create_wb_pool.cold (STB_LOCAL)
ffffffff81800b80-ffffffff81800c71: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81888ba2)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81895969-ffffffff8189597a: mddev_create_wb_pool.cold (STB_LOCAL)
ffffffff81888b40-ffffffff81888c31: mddev_create_wb_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_create_wb_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff818a62d2)
Location: drivers/md/md.c:145
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff818b1988-ffffffff818b1999: mddev_create_wb_pool.cold (STB_LOCAL)
ffffffff818a6270-ffffffff818a6361: mddev_create_wb_pool (STB_GLOBAL)
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
