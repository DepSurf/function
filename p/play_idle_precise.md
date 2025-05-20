# Function: <code>play_idle_precise</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e84d0)
Location: kernel/sched/idle.c:331
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810e84d0-ffffffff810e8610: play_idle_precise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e60c0)
Location: kernel/sched/idle.c:355
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810e60c0-ffffffff810e621e: play_idle_precise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e8090)
Location: kernel/sched/idle.c:361
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810e8090-ffffffff810e81ee: play_idle_precise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ff750)
Location: kernel/sched/idle.c:361
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810ff750-ffffffff810ff8ae: play_idle_precise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81133770)
Location: kernel/sched/idle.c:358
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff81133770-ffffffff81133904: play_idle_precise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115dba0)
Location: kernel/sched/idle.c:358
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff8115dba0-ffffffff8115dd34: play_idle_precise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116e280)
Location: kernel/sched/idle.c:337
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff8116e280-ffffffff8116e414: play_idle_precise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void play_idle_precise(u64 duration_ns, u64 latency_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117b840)
Location: kernel/sched/idle.c:367
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff8117b840-ffffffff8117b9d4: play_idle_precise (STB_GLOBAL)
```
</details>
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
