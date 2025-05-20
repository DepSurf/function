# Function: <code>__wrgsbase_inactive</code>

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
void __wrgsbase_inactive(long unsigned int gsbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c350d0)
Location: arch/x86/kernel/process_64.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
**Symbols:**

```
ffffffff81c350d0-ffffffff81c350fc: __wrgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wrgsbase_inactive(long unsigned int gsbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c27570)
Location: arch/x86/kernel/process_64.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
**Symbols:**

```
ffffffff81c27570-ffffffff81c2759c: __wrgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wrgsbase_inactive(long unsigned int gsbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81d455c0)
Location: arch/x86/kernel/process_64.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
**Symbols:**

```
ffffffff81d455c0-ffffffff81d455ec: __wrgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wrgsbase_inactive(long unsigned int gsbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81f13760)
Location: arch/x86/kernel/process_64.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
**Symbols:**

```
ffffffff81f13760-ffffffff81f137bf: __wrgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wrgsbase_inactive(long unsigned int gsbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff820ba900)
Location: arch/x86/kernel/process_64.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
**Symbols:**

```
ffffffff820ba900-ffffffff820ba95f: __wrgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wrgsbase_inactive(long unsigned int gsbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8213c010)
Location: arch/x86/kernel/process_64.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
**Symbols:**

```
ffffffff8213c010-ffffffff8213c06f: __wrgsbase_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wrgsbase_inactive(long unsigned int gsbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8221e010)
Location: arch/x86/kernel/process_64.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
**Symbols:**

```
ffffffff8221e010-ffffffff8221e06f: __wrgsbase_inactive (STB_LOCAL)
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
