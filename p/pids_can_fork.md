# Function: <code>pids_can_fork</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task, void **priv_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup_pids.c (ffffffff8111a460)
Location: kernel/cgroup_pids.c:212
Inline: False
```
**Symbols:**

```
ffffffff8111a460-ffffffff8111a506: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup_pids.c (ffffffff81122290)
Location: kernel/cgroup_pids.c:219
Inline: False
```
**Symbols:**

```
ffffffff81122290-ffffffff811223ab: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup_pids.c (ffffffff8112a8c0)
Location: kernel/cgroup_pids.c:219
Inline: False
```
**Symbols:**

```
ffffffff8112a8c0-ffffffff8112a9c5: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff8112b5c0)
Location: kernel/cgroup/pids.c:219
Inline: False
```
**Symbols:**

```
ffffffff8112b5c0-ffffffff8112b6be: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff811383c0)
Location: kernel/cgroup/pids.c:219
Inline: False
```
**Symbols:**

```
ffffffff811383c0-ffffffff811384be: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:219
Inline: False
```
**Symbols:**

```
ffffffff81146ce0-ffffffff81146dbb: pids_can_fork (STB_LOCAL)
ffffffff81147024-ffffffff81147050: pids_can_fork.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:219
Inline: False
```
**Symbols:**

```
ffffffff81152860-ffffffff8115293b: pids_can_fork (STB_LOCAL)
ffffffff81152ba4-ffffffff81152bd0: pids_can_fork.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:216
Inline: False
```
**Symbols:**

```
ffffffff8115eec0-ffffffff8115ef83: pids_can_fork (STB_LOCAL)
ffffffff8115f1f0-ffffffff8115f21c: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
ffffffff8116ab20-ffffffff8116abe6: pids_can_fork (STB_LOCAL)
ffffffff8116ae50-ffffffff8116ae7c: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:218
Inline: False
```
**Symbols:**

```
ffffffff8117c8a0-ffffffff8117c97f: pids_can_fork (STB_LOCAL)
ffffffff8117c97f-ffffffff8117c9ab: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:218
Inline: False
```
**Symbols:**

```
ffffffff81179750-ffffffff8117982f: pids_can_fork (STB_LOCAL)
ffffffff81be47c0-ffffffff81be47ec: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:218
Inline: False
```
**Symbols:**

```
ffffffff8117a2b0-ffffffff8117a38f: pids_can_fork (STB_LOCAL)
ffffffff81bd65e9-ffffffff81bd6615: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:218
Inline: False
```
**Symbols:**

```
ffffffff811a1bd0-ffffffff811a1caf: pids_can_fork (STB_LOCAL)
ffffffff81cb3203-ffffffff81cb322f: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:218
Inline: False
```
**Symbols:**

```
ffffffff811d25c0-ffffffff811d26bb: pids_can_fork (STB_LOCAL)
ffffffff81e64008-ffffffff81e64034: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff81216450)
Location: kernel/cgroup/pids.c:238
Inline: False
```
**Symbols:**

```
ffffffff81216450-ffffffff8121658a: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff8122bd90)
Location: kernel/cgroup/pids.c:238
Inline: False
```
**Symbols:**

```
ffffffff8122bd90-ffffffff8122beca: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task, struct css_set *cset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff81243dc0)
Location: kernel/cgroup/pids.c:238
Inline: False
```
**Symbols:**

```
ffffffff81243dc0-ffffffff81243efa: pids_can_fork (STB_LOCAL)
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
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffff8000101dec50)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
ffff8000101dec50-ffff8000101ded70: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (c04206b4)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
c04206b4-c04207ec: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (c00000000024cd50)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
c00000000024cd50-c00000000024ceb4: pids_can_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffe00015602a)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
ffffffe00015602a-ffffffe000156114: pids_can_fork (STB_LOCAL)
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
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
ffffffff81163140-ffffffff81163206: pids_can_fork (STB_LOCAL)
ffffffff81163470-ffffffff8116349c: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
ffffffff81156390-ffffffff81156456: pids_can_fork (STB_LOCAL)
ffffffff811566c0-ffffffff811566ec: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
ffffffff81160f10-ffffffff81160fd6: pids_can_fork (STB_LOCAL)
ffffffff81161240-ffffffff8116126c: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pids_can_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/pids.c (0)
Location: kernel/cgroup/pids.c:217
Inline: False
```
**Symbols:**

```
ffffffff8116e360-ffffffff8116e426: pids_can_fork (STB_LOCAL)
ffffffff8116e690-ffffffff8116e6bc: pids_can_fork.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void **priv_p</code>
</li>
</ul>
</details>
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
<code>struct css_set *cset</code>
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
