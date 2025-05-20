# Function: <code>__rdgsbase_inactive</code>

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
long unsigned int __rdgsbase_inactive();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c35100)
Location: arch/x86/kernel/process_64.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
**Symbols:**

```
ffffffff81c35100-ffffffff81c35123: __rdgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __rdgsbase_inactive();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c275a0)
Location: arch/x86/kernel/process_64.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
**Symbols:**

```
ffffffff81c275a0-ffffffff81c275c3: __rdgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __rdgsbase_inactive();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81d455f0)
Location: arch/x86/kernel/process_64.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
**Symbols:**

```
ffffffff81d455f0-ffffffff81d45613: __rdgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __rdgsbase_inactive();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81f137c0)
Location: arch/x86/kernel/process_64.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
**Symbols:**

```
ffffffff81f137c0-ffffffff81f13812: __rdgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __rdgsbase_inactive();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff820ba970)
Location: arch/x86/kernel/process_64.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
**Symbols:**

```
ffffffff820ba970-ffffffff820ba9c2: __rdgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __rdgsbase_inactive();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8213c080)
Location: arch/x86/kernel/process_64.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
**Symbols:**

```
ffffffff8213c080-ffffffff8213c0d2: __rdgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __rdgsbase_inactive();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8221e080)
Location: arch/x86/kernel/process_64.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
```
**Symbols:**

```
ffffffff8221e080-ffffffff8221e0d2: __rdgsbase_inactive (STB_LOCAL)
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
