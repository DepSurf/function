# Function: <code>task_will_free_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811909f4)
Location: include/linux/oom.h:105
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/memcontrol.c (ffffffff811fe8e9)
Location: include/linux/oom.h:105
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a52b0)
Location: mm/oom_kill.c:763
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
**Symbols:**

```
ffffffff811a52b0-ffffffff811a53b9: task_will_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b4fa0)
Location: mm/oom_kill.c:760
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811b4fa0-ffffffff811b50a9: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bc470)
Location: mm/oom_kill.c:765
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811bc470-ffffffff811bc574: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1070)
Location: mm/oom_kill.c:789
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811d1070-ffffffff811d1174: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f22a0)
Location: mm/oom_kill.c:791
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff811f22a0-ffffffff811f23a4: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81204110)
Location: mm/oom_kill.c:799
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81204110-ffffffff81204222: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121b4e0)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8121b4e0-ffffffff8121b612: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81228e70)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81228e70-ffffffff81228fa2: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81255a00)
Location: mm/oom_kill.c:811
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81255a00-ffffffff81255b34: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81260680)
Location: mm/oom_kill.c:813
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81260680-ffffffff812607c7: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81265270)
Location: mm/oom_kill.c:812
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81265270-ffffffff812653b7: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a1aa0)
Location: mm/oom_kill.c:813
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812a1aa0-ffffffff812a1be7: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812f9980)
Location: mm/oom_kill.c:870
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812f9980-ffffffff812f9b21: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81363af0)
Location: mm/oom_kill.c:869
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81363af0-ffffffff81363c91: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81395fc0)
Location: mm/oom_kill.c:869
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81395fc0-ffffffff81396164: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813bfd80)
Location: mm/oom_kill.c:866
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff813bfd80-ffffffff813bff21: task_will_free_mem (STB_LOCAL)
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
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b61d8)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffff8000102b61d8-ffff8000102b6308: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e38f4)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c04e38f4-c04e3a38: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036e5a0)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c00000000036e5a0-c00000000036e6e8: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001db002)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffe0001db002-ffffffe0001db0ec: task_will_free_mem (STB_LOCAL)
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
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812214c0)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812214c0-ffffffff812215f2: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81214670)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81214670-ffffffff812147a2: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121f260)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8121f260-ffffffff8121f392: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool task_will_free_mem(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122e2d0)
Location: mm/oom_kill.c:809
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8122e2d0-ffffffff8122e428: task_will_free_mem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
