# Function: <code>ktime_get_coarse_with_offset</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81116f60)
Location: kernel/time/timekeeping.c:798
Inline: False
```
**Symbols:**

```
ffffffff81116f60-ffffffff81116fa8: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811225a0)
Location: kernel/time/timekeeping.c:805
Inline: False
```
**Symbols:**

```
ffffffff811225a0-ffffffff811225e8: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffff8112f743-ffffffff8112f756: ktime_get_coarse_with_offset.cold (STB_LOCAL)
ffffffff8112d3d0-ffffffff8112d42d: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139270)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffff81139270-ffffffff811392cb: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147f10)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffff81147f10-ffffffff81147f6d: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81144350)
Location: kernel/time/timekeeping.c:881
Inline: False
```
**Symbols:**

```
ffffffff81144350-ffffffff811443ac: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811454d0)
Location: kernel/time/timekeeping.c:881
Inline: False
```
**Symbols:**

```
ffffffff811454d0-ffffffff8114552c: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:881
Inline: False
```
**Symbols:**

```
ffffffff81cb0a3f-ffffffff81cb0a63: ktime_get_coarse_with_offset.cold (STB_LOCAL)
ffffffff81168c80-ffffffff81168d11: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:900
Inline: False
```
**Symbols:**

```
ffffffff81e61fd7-ffffffff81e61ffb: ktime_get_coarse_with_offset.cold (STB_LOCAL)
ffffffff8119c810-ffffffff8119c8b0: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:900
Inline: False
```
**Symbols:**

```
ffffffff8205ae73-ffffffff8205ae97: ktime_get_coarse_with_offset.cold (STB_LOCAL)
ffffffff811db230-ffffffff811db2d0: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:900
Inline: False
```
**Symbols:**

```
ffffffff820d9727-ffffffff820d974b: ktime_get_coarse_with_offset.cold (STB_LOCAL)
ffffffff811ef7d0-ffffffff811ef870: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:900
Inline: False
Direct callers:
  - net/core/page_pool_user.c:page_pool_detached
```
**Symbols:**

```
ffffffff821b5026-ffffffff821b504a: ktime_get_coarse_with_offset.cold (STB_LOCAL)
ffffffff81205860-ffffffff81205900: ktime_get_coarse_with_offset (STB_GLOBAL)
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
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a2ff0)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffff8000101a2ff0-ffff8000101a3078: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ecf30)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
c03ecf30-c03ed01c: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204860)
Location: kernel/time/timekeeping.c:811
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:show_uptime
```
**Symbols:**

```
c000000000204860-c0000000002048fc: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fc6c)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffe00012fc6c-ffffffe00012fce4: ktime_get_coarse_with_offset (STB_GLOBAL)
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
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131a20)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffff81131a20-ffffffff81131a7b: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124480)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffff81124480-ffffffff811244db: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f740)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffff8112f740-ffffffff8112f79b: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t ktime_get_coarse_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c160)
Location: kernel/time/timekeeping.c:811
Inline: False
```
**Symbols:**

```
ffffffff8113c160-ffffffff8113c1bb: ktime_get_coarse_with_offset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
