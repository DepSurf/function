# Function: <code>elv_drain_elevator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_drain_elevator(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3f10)
Location: block/elevator.c:578
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff813b3f10-ffffffff813b3f70: elv_drain_elevator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_drain_elevator(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7bf0)
Location: block/elevator.c:577
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff813f7bf0-ffffffff813f7c50: elv_drain_elevator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_drain_elevator(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411620)
Location: block/elevator.c:575
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff81411620-ffffffff81411680: elv_drain_elevator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_drain_elevator(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f1f0)
Location: block/elevator.c:614
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff8141f1f0-ffffffff8141f264: elv_drain_elevator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_drain_elevator(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449cd0)
Location: block/elevator.c:631
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff81449cd0-ffffffff81449d4a: elv_drain_elevator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void elv_drain_elevator(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:600
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
```
**Symbols:**

```
ffffffff8147d76e-ffffffff8147d78d: elv_drain_elevator.cold.31 (STB_LOCAL)
ffffffff8147ca30-ffffffff8147caa0: elv_drain_elevator (STB_GLOBAL)
```
</details>
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
</ul>
