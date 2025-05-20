# Function: <code>mddev_destroy_serial_pool</code>

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
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff8196abd9)
Location: drivers/md/md.c:255
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81963330-ffffffff81963493: mddev_destroy_serial_pool.part.0 (STB_LOCAL)
ffffffff819700d5-ffffffff819700e6: mddev_destroy_serial_pool.part.0.cold (STB_LOCAL)
ffffffff81969910-ffffffff81969941: mddev_destroy_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81971759)
Location: drivers/md/md.c:253
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81969be0-ffffffff81969d47: mddev_destroy_serial_pool.part.0 (STB_LOCAL)
ffffffff81c2622a-ffffffff81c2623b: mddev_destroy_serial_pool.part.0.cold (STB_LOCAL)
ffffffff81970490-ffffffff819704c1: mddev_destroy_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81955849)
Location: drivers/md/md.c:253
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff8194ded0-ffffffff8194e037: mddev_destroy_serial_pool.part.0 (STB_LOCAL)
ffffffff81c183c1-ffffffff81c183d2: mddev_destroy_serial_pool.part.0.cold (STB_LOCAL)
ffffffff819543e0-ffffffff81954411: mddev_destroy_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff819fae79)
Location: drivers/md/md.c:254
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff819f32d0-ffffffff819f3437: mddev_destroy_serial_pool.part.0 (STB_LOCAL)
ffffffff81d27939-ffffffff81d2794a: mddev_destroy_serial_pool.part.0.cold (STB_LOCAL)
ffffffff819f99e0-ffffffff819f9a11: mddev_destroy_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81b62370)
Location: drivers/md/md.c:255
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81b5f200-ffffffff81b5f417: mddev_destroy_serial_pool.part.0 (STB_LOCAL)
ffffffff81ef3a60-ffffffff81ef3a71: mddev_destroy_serial_pool.part.0.cold (STB_LOCAL)
ffffffff81b60f10-ffffffff81b60f59: mddev_destroy_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfb040)
Location: drivers/md/md.c:267
Inline: False
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81cfb040-ffffffff81cfb232: mddev_destroy_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d619e0)
Location: drivers/md/md.c:253
Inline: False
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81d619e0-ffffffff81d61bd0: mddev_destroy_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mddev_destroy_serial_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81e1dca3)
Location: drivers/md/md.c:265
Inline: True
Inline callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
Direct callers:
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_destroy
```
**Symbols:**

```
ffffffff81e15b30-ffffffff81e15c78: mddev_destroy_serial_pool.part.0 (STB_LOCAL)
ffffffff81e18bf0-ffffffff81e18c32: mddev_destroy_serial_pool (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_suspend</code>
</li>
</ul>
</details>
</li>
</ul>
