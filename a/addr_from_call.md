# Function: <code>addr_from_call</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105aad0)
Location: arch/x86/kernel/ftrace.c:860
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8105aad0-ffffffff8105ab92: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105a990)
Location: arch/x86/kernel/ftrace.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8105a990-ffffffff8105aa52: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105d7b0)
Location: arch/x86/kernel/ftrace.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8105d7b0-ffffffff8105d872: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105ceb0)
Location: arch/x86/kernel/ftrace.c:880
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8105ceb0-ffffffff8105cf26: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81060b50)
Location: arch/x86/kernel/ftrace.c:881
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff81060b50-ffffffff81060bc6: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81063c70)
Location: arch/x86/kernel/ftrace.c:881
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff81063c70-ffffffff81063ce7: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81069970)
Location: arch/x86/kernel/ftrace.c:871
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff81069970-ffffffff810699e7: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8106d150-ffffffff8106d1b6: addr_from_call (STB_LOCAL)
ffffffff8106de5a-ffffffff8106de72: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8106e7c0-ffffffff8106e826: addr_from_call (STB_LOCAL)
ffffffff8106f46a-ffffffff8106f482: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:504
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff81075f50-ffffffff81075fb5: addr_from_call (STB_LOCAL)
ffffffff8107660c-ffffffff81076624: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:512
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff81076580-ffffffff810765e5: addr_from_call (STB_LOCAL)
ffffffff81bd79ed-ffffffff81bd7a05: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:512
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff81077000-ffffffff81077065: addr_from_call (STB_LOCAL)
ffffffff81bc99a3-ffffffff81bc99bb: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:512
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff810847e0-ffffffff81084845: addr_from_call (STB_LOCAL)
ffffffff81c9e80f-ffffffff81c9e827: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:504
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff81094990-ffffffff81094a0a: addr_from_call (STB_LOCAL)
ffffffff81e4dc7f-ffffffff81e4dc95: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810aa110)
Location: arch/x86/kernel/ftrace.c:510
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff810aa110-ffffffff810aa19a: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810ad4d0)
Location: arch/x86/kernel/ftrace.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff810ad4d0-ffffffff810ad55a: addr_from_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810b4050)
Location: arch/x86/kernel/ftrace.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff810b4050-ffffffff810b40da: addr_from_call (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8106d760-ffffffff8106d7c6: addr_from_call (STB_LOCAL)
ffffffff8106e40a-ffffffff8106e422: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8105db80-ffffffff8105dbe6: addr_from_call (STB_LOCAL)
ffffffff8105e82a-ffffffff8105e842: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8106dc10-ffffffff8106dc76: addr_from_call (STB_LOCAL)
ffffffff8106e8ba-ffffffff8106e8d2: addr_from_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *addr_from_call(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/kernel/ftrace.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_func
```
**Symbols:**

```
ffffffff8106fe90-ffffffff8106fef6: addr_from_call (STB_LOCAL)
ffffffff81070b3a-ffffffff81070b52: addr_from_call.cold (STB_LOCAL)
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
