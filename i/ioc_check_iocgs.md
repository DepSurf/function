# Function: <code>ioc_check_iocgs</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ioc_check_iocgs(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158eac0)
Location: block/blk-iocost.c:2134
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8158eac0-ffffffff8158ee2f: ioc_check_iocgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ioc_check_iocgs(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81595d20)
Location: block/blk-iocost.c:2141
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81595d20-ffffffff8159608d: ioc_check_iocgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ioc_check_iocgs(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2141
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff815fd290-ffffffff815fd60a: ioc_check_iocgs (STB_LOCAL)
ffffffff81cd9e7d-ffffffff81cd9e91: ioc_check_iocgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ioc_check_iocgs(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2134
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff816b0b40-ffffffff816b0ed7: ioc_check_iocgs (STB_LOCAL)
ffffffff81e8d9b6-ffffffff81e8d9d2: ioc_check_iocgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ioc_check_iocgs(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2139
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8176f320-ffffffff8176f6b7: ioc_check_iocgs (STB_LOCAL)
ffffffff82076ecc-ffffffff82076ee8: ioc_check_iocgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ioc_check_iocgs(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2155
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817aeed0-ffffffff817af267: ioc_check_iocgs (STB_LOCAL)
ffffffff820f6d50-ffffffff820f6d6c: ioc_check_iocgs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ioc_check_iocgs(struct ioc *ioc, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2162
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817f2ce0-ffffffff817f3077: ioc_check_iocgs (STB_LOCAL)
ffffffff821d419e-ffffffff821d41ba: ioc_check_iocgs.cold (STB_LOCAL)
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
