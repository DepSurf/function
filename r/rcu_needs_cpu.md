# Function: <code>rcu_needs_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e86c0)
Location: kernel/rcu/tree_plugin.h:1360
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810e86c0-ffffffff810e873b: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eedb0)
Location: kernel/rcu/tree_plugin.h:1258
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810eedb0-ffffffff810eee2b: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5f20)
Location: kernel/rcu/tree_plugin.h:1258
Inline: False
```
**Symbols:**

```
ffffffff810f5f20-ffffffff810f5f9b: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f6bf0)
Location: kernel/rcu/tree_plugin.h:1296
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810f6bf0-ffffffff810f6c70: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81100c10)
Location: kernel/rcu/tree_plugin.h:1310
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff81100c10-ffffffff81100c93: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81108b20)
Location: kernel/rcu/tree_plugin.h:1346
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81108b20-ffffffff81108ba3: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113f80)
Location: kernel/rcu/tree_plugin.h:1543
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81113f80-ffffffff81113fb2: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111dc20)
Location: kernel/rcu/tree_plugin.h:1259
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8111dc20-ffffffff8111dc52: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112a1c0)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8112a1c0-ffffffff8112a20f: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81138730)
Location: kernel/rcu/tree_plugin.h:1227
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81138730-ffffffff8113877f: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134000)
Location: kernel/rcu/tree_plugin.h:1255
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81134000-ffffffff81134047: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134d70)
Location: kernel/rcu/tree_plugin.h:1322
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81134d70-ffffffff81134db7: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81157570)
Location: kernel/rcu/tree_plugin.h:1268
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81157570-ffffffff811575b7: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rcu_needs_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117f730)
Location: kernel/rcu/tree.c:1100
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8117f730-ffffffff8117f75b: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rcu_needs_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b9980)
Location: kernel/rcu/tree.c:675
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff811b9980-ffffffff811b99ab: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rcu_needs_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cc290)
Location: kernel/rcu/tree.c:657
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff811cc290-ffffffff811cc2bb: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rcu_needs_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811e0e00)
Location: kernel/rcu/tree.c:658
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff811e0e00-ffffffff811e0e3d: rcu_needs_cpu (STB_GLOBAL)
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
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff8000101920a0)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffff8000101920a0-ffff8000101920f4: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dfadc)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
c03dfadc-c03dfb24: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ed6c0)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
c0000000001ed6c0-c0000000001ed70c: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000124e8c)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffe000124e8c-ffffffe000124ede: rcu_needs_cpu (STB_GLOBAL)
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
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811227a0)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff811227a0-ffffffff811227ef: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114e90)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81114e90-ffffffff81114edf: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81120690)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff81120690-ffffffff811206df: rcu_needs_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rcu_needs_cpu(u64 basemono, u64 *nextevt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112c950)
Location: kernel/rcu/tree_plugin.h:1238
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_next_event
```
**Symbols:**

```
ffffffff8112c950-ffffffff8112c99f: rcu_needs_cpu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 basemono</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 *nextevt</code>
</li>
</ul>
</details>
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
