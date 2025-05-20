# Function: <code>security_task_setnice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e5a0)
Location: security/security.c:951
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8133e5a0-ffffffff8133e5ef: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373bb0)
Location: security/security.c:975
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81373bb0-ffffffff81373bff: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a4e0)
Location: security/security.c:996
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8138a4e0-ffffffff8138a52f: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f9d0)
Location: security/security.c:1633
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8139f9d0-ffffffff8139fa1f: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c55d0)
Location: security/security.c:1595
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff813c55d0-ffffffff813c5625: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5650)
Location: security/security.c:1099
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff813f5650-ffffffff813f5694: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410c80)
Location: security/security.c:1707
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81410c80-ffffffff81410cc4: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e460)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8143e460-ffffffff8143e4ad: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457ec0)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81457ec0-ffffffff81457f04: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aad50)
Location: security/security.c:1961
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff814aad50-ffffffff814aad94: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8350)
Location: security/security.c:1978
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff814c8350-ffffffff814c8394: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce990)
Location: security/security.c:2041
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff814ce990-ffffffff814ce9d4: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527650)
Location: security/security.c:2049
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81527650-ffffffff81527694: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc480)
Location: security/security.c:2055
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff815bc480-ffffffff815bc4dd: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668490)
Location: security/security.c:2107
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81668490-ffffffff816684ed: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0ae0)
Location: security/security.c:3432
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff816a0ae0-ffffffff816a0b3d: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd4b0)
Location: security/security.c:3491
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff816dd4b0-ffffffff816dd50d: security_task_setnice (STB_GLOBAL)
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
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543c18)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__arm64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffff800010543c18-ffff800010543c78: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9b70)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__se_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
c06f9b70-c06f9bcc: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006981d0)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__se_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
c0000000006981d0-c00000000069828c: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ffd8)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffe00039ffd8-ffffffe0003a001c: security_task_setnice (STB_GLOBAL)
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
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814504a0)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff814504a0-ffffffff814504e4: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440ef0)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81440ef0-ffffffff81440f34: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c540)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8144c540-ffffffff8144c584: security_task_setnice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct *p, int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463910)
Location: security/security.c:1765
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81463910-ffffffff81463954: security_task_setnice (STB_GLOBAL)
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
