# Function: <code>mds_show_state</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047488)
Location: arch/x86/kernel/cpu/bugs.c:1314
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047bf3)
Location: arch/x86/kernel/cpu/bugs.c:1460
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b930)
Location: arch/x86/kernel/cpu/bugs.c:1582
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff8104b930-ffffffff8104b9bb: mds_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104ae70)
Location: arch/x86/kernel/cpu/bugs.c:1590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff8104ae70-ffffffff8104aefb: mds_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c750)
Location: arch/x86/kernel/cpu/bugs.c:1590
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff8104c750-ffffffff8104c7dc: mds_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81053ab0)
Location: arch/x86/kernel/cpu/bugs.c:1745
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff81053ab0-ffffffff81053bbd: mds_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8105f5b0)
Location: arch/x86/kernel/cpu/bugs.c:2247
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff8105f5b0-ffffffff8105f6d8: mds_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106dd30)
Location: arch/x86/kernel/cpu/bugs.c:2298
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff8106dd30-ffffffff8106de58: mds_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f650)
Location: arch/x86/kernel/cpu/bugs.c:2573
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff8106f650-ffffffff8106f777: mds_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t mds_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81076a10)
Location: arch/x86/kernel/cpu/bugs.c:2711
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_mds
```
**Symbols:**

```
ffffffff81076a10-ffffffff81076b38: mds_show_state (STB_LOCAL)
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81047d63)
Location: arch/x86/kernel/cpu/bugs.c:1460
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81037073)
Location: arch/x86/kernel/cpu/bugs.c:1460
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81047ba3)
Location: arch/x86/kernel/cpu/bugs.c:1460
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81048fb3)
Location: arch/x86/kernel/cpu/bugs.c:1460
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
