# Function: <code>mddev_create_serial_pool</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:211
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81970d17-ffffffff81970d28: mddev_create_serial_pool.cold (STB_LOCAL)
ffffffff81969330-ffffffff819694f9: mddev_create_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:209
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81c26e02-ffffffff81c26e13: mddev_create_serial_pool.cold (STB_LOCAL)
ffffffff8196fe40-ffffffff8197000d: mddev_create_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:209
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81c18fb3-ffffffff81c18fc4: mddev_create_serial_pool.cold (STB_LOCAL)
ffffffff81953d80-ffffffff81953f4d: mddev_create_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:210
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81d28590-ffffffff81d285a1: mddev_create_serial_pool.cold (STB_LOCAL)
ffffffff819f9350-ffffffff819f951d: mddev_create_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:211
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81ef461f-ffffffff81ef4630: mddev_create_serial_pool.cold (STB_LOCAL)
ffffffff81b607f0-ffffffff81b60a10: mddev_create_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfaa20)
Location: drivers/md/md.c:223
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81cfaa20-ffffffff81cfac31: mddev_create_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev, bool is_suspend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d613a0)
Location: drivers/md/md.c:209
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81d613a0-ffffffff81d615df: mddev_create_serial_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mddev_create_serial_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e18680)
Location: drivers/md/md.c:229
Inline: False
Direct callers:
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:backlog_store
  - drivers/md/md-bitmap.c:md_bitmap_load
```
**Symbols:**

```
ffffffff81e18680-ffffffff81e187d1: mddev_create_serial_pool (STB_GLOBAL)
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
