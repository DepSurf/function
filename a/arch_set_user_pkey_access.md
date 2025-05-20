# Function: <code>arch_set_user_pkey_access</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b300)
Location: arch/x86/kernel/fpu/xstate.c:876
Inline: False
```
**Symbols:**

```
ffffffff8103b300-ffffffff8103b3b2: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103abe0)
Location: arch/x86/kernel/fpu/xstate.c:882
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:SyS_pkey_alloc
```
**Symbols:**

```
ffffffff8103abe0-ffffffff8103ac52: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038a50)
Location: arch/x86/kernel/fpu/xstate.c:889
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:SyS_pkey_alloc
```
**Symbols:**

```
ffffffff81038a50-ffffffff81038abf: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103abc0)
Location: arch/x86/kernel/fpu/xstate.c:916
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:SyS_pkey_alloc
```
**Symbols:**

```
ffffffff8103abc0-ffffffff8103ac30: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c0c0)
Location: arch/x86/kernel/fpu/xstate.c:916
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff8103c0c0-ffffffff8103c123: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d540)
Location: arch/x86/kernel/fpu/xstate.c:914
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff8103d540-ffffffff8103d5a3: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fde0)
Location: arch/x86/kernel/fpu/xstate.c:904
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff8103fde0-ffffffff8103fe98: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040500)
Location: arch/x86/kernel/fpu/xstate.c:904
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81040500-ffffffff810405b8: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043880)
Location: arch/x86/kernel/fpu/xstate.c:954
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81043880-ffffffff81043966: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043930)
Location: arch/x86/kernel/fpu/xstate.c:994
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__do_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81043930-ffffffff81043a16: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045180)
Location: arch/x86/kernel/fpu/xstate.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__do_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81045180-ffffffff8104525a: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:915
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__do_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81c9a587-ffffffff81c9a5ba: arch_set_user_pkey_access.cold (STB_LOCAL)
ffffffff8104b660-ffffffff8104b71a: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:1002
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__do_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81e499a5-ffffffff81e499d8: arch_set_user_pkey_access.cold (STB_LOCAL)
ffffffff81056340-ffffffff81056401: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:997
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
```
**Symbols:**

```
ffffffff820526ca-ffffffff820526fd: arch_set_user_pkey_access.cold (STB_LOCAL)
ffffffff81063fd0-ffffffff81064094: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:1004
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
```
**Symbols:**

```
ffffffff820d0b98-ffffffff820d0bcb: arch_set_user_pkey_access.cold (STB_LOCAL)
ffffffff81065920-ffffffff810659e4: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:1000
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
```
**Symbols:**

```
ffffffff821ab6c1-ffffffff821ab6f4: arch_set_user_pkey_access.cold (STB_LOCAL)
ffffffff8106cd80-ffffffff8106ce44: arch_set_user_pkey_access (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040680)
Location: arch/x86/kernel/fpu/xstate.c:904
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81040680-ffffffff81040738: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fe60)
Location: arch/x86/kernel/fpu/xstate.c:904
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff8102fe60-ffffffff8102ff18: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810404c0)
Location: arch/x86/kernel/fpu/xstate.c:904
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff810404c0-ffffffff81040578: arch_set_user_pkey_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_set_user_pkey_access(struct task_struct *tsk, int pkey, long unsigned int init_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041890)
Location: arch/x86/kernel/fpu/xstate.c:904
Inline: False
Direct callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
**Symbols:**

```
ffffffff81041890-ffffffff81041959: arch_set_user_pkey_access (STB_GLOBAL)
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
