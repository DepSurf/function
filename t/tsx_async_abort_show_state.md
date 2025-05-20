# Function: <code>tsx_async_abort_show_state</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047e2e)
Location: arch/x86/kernel/cpu/bugs.c:1477
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b9c0)
Location: arch/x86/kernel/cpu/bugs.c:1599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff8104b9c0-ffffffff8104ba36: tsx_async_abort_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104af00)
Location: arch/x86/kernel/cpu/bugs.c:1607
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff8104af00-ffffffff8104af76: tsx_async_abort_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c7e0)
Location: arch/x86/kernel/cpu/bugs.c:1607
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff8104c7e0-ffffffff8104c856: tsx_async_abort_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81053bc0)
Location: arch/x86/kernel/cpu/bugs.c:1762
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff81053bc0-ffffffff81053cbf: tsx_async_abort_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8105f6e0)
Location: arch/x86/kernel/cpu/bugs.c:2264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff8105f6e0-ffffffff8105f812: tsx_async_abort_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106de70)
Location: arch/x86/kernel/cpu/bugs.c:2315
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff8106de70-ffffffff8106dfa2: tsx_async_abort_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f790)
Location: arch/x86/kernel/cpu/bugs.c:2590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff8106f790-ffffffff8106f8c2: tsx_async_abort_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tsx_async_abort_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81076b50)
Location: arch/x86/kernel/cpu/bugs.c:2728
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_tsx_async_abort
```
**Symbols:**

```
ffffffff81076b50-ffffffff81076c82: tsx_async_abort_show_state (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047f9e)
Location: arch/x86/kernel/cpu/bugs.c:1477
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810372ae)
Location: arch/x86/kernel/cpu/bugs.c:1477
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047dde)
Location: arch/x86/kernel/cpu/bugs.c:1477
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810491ee)
Location: arch/x86/kernel/cpu/bugs.c:1477
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
