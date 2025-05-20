# Function: <code>move_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff810f9330)
Location: kernel/time/timer_list.c:331
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff810f9330-ffffffff810f9398: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811005b0)
Location: kernel/time/timer_list.c:331
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff811005b0-ffffffff81100618: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81103350)
Location: kernel/time/timer_list.c:331
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff81103350-ffffffff811033ba: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81105840)
Location: kernel/time/timer_list.c:327
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff81105840-ffffffff811058a9: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8110ff20)
Location: kernel/time/timer_list.c:327
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff8110ff20-ffffffff8110ff7d: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8111b940)
Location: kernel/time/timer_list.c:325
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff8111b940-ffffffff8111b99d: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811270f0)
Location: kernel/time/timer_list.c:320
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff811270f0-ffffffff8112714d: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81131b30)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff81131b30-ffffffff81131b84: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8113da80)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff8113da80-ffffffff8113dad4: move_iter (STB_LOCAL)
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
In kernel/time/timer_list.c (ffffffff8114d6da)
Location: kernel/time/timer_list.c:321
Inline: True
Inline callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
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
In kernel/time/timer_list.c (ffffffff8114982a)
Location: kernel/time/timer_list.c:293
Inline: True
Inline callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
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
In kernel/time/timer_list.c (ffffffff8114acfa)
Location: kernel/time/timer_list.c:293
Inline: True
Inline callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8116eb6b)
Location: kernel/time/timer_list.c:301
Inline: True
Inline callers:
  - kernel/time/timer_list.c:timer_list_next
Direct callers:
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff8116e970-ffffffff8116e9d9: move_iter (STB_LOCAL)
ffffffff81cb1aeb-ffffffff81cb1b00: move_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811a2e7b)
Location: kernel/time/timer_list.c:301
Inline: True
Inline callers:
  - kernel/time/timer_list.c:timer_list_next
Direct callers:
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff811a2c40-ffffffff811a2cb9: move_iter (STB_LOCAL)
ffffffff81e63096-ffffffff81e630ab: move_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (0)
Location: kernel/time/timer_list.c:301
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff811e2320-ffffffff811e23b2: move_iter (STB_LOCAL)
ffffffff8205ba7f-ffffffff8205ba94: move_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (0)
Location: kernel/time/timer_list.c:301
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff811f6880-ffffffff811f6912: move_iter (STB_LOCAL)
ffffffff820da281-ffffffff820da296: move_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (0)
Location: kernel/time/timer_list.c:301
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff8120ca20-ffffffff8120cab2: move_iter (STB_LOCAL)
ffffffff821b5b80-ffffffff821b5b95: move_iter.cold (STB_LOCAL)
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
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffff8000101a7568)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffff8000101a7568-ffff8000101a760c: move_iter (STB_LOCAL)
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
In kernel/time/timer_list.c (c03f359c)
Location: kernel/time/timer_list.c:321
Inline: True
Inline callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (c00000000020a240)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
c00000000020a240-c00000000020a33c: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffe000133546)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffe000133546-ffffffe0001335c6: move_iter (STB_LOCAL)
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
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81136230)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff81136230-ffffffff81136284: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81128c80)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff81128c80-ffffffff81128cd4: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81133f50)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff81133f50-ffffffff81133fa4: move_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *move_iter(struct timer_list_iter *iter, loff_t offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81140970)
Location: kernel/time/timer_list.c:321
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_next
  - kernel/time/timer_list.c:timer_list_start
```
**Symbols:**

```
ffffffff81140970-ffffffff811409c4: move_iter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
