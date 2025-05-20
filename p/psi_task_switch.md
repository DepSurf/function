# Function: <code>psi_task_switch</code>

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
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d7c0)
Location: kernel/sched/psi.c:794
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8110d7c0-ffffffff8110d929: psi_task_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110aab0)
Location: kernel/sched/psi.c:810
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8110aab0-ffffffff8110ac19: psi_task_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110c6a0)
Location: kernel/sched/psi.c:817
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8110c6a0-ffffffff8110c8e8: psi_task_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112b700)
Location: kernel/sched/psi.c:829
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8112b700-ffffffff8112b91a: psi_task_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114be40)
Location: kernel/sched/psi.c:828
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8114be40-ffffffff8114c07e: psi_task_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117aab0)
Location: kernel/sched/psi.c:904
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8117aab0-ffffffff8117ad0a: psi_task_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118b610)
Location: kernel/sched/psi.c:927
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8118b610-ffffffff8118b873: psi_task_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void psi_task_switch(struct task_struct *prev, struct task_struct *next, bool sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81199f40)
Location: kernel/sched/psi.c:916
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81199f40-ffffffff8119a1a3: psi_task_switch (STB_GLOBAL)
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
