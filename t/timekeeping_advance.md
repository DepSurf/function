# Function: <code>timekeeping_advance</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2038
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81123d50-ffffffff811242e2: timekeeping_advance (STB_LOCAL)
ffffffff81124d5f-ffffffff81124d82: timekeeping_advance.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8112e310-ffffffff8112e8a9: timekeeping_advance (STB_LOCAL)
ffffffff8112f78d-ffffffff8112f7b1: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8113a2c0-ffffffff8113a859: timekeeping_advance (STB_LOCAL)
ffffffff8113b701-ffffffff8113b725: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81149900)
Location: kernel/time/timekeeping.c:2047
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81149900-ffffffff81149d53: timekeeping_advance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145a60)
Location: kernel/time/timekeeping.c:2117
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff81145a60-ffffffff81145eb3: timekeeping_advance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2128
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff81146cb0-ffffffff81147226: timekeeping_advance (STB_LOCAL)
ffffffff81bd56f9-ffffffff81bd571b: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2129
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff8116a710-ffffffff8116ab77: timekeeping_advance (STB_LOCAL)
ffffffff81cb1096-ffffffff81cb11ec: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2150
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff8119e2d0-ffffffff8119e773: timekeeping_advance (STB_LOCAL)
ffffffff81e625e8-ffffffff81e62737: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2150
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff811dceb0-ffffffff811dd353: timekeeping_advance (STB_LOCAL)
ffffffff8205b435-ffffffff8205b584: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2150
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff811f13c0-ffffffff811f185b: timekeeping_advance (STB_LOCAL)
ffffffff820d9cfe-ffffffff820d9e1d: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2150
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff81207500-ffffffff81207991: timekeeping_advance (STB_LOCAL)
ffffffff821b55fd-ffffffff821b571c: timekeeping_advance.cold (STB_LOCAL)
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
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a4738)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffff8000101a4738-ffff8000101a4ce4: timekeeping_advance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ee7f8)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
c03ee7f8-c03ef128: timekeeping_advance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000206200)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
c000000000206200-c000000000206938: timekeeping_advance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130d4c)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffe000130d4c-ffffffe0001312e6: timekeeping_advance (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81132a70-ffffffff81133009: timekeeping_advance (STB_LOCAL)
ffffffff81133eb1-ffffffff81133ed5: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff811254d0-ffffffff81125a69: timekeeping_advance (STB_LOCAL)
ffffffff81126911-ffffffff81126935: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff81130790-ffffffff81130d29: timekeeping_advance (STB_LOCAL)
ffffffff81131bd1-ffffffff81131bf5: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void timekeeping_advance(enum timekeeping_adv_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:2048
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff8113d1b0-ffffffff8113d749: timekeeping_advance (STB_LOCAL)
ffffffff8113e5ef-ffffffff8113e613: timekeeping_advance.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
