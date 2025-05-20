# Function: <code>__ioc_clear_queue</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ioc_clear_queue(struct list_head *icq_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8142a940)
Location: block/blk-ioc.c:228
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:ioc_clear_queue
```
**Symbols:**

```
ffffffff8142a940-ffffffff8142a99c: __ioc_clear_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ioc_clear_queue(struct list_head *icq_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81455b30)
Location: block/blk-ioc.c:229
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:ioc_clear_queue
```
**Symbols:**

```
ffffffff81455b30-ffffffff81455b8c: __ioc_clear_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ioc_clear_queue(struct list_head *icq_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81488f70)
Location: block/blk-ioc.c:229
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:ioc_clear_queue
```
**Symbols:**

```
ffffffff81488f70-ffffffff81488fcb: __ioc_clear_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81549591)
Location: block/blk-ioc.c:212
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815653b1)
Location: block/blk-ioc.c:212
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8156da21)
Location: block/blk-ioc.c:212
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815d2011)
Location: block/blk-ioc.c:212
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffff8000105e8bfc)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c0795414)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffe0004295d6)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814f7ac8)
Location: block/blk-ioc.c:211
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
