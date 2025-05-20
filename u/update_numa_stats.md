# Function: <code>update_numa_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b23f0)
Location: kernel/sched/fair.c:1139
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b23f0-ffffffff810b24f2: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4f10)
Location: kernel/sched/fair.c:1282
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b4f10-ffffffff810b5012: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb3d0)
Location: kernel/sched/fair.c:1406
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810bb3d0-ffffffff810bb4d5: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b6670)
Location: kernel/sched/fair.c:1402
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b6670-ffffffff810b6774: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd880)
Location: kernel/sched/fair.c:1443
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810bd880-ffffffff810bd974: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5710)
Location: kernel/sched/fair.c:1471
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810c5710-ffffffff810c5804: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce440)
Location: kernel/sched/fair.c:1471
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810ce440-ffffffff810ce4c3: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6440)
Location: kernel/sched/fair.c:1532
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d6440-ffffffff810d64b9: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0a20)
Location: kernel/sched/fair.c:1490
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810e0a20-ffffffff810e0a99: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebea0)
Location: kernel/sched/fair.c:1601
Inline: False
```
**Symbols:**

```
ffffffff810ebea0-ffffffff810ec15a: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea2c0)
Location: kernel/sched/fair.c:1613
Inline: False
```
**Symbols:**

```
ffffffff810ea2c0-ffffffff810ea5a4: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea540)
Location: kernel/sched/fair.c:1610
Inline: False
```
**Symbols:**

```
ffffffff810ea540-ffffffff810ea857: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81101f20)
Location: kernel/sched/fair.c:1599
Inline: False
```
**Symbols:**

```
ffffffff81101f20-ffffffff81102361: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111ceb0)
Location: kernel/sched/fair.c:1602
Inline: False
```
**Symbols:**

```
ffffffff8111ceb0-ffffffff8111d317: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81146700)
Location: kernel/sched/fair.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81146700-ffffffff81146bbc: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81154350)
Location: kernel/sched/fair.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81154350-ffffffff81154702: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_numa_stats(struct task_numa_env *env, struct numa_stats *ns, int nid, bool find_idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811603a0)
Location: kernel/sched/fair.c:2029
Inline: False
```
**Symbols:**

```
ffffffff811603a0-ffffffff81160752: update_numa_stats (STB_LOCAL)
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
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010140868)
Location: kernel/sched/fair.c:1490
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffff800010140868-ffff800010140918: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001908a0)
Location: kernel/sched/fair.c:1490
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
c0000000001908a0-c00000000019098c: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dabd0)
Location: kernel/sched/fair.c:1490
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810dabd0-ffffffff810dac49: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9be0)
Location: kernel/sched/fair.c:1490
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810c9be0-ffffffff810c9c59: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6f50)
Location: kernel/sched/fair.c:1490
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d6f50-ffffffff810d6fc9: update_numa_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_numa_stats(struct numa_stats *ns, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2900)
Location: kernel/sched/fair.c:1490
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810e2900-ffffffff810e2979: update_numa_stats (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_numa_env *env</code>
</li>
<li>
<b>Param added. </b>
<code>bool find_idle</code>
</li>
<li>
<b>Param reordered. </b>
<code>ns, nid</code> ➡️ <code>env, ns, nid, find_idle</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
