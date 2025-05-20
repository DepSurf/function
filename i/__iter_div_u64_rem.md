# Function: <code>__iter_div_u64_rem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4813)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In lib/div64.c (ffffffff813f7e21)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - lib/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc8d9)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In lib/div64.c (ffffffff8143ece1)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - lib/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff7f9)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In lib/div64.c (ffffffff8145bd31)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - lib/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81101a15)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In lib/div64.c (ffffffff81461211)
Location: include/linux/math64.h:118
Inline: True
Inline callers:
  - lib/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110c918)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:__getnstimeofday64
```
```
In lib/div64.c (ffffffff8148d0e0)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117098)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In lib/div64.c (ffffffff814c1e60)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811226d8)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In lib/div64.c (ffffffff814d6550)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112d4d5)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8113dd9c)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff81510670)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139375)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8114993e)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff8152e570)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148017)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8115988d)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff81592450)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114445d)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8115581d)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff815aef95)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811455dd)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff81156c5d)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff815b9d45)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8116985d)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8117bb7e)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff81620695)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119de42)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff811b123b)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff816ee785)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811dc062)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff811f1e9b)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff817df335)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811f0f02)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8120664b)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff8181eb15)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81207042)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8121d85b)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff81864985)
Location: include/vdso/math64.h:6
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3108)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffff8000101b611c)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffff80001063aab8)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/plat-omap/counter_32k.c (c034f814)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - arch/arm/plat-omap/counter_32k.c:omap_read_persistent_clock64
```
```
In kernel/time/timekeeping.c (c03ed138)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In lib/math/div64.c (c07e0804)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c0000000002049d0)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In lib/math/div64.c (c0000000007e1a70)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fa66)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In lib/math/div64.c (ffffffe000466f78)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131b25)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff81141f5e)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff81526b50)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124585)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff811352be)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff81516e30)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f845)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8113fe0e)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff81522be0)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c265)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
```
In kernel/time/vsyscall.c (ffffffff8114c93e)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
```
In lib/math/div64.c (ffffffff8153c560)
Location: include/linux/math64.h:146
Inline: True
Inline callers:
  - lib/math/div64.c:iter_div_u64_rem
```
</details>
</li>
</ul>

## Differences
