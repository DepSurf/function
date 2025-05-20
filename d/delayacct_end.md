# Function: <code>delayacct_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void delayacct_end(u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8113ddf0)
Location: kernel/delayacct.c:52
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_freepages_end
```
**Symbols:**

```
ffffffff8113ddf0-ffffffff8113de4f: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void delayacct_end(u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81146400)
Location: kernel/delayacct.c:52
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff81146400-ffffffff8114645f: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void delayacct_end(u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81150240)
Location: kernel/delayacct.c:52
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff81150240-ffffffff8115029f: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void delayacct_end(u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81152860)
Location: kernel/delayacct.c:54
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff81152860-ffffffff811528bf: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void delayacct_end(spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8115f0a0)
Location: kernel/delayacct.c:54
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff8115f0a0-ffffffff8115f0f0: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8116e050)
Location: kernel/delayacct.c:54
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff8116e050-ffffffff8116e0a0: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8117ba90)
Location: kernel/delayacct.c:54
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff8117ba90-ffffffff8117bae0: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811888b0)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff811888b0-ffffffff81188900: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811947f0)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff811947f0-ffffffff81194840: delayacct_end (STB_LOCAL)
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
In kernel/delayacct.c (ffffffff811a9c5c)
Location: kernel/delayacct.c:45
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
In kernel/delayacct.c (ffffffff811a727c)
Location: kernel/delayacct.c:45
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
In kernel/delayacct.c (ffffffff811a7dbc)
Location: kernel/delayacct.c:45
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
In kernel/delayacct.c (ffffffff811d18ec)
Location: kernel/delayacct.c:79
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
In kernel/delayacct.c (ffffffff8120611c)
Location: kernel/delayacct.c:99
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_wpcopy_end
  - kernel/delayacct.c:__delayacct_compact_end
  - kernel/delayacct.c:__delayacct_swapin_end
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
In kernel/delayacct.c (ffffffff8124e3ec)
Location: kernel/delayacct.c:99
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_wpcopy_end
  - kernel/delayacct.c:__delayacct_compact_end
  - kernel/delayacct.c:__delayacct_swapin_end
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
In kernel/delayacct.c (ffffffff8126572c)
Location: kernel/delayacct.c:99
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_wpcopy_end
  - kernel/delayacct.c:__delayacct_compact_end
  - kernel/delayacct.c:__delayacct_swapin_end
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
In kernel/delayacct.c (ffffffff8127f5ac)
Location: kernel/delayacct.c:99
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_wpcopy_end
  - kernel/delayacct.c:__delayacct_compact_end
  - kernel/delayacct.c:__delayacct_swapin_end
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
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
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffff80001020c818)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffff80001020c818-ffff80001020c900: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (c044b210)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
c044b210-c044b290: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (c00000000028a480)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
c00000000028a480-c00000000028a524: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffe00016dbb2)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffe00016dbb2-ffffffe00016dc20: delayacct_end (STB_LOCAL)
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
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8118ce10)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff8118ce10-ffffffff8118ce60: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8117fef0)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff8117fef0-ffffffff8117ff40: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8118abe0)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff8118abe0-ffffffff8118ac30: delayacct_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void delayacct_end(raw_spinlock_t *lock, u64 *start, u64 *total, u32 *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81198550)
Location: kernel/delayacct.c:45
Inline: False
Direct callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_end
```
**Symbols:**

```
ffffffff81198550-ffffffff811985a0: delayacct_end (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>spinlock_t *lock</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, total, count</code> ➡️ <code>lock, start, total, count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>spinlock_t *lock</code> ➡️ <code>raw_spinlock_t *lock</code>
</li>
</ul>
</details>
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
