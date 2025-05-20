# Function: <code>throtl_select_dispatch</code>

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
In block/blk-throttle.c (ffffffff813db7bc)
Location: block/blk-throttle.c:976
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (ffffffff814212dc)
Location: block/blk-throttle.c:972
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (ffffffff8143c6ca)
Location: block/blk-throttle.c:972
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8144b030)
Location: block/blk-throttle.c:1208
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8144b030-ffffffff8144b176: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81477860)
Location: block/blk-throttle.c:1206
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81477860-ffffffff81477999: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814abed0)
Location: block/blk-throttle.c:1204
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814abed0-ffffffff814ac008: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c62b0)
Location: block/blk-throttle.c:1190
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814c62b0-ffffffff814c63f0: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f4b00)
Location: block/blk-throttle.c:1187
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814f4b00-ffffffff814f4c47: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150e100)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8150e100-ffffffff8150e26e: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156ec60)
Location: block/blk-throttle.c:1207
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8156ec60-ffffffff8156ed2a: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81589a10)
Location: block/blk-throttle.c:1217
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81589a10-ffffffff81589ada: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81590320)
Location: block/blk-throttle.c:1217
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81590320-ffffffff815904d4: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f72a0)
Location: block/blk-throttle.c:1228
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff815f72a0-ffffffff815f7461: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816aa030)
Location: block/blk-throttle.c:1086
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff816aa030-ffffffff816aa1ff: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1116
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1115
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1121
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff800010611d20)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffff800010611d20-ffff800010611ec4: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07bc558)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
c07bc558-c07bc6bc: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007afe60)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
c0000000007afe60-c0000000007b00c0: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe000449546)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffe000449546-ffffffe000449680: throtl_select_dispatch (STB_LOCAL)
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
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815066e0)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff815066e0-ffffffff8150684e: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f6ba0)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814f6ba0-ffffffff814f6d0e: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81502770)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81502770-ffffffff815028de: throtl_select_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int throtl_select_dispatch(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8151bb80)
Location: block/blk-throttle.c:1189
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8151bb80-ffffffff8151bcee: throtl_select_dispatch (STB_LOCAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
