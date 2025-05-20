# Function: <code>pm_notifier_call_chain_robust</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_notifier_call_chain_robust(long unsigned int val_up, long unsigned int val_down);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110ff60)
Location: kernel/power/main.c:83
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8110ff60-ffffffff8110ff96: pm_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_notifier_call_chain_robust(long unsigned int val_up, long unsigned int val_down);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811109a0)
Location: kernel/power/main.c:83
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811109a0-ffffffff811109d5: pm_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_notifier_call_chain_robust(long unsigned int val_up, long unsigned int val_down);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81130450)
Location: kernel/power/main.c:83
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81130450-ffffffff81130485: pm_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_notifier_call_chain_robust(long unsigned int val_up, long unsigned int val_down);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81151c70)
Location: kernel/power/main.c:83
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81151c70-ffffffff81151cb1: pm_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_notifier_call_chain_robust(long unsigned int val_up, long unsigned int val_down);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811809f0)
Location: kernel/power/main.c:86
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811809f0-ffffffff81180a31: pm_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_notifier_call_chain_robust(long unsigned int val_up, long unsigned int val_down);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811918e0)
Location: kernel/power/main.c:127
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811918e0-ffffffff81191921: pm_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_notifier_call_chain_robust(long unsigned int val_up, long unsigned int val_down);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811a02a0)
Location: kernel/power/main.c:111
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811a02a0-ffffffff811a02e1: pm_notifier_call_chain_robust (STB_GLOBAL)
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
