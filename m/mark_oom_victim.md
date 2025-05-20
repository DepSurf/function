# Function: <code>mark_oom_victim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190a20)
Location: mm/oom_kill.c:418
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
**Symbols:**

```
ffffffff81190a20-ffffffff81190a67: mark_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a4f10)
Location: mm/oom_kill.c:668
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
**Symbols:**

```
ffffffff811a4f10-ffffffff811a4f62: mark_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b4dd0)
Location: mm/oom_kill.c:652
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811b4dd0-ffffffff811b4e48: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bc0c0)
Location: mm/oom_kill.c:654
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811bc0c0-ffffffff811bc177: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d0cf0)
Location: mm/oom_kill.c:676
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811d0cf0-ffffffff811d0db0: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f1f90)
Location: mm/oom_kill.c:678
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811f1f90-ffffffff811f204f: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81203df0)
Location: mm/oom_kill.c:686
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81203df0-ffffffff81203eb1: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff8121b230-ffffffff8121b2ef: mark_oom_victim (STB_LOCAL)
ffffffff8121cfed-ffffffff8121d000: mark_oom_victim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81228cf0)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81228cf0-ffffffff81228db4: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81255b40)
Location: mm/oom_kill.c:698
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81255b40-ffffffff81255c04: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812607d0)
Location: mm/oom_kill.c:700
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff812607d0-ffffffff81260881: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81264f70)
Location: mm/oom_kill.c:699
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81264f70-ffffffff81265024: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:700
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff812a1790-ffffffff812a1857: mark_oom_victim (STB_LOCAL)
ffffffff81cba0d7-ffffffff81cba0ec: mark_oom_victim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff812f9490-ffffffff812f9576: mark_oom_victim (STB_LOCAL)
ffffffff81e6b820-ffffffff81e6b835: mark_oom_victim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:758
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81363210-ffffffff813632ea: mark_oom_victim (STB_LOCAL)
ffffffff8206241e-ffffffff82062433: mark_oom_victim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:758
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81395640-ffffffff81395719: mark_oom_victim (STB_LOCAL)
ffffffff820e1bf9-ffffffff820e1c0e: mark_oom_victim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:755
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff813bf400-ffffffff813bf4d9: mark_oom_victim (STB_LOCAL)
ffffffff821be61e-ffffffff821be633: mark_oom_victim.cold (STB_LOCAL)
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
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b7118)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffff8000102b7118-ffff8000102b72d0: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e3780)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
c04e3780-c04e38f4: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036e150)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
c00000000036e150-c00000000036e2dc: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001daf1a)
Location: mm/oom_kill.c:696
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffe0001daf1a-ffffffe0001db002: mark_oom_victim (STB_LOCAL)
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
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81221340)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81221340-ffffffff81221404: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812144f0)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff812144f0-ffffffff812145b4: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121f0e0)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff8121f0e0-ffffffff8121f1a4: mark_oom_victim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mark_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122e130)
Location: mm/oom_kill.c:696
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff8122e130-ffffffff8122e209: mark_oom_victim (STB_LOCAL)
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
