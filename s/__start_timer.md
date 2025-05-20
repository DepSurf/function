# Function: <code>__start_timer</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045830)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81045830-ffffffff8104588b: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045970)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1357
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81045970-ffffffff810459cb: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049e70)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1367
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81049e70-ffffffff81049ecb: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c4a0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1345
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104c4a0-ffffffff8104c4fb: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049b90)
Location: arch/x86/kernel/cpu/mce/core.c:1361
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81049b90-ffffffff81049beb: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cd20)
Location: arch/x86/kernel/cpu/mce/core.c:1394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104cd20-ffffffff8104cd7a: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d6c0)
Location: arch/x86/kernel/cpu/mce/core.c:1394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104d6c0-ffffffff8104d71a: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810522f0)
Location: arch/x86/kernel/cpu/mce/core.c:1397
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff810522f0-ffffffff8105234c: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810514d0)
Location: arch/x86/kernel/cpu/mce/core.c:1472
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff810514d0-ffffffff8105152c: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053880)
Location: arch/x86/kernel/cpu/mce/core.c:1484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81053880-ffffffff810538e6: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c0a0)
Location: arch/x86/kernel/cpu/mce/core.c:1545
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8105c0a0-ffffffff8105c106: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067150)
Location: arch/x86/kernel/cpu/mce/core.c:1608
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81067150-ffffffff810671b7: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810766b0)
Location: arch/x86/kernel/cpu/mce/core.c:1608
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff810766b0-ffffffff81076721: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078930)
Location: arch/x86/kernel/cpu/mce/core.c:1621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81078930-ffffffff810789a1: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fde0)
Location: arch/x86/kernel/cpu/mce/core.c:1645
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8107fde0-ffffffff8107fe51: __start_timer (STB_LOCAL)
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
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d820)
Location: arch/x86/kernel/cpu/mce/core.c:1394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104d820-ffffffff8104d87a: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c000)
Location: arch/x86/kernel/cpu/mce/core.c:1394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8103c000-ffffffff8103c044: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d670)
Location: arch/x86/kernel/cpu/mce/core.c:1394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104d670-ffffffff8104d6ca: __start_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __start_timer(struct timer_list *t, long unsigned int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104eab0)
Location: arch/x86/kernel/cpu/mce/core.c:1394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_start_timer
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_kick
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff8104eab0-ffffffff8104eb0a: __start_timer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
