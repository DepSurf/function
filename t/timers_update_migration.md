# Function: <code>timers_update_migration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void timers_update_migration(bool update_nohz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ee4c0)
Location: kernel/time/timer.c:103
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff810ee4c0-ffffffff810ee581: timers_update_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void timers_update_migration(bool update_nohz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f54a0)
Location: kernel/time/timer.c:213
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
**Symbols:**

```
ffffffff810f54a0-ffffffff810f5587: timers_update_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void timers_update_migration(bool update_nohz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fc510)
Location: kernel/time/timer.c:213
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
**Symbols:**

```
ffffffff810fc510-ffffffff810fc5f9: timers_update_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void timers_update_migration(bool update_nohz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fe9b0)
Location: kernel/time/timer.c:216
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
**Symbols:**

```
ffffffff810fe9b0-ffffffff810fea98: timers_update_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void timers_update_migration(bool update_nohz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811096a0)
Location: kernel/time/timer.c:216
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
**Symbols:**

```
ffffffff811096a0-ffffffff81109789: timers_update_migration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81112d80)
Location: kernel/time/timer.c:224
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff81112d80-ffffffff81112db2: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111e560)
Location: kernel/time/timer.c:223
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff8111e560-ffffffff8111e592: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811291f0)
Location: kernel/time/timer.c:223
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff811291f0-ffffffff81129222: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81135190)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff81135190-ffffffff811351c2: timers_update_migration (STB_LOCAL)
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
In kernel/time/timer.c (ffffffff81145944)
Location: kernel/time/timer.c:228
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
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
In kernel/time/timer.c (ffffffff81141f24)
Location: kernel/time/timer.c:229
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
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
In kernel/time/timer.c (ffffffff811430e4)
Location: kernel/time/timer.c:230
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
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
In kernel/time/timer.c (ffffffff81166674)
Location: kernel/time/timer.c:230
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
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
In kernel/time/timer.c (ffffffff81198935)
Location: kernel/time/timer.c:231
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_migration_handler
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
In kernel/time/timer.c (ffffffff811d6b95)
Location: kernel/time/timer.c:231
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_migration_handler
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
In kernel/time/timer.c (ffffffff811eb155)
Location: kernel/time/timer.c:231
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_migration_handler
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
In kernel/time/timer.c (ffffffff81201185)
Location: kernel/time/timer.c:231
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_migration_handler
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
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019cc60)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffff80001019cc60-ffff80001019ccb0: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7b48)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
c03e7b48-c03e7cd0: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fe060)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
c0000000001fe060-c0000000001fe0d8: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012c2b8)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffe00012c2b8-ffffffe00012c38a: timers_update_migration (STB_LOCAL)
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
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d940)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff8112d940-ffffffff8112d972: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811201b0)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff811201b0-ffffffff811201e2: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112b660)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff8112b660-ffffffff8112b692: timers_update_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void timers_update_migration();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137a70)
Location: kernel/time/timer.c:227
Inline: False
Direct callers:
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
```
**Symbols:**

```
ffffffff81137a70-ffffffff81137aa2: timers_update_migration (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool update_nohz</code>
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
