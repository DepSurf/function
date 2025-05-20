# Function: <code>process_adjtimex_modes</code>

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
In kernel/time/ntp.c (ffffffff810f7633)
Location: kernel/time/ntp.c:601
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff810fe777)
Location: kernel/time/ntp.c:607
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff81101567)
Location: kernel/time/ntp.c:607
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff811036fb)
Location: kernel/time/ntp.c:607
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8110e78b)
Location: kernel/time/ntp.c:668
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8111a13e)
Location: kernel/time/ntp.c:668
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8112563e)
Location: kernel/time/ntp.c:659
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff811300c6)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8113c006)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8114a990)
Location: kernel/time/ntp.c:661
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff8114a990-ffffffff8114ab24: process_adjtimex_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81146e80)
Location: kernel/time/ntp.c:709
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff81146e80-ffffffff81147014: process_adjtimex_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81147e50)
Location: kernel/time/ntp.c:709
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff81147e50-ffffffff81148157: process_adjtimex_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8116bb30)
Location: kernel/time/ntp.c:709
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff8116bb30-ffffffff8116bcc0: process_adjtimex_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8119fa80)
Location: kernel/time/ntp.c:709
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff8119fa80-ffffffff8119fc3a: process_adjtimex_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811de7f0)
Location: kernel/time/ntp.c:709
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff811de7f0-ffffffff811de9aa: process_adjtimex_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811f2cc0)
Location: kernel/time/ntp.c:709
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff811f2cc0-ffffffff811f2e7a: process_adjtimex_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void process_adjtimex_modes(const struct __kernel_timex *txc, s32 *time_tai);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81208e00)
Location: kernel/time/ntp.c:709
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff81208e00-ffffffff81208fba: process_adjtimex_modes (STB_LOCAL)
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
In kernel/time/ntp.c (ffff8000101a62c8)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (c03f13fc)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (c000000000208570)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffe000132456)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff811347b6)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff81127216)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff811324d6)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
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
In kernel/time/ntp.c (ffffffff8113eef6)
Location: kernel/time/ntp.c:661
Inline: True
Inline callers:
  - kernel/time/ntp.c:__do_adjtimex
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
