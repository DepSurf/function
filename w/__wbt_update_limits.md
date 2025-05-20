# Function: <code>__wbt_update_limits</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd150)
Location: block/blk-wbt.c:405
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_queue_depth
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff814cd150-ffffffff814cd1a0: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fb9c0)
Location: block/blk-wbt.c:406
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_queue_depth
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff814fb9c0-ffffffff814fba15: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81519880)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff81519880-ffffffff815198d5: __wbt_update_limits (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010620de8)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffff800010620de8-ffff800010620e4c: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c8eb8)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
c07c8eb8-c07c8f0c: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c1280)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
c0000000007c1280-c0000000007c1310: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe0004538d2)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffe0004538d2-ffffffe000453936: __wbt_update_limits (STB_LOCAL)
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
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81511e60)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff81511e60-ffffffff81511eb5: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502180)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff81502180-ffffffff815021d5: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150def0)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff8150def0-ffffffff8150df45: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81527510)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_update_limits
```
**Symbols:**

```
ffffffff81527510-ffffffff81527565: __wbt_update_limits (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
