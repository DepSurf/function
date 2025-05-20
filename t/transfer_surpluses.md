# Function: <code>transfer_surpluses</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void transfer_surpluses(struct list_head *surpluses, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1817
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8158d780-ffffffff8158de10: transfer_surpluses (STB_LOCAL)
ffffffff81bf3b88-ffffffff81bf3bdb: transfer_surpluses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void transfer_surpluses(struct list_head *surpluses, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1824
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81593f30-ffffffff815945bc: transfer_surpluses (STB_LOCAL)
ffffffff81be59e8-ffffffff81be5a3b: transfer_surpluses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void transfer_surpluses(struct list_head *surpluses, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1824
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff815fb3f0-ffffffff815fba79: transfer_surpluses (STB_LOCAL)
ffffffff81cd9dd0-ffffffff81cd9e23: transfer_surpluses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void transfer_surpluses(struct list_head *surpluses, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1817
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff816afb20-ffffffff816b01fb: transfer_surpluses (STB_LOCAL)
ffffffff81e8d933-ffffffff81e8d986: transfer_surpluses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void transfer_surpluses(struct list_head *surpluses, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176de20)
Location: block/blk-iocost.c:1822
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8176de20-ffffffff8176e537: transfer_surpluses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void transfer_surpluses(struct list_head *surpluses, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ad9a0)
Location: block/blk-iocost.c:1838
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817ad9a0-ffffffff817ae0b6: transfer_surpluses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void transfer_surpluses(struct list_head *surpluses, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817f17b0)
Location: block/blk-iocost.c:1845
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817f17b0-ffffffff817f1ec6: transfer_surpluses (STB_LOCAL)
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
