# Function: <code>tg_service_queue_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813d9a86)
Location: block/blk-throttle.c:451
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8141f8c6)
Location: block/blk-throttle.c:445
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143b9e6)
Location: block/blk-throttle.c:445
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81449d26)
Location: block/blk-throttle.c:660
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81475986)
Location: block/blk-throttle.c:658
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814a9e45)
Location: block/blk-throttle.c:656
Inline: True
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
In block/blk-throttle.c (ffffffff814c4305)
Location: block/blk-throttle.c:649
Inline: True
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
In block/blk-throttle.c (ffffffff814f2aa5)
Location: block/blk-throttle.c:649
Inline: True
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
In block/blk-throttle.c (ffffffff8150c025)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (ffffffff8156d3f5)
Location: block/blk-throttle.c:669
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_enqueue_tg
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
In block/blk-throttle.c (ffffffff81587ca5)
Location: block/blk-throttle.c:674
Inline: True
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
In block/blk-throttle.c (ffffffff8158eaf5)
Location: block/blk-throttle.c:674
Inline: True
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
In block/blk-throttle.c (ffffffff815f4b55)
Location: block/blk-throttle.c:677
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a6585)
Location: block/blk-throttle.c:537
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tg_service_queue_add(struct throtl_grp *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81764b20)
Location: block/blk-throttle.c:530
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff81764b20-ffffffff81764bf6: tg_service_queue_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tg_service_queue_add(struct throtl_grp *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a3c00)
Location: block/blk-throttle.c:529
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff817a3c00-ffffffff817a3cd4: tg_service_queue_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tg_service_queue_add(struct throtl_grp *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817e7770)
Location: block/blk-throttle.c:529
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff817e7770-ffffffff817e7844: tg_service_queue_add (STB_LOCAL)
```
</details>
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
In block/blk-throttle.c (ffff80001060fc00)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (c07ba2f8)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (c0000000007ad120)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (ffffffe000447ad4)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (ffffffff81504605)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (ffffffff814f4ac5)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (ffffffff81500695)
Location: block/blk-throttle.c:651
Inline: True
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
In block/blk-throttle.c (ffffffff815196a5)
Location: block/blk-throttle.c:651
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
