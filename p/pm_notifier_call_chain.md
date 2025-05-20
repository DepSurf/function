# Function: <code>pm_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810cd650)
Location: kernel/power/main.c:41
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810cd650-ffffffff810cd681: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d2120)
Location: kernel/power/main.c:50
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810d2120-ffffffff810d215d: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d8cd0)
Location: kernel/power/main.c:50
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810d8cd0-ffffffff810d8d0d: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d7cd0)
Location: kernel/power/main.c:50
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810d7cd0-ffffffff810d7d0d: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810dfd20)
Location: kernel/power/main.c:50
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810dfd20-ffffffff810dfd5d: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e83c0)
Location: kernel/power/main.c:79
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810e83c0-ffffffff810e83fd: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f39d0)
Location: kernel/power/main.c:79
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810f39d0-ffffffff810f3a0d: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fbec0)
Location: kernel/power/main.c:91
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810fbec0-ffffffff810fbefb: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811082e0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811082e0-ffffffff8110831b: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112ed0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81112ed0-ffffffff81112f0b: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110ffa0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff8110ffa0-ffffffff8110ffbc: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811109e0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811109e0-ffffffff811109fc: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81130490)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81130490-ffffffff811304ac: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81151cc0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81151cc0-ffffffff81151ce6: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81180a50)
Location: kernel/power/main.c:95
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81180a50-ffffffff81180a76: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81191940)
Location: kernel/power/main.c:136
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81191940-ffffffff81191966: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811a0300)
Location: kernel/power/main.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff811a0300-ffffffff811a0326: pm_notifier_call_chain (STB_GLOBAL)
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
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016f550)
Location: kernel/power/main.c:92
Inline: False
```
**Symbols:**

```
ffff80001016f550-ffff80001016f5a4: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03ba1b4)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
c03ba1b4-c03ba204: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c7430)
Location: kernel/power/main.c:92
Inline: False
```
**Symbols:**

```
c0000000001c7430-c0000000001c74a4: pm_notifier_call_chain (STB_GLOBAL)
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
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81101420)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81101420-ffffffff8110145b: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f17e0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810f17e0-ffffffff810f181b: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fe7b0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff810fe7b0-ffffffff810fe7eb: pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm_notifier_call_chain(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81109a70)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
ffffffff81109a70-ffffffff81109aab: pm_notifier_call_chain (STB_GLOBAL)
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
