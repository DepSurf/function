# Function: <code>__pm_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d2126)
Location: kernel/power/main.c:41
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810d20e0-ffffffff810d211a: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d8cd6)
Location: kernel/power/main.c:41
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810d8c90-ffffffff810d8cca: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d7cd6)
Location: kernel/power/main.c:41
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810d7c90-ffffffff810d7cca: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810dfd26)
Location: kernel/power/main.c:41
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810dfce0-ffffffff810dfd1a: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e83c5)
Location: kernel/power/main.c:70
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810e8380-ffffffff810e83ba: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f39d5)
Location: kernel/power/main.c:70
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810f3990-ffffffff810f39ca: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fbec5)
Location: kernel/power/main.c:82
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810fbe80-ffffffff810fbeb8: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811082e5)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811082a0-ffffffff811082d8: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112ed5)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81112e90-ffffffff81112ec8: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016f568)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffff80001016f4e8-ffff80001016f54c: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03ba1cc)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
c03ba168-c03ba1b4: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c744c)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
c0000000001c73a0-c0000000001c7424: __pm_notifier_call_chain (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81101425)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811013e0-ffffffff81101418: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f17e5)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810f17a0-ffffffff810f17d8: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fe7b5)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810fe770-ffffffff810fe7a8: __pm_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __pm_notifier_call_chain(long unsigned int val, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81109a75)
Location: kernel/power/main.c:83
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81109a30-ffffffff81109a68: __pm_notifier_call_chain (STB_GLOBAL)
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
