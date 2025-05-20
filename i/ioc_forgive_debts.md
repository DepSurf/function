# Function: <code>ioc_forgive_debts</code>

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
void ioc_forgive_debts(struct ioc *ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158f430)
Location: block/blk-iocost.c:2043
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8158f430-ffffffff8158f6b9: ioc_forgive_debts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioc_forgive_debts(struct ioc *ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81596090)
Location: block/blk-iocost.c:2050
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81596090-ffffffff81596314: ioc_forgive_debts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ioc_forgive_debts(struct ioc *ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2050
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff815fd610-ffffffff815fd8bb: ioc_forgive_debts (STB_LOCAL)
ffffffff81cd9e91-ffffffff81cd9ecd: ioc_forgive_debts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioc_forgive_debts(struct ioc *ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2043
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff816af800-ffffffff816afb18: ioc_forgive_debts (STB_LOCAL)
ffffffff81e8d8df-ffffffff81e8d933: ioc_forgive_debts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ioc_forgive_debts(struct ioc *ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2048
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8176e9d0-ffffffff8176ece4: ioc_forgive_debts (STB_LOCAL)
ffffffff82076e78-ffffffff82076ecc: ioc_forgive_debts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ioc_forgive_debts(struct ioc *ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2064
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817ae550-ffffffff817ae864: ioc_forgive_debts (STB_LOCAL)
ffffffff820f6cfc-ffffffff820f6d50: ioc_forgive_debts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ioc_forgive_debts(struct ioc *ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2071
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817f2360-ffffffff817f2674: ioc_forgive_debts (STB_LOCAL)
ffffffff821d414a-ffffffff821d419e: ioc_forgive_debts.cold (STB_LOCAL)
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
