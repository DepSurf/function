# Function: <code>fill_stats_for_tgid</code>

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
In kernel/taskstats.c (ffffffff8113ea29)
Location: kernel/taskstats.c:209
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (ffffffff81147059)
Location: kernel/taskstats.c:209
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (ffffffff81150f01)
Location: kernel/taskstats.c:208
Inline: True
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
In kernel/taskstats.c (ffffffff8115338f)
Location: kernel/taskstats.c:209
Inline: True
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
In kernel/taskstats.c (ffffffff8115fb8f)
Location: kernel/taskstats.c:209
Inline: True
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
In kernel/taskstats.c (ffffffff8116eadf)
Location: kernel/taskstats.c:205
Inline: True
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
In kernel/taskstats.c (ffffffff8117c5df)
Location: kernel/taskstats.c:205
Inline: True
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
In kernel/taskstats.c (ffffffff81189482)
Location: kernel/taskstats.c:195
Inline: True
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
In kernel/taskstats.c (ffffffff811953c2)
Location: kernel/taskstats.c:195
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811aa2e0)
Location: kernel/taskstats.c:195
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811aa2e0-ffffffff811aa4c7: fill_stats_for_tgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a7880)
Location: kernel/taskstats.c:191
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811a7880-ffffffff811a7a71: fill_stats_for_tgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a8260)
Location: kernel/taskstats.c:191
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811a8260-ffffffff811a8451: fill_stats_for_tgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811d1b50)
Location: kernel/taskstats.c:191
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff811d1b50-ffffffff811d1d2d: fill_stats_for_tgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81206350)
Location: kernel/taskstats.c:213
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff81206350-ffffffff81206547: fill_stats_for_tgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8124e650)
Location: kernel/taskstats.c:213
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff8124e650-ffffffff8124e847: fill_stats_for_tgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81265a00)
Location: kernel/taskstats.c:213
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff81265a00-ffffffff81265bf7: fill_stats_for_tgid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fill_stats_for_tgid(pid_t tgid, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8127f880)
Location: kernel/taskstats.c:213
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff8127f880-ffffffff8127fab6: fill_stats_for_tgid (STB_LOCAL)
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
In kernel/taskstats.c (ffff80001020d680)
Location: kernel/taskstats.c:195
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (c044c07c)
Location: kernel/taskstats.c:195
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (c00000000028b680)
Location: kernel/taskstats.c:195
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (ffffffe00016e6e2)
Location: kernel/taskstats.c:195
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
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
In kernel/taskstats.c (ffffffff8118d9e2)
Location: kernel/taskstats.c:195
Inline: True
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
In kernel/taskstats.c (ffffffff81180b03)
Location: kernel/taskstats.c:195
Inline: True
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
In kernel/taskstats.c (ffffffff8118b7b2)
Location: kernel/taskstats.c:195
Inline: True
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
In kernel/taskstats.c (ffffffff81199122)
Location: kernel/taskstats.c:195
Inline: True
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
