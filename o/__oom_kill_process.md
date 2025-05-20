# Function: <code>__oom_kill_process</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __oom_kill_process(struct task_struct *victim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:846
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812048c0-ffffffff81204a0e: __oom_kill_process (STB_LOCAL)
ffffffff81205bd3-ffffffff81205cbd: __oom_kill_process.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121c030)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8121c030-ffffffff8121c2bf: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812299c0)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812299c0-ffffffff81229c8b: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81256770)
Location: mm/oom_kill.c:858
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81256770-ffffffff81256aff: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:860
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81261390-ffffffff8126170c: __oom_kill_process (STB_LOCAL)
ffffffff81be6c98-ffffffff81be6cf9: __oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:859
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81265bd0-ffffffff81265f31: __oom_kill_process (STB_LOCAL)
ffffffff81bd8a31-ffffffff81bd8a92: __oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:860
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812a2400-ffffffff812a275b: __oom_kill_process (STB_LOCAL)
ffffffff81cba310-ffffffff81cba371: __oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812f9f00)
Location: mm/oom_kill.c:917
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812f9f00-ffffffff812fa389: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81364630)
Location: mm/oom_kill.c:916
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81364630-ffffffff81364aea: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81396b00)
Location: mm/oom_kill.c:916
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81396b00-ffffffff81396fad: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c0870)
Location: mm/oom_kill.c:913
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff813c0870-ffffffff813c0d1d: __oom_kill_process (STB_LOCAL)
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
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b7738)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffff8000102b7738-ffff8000102b7afc: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e4398)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c04e4398-c04e4740: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036f4f0)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
c00000000036f4f0-c00000000036f908: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dba42)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffe0001dba42-ffffffe0001dbd5c: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81222010)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff81222010-ffffffff812222db: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812151c0)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812151c0-ffffffff8121548b: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121fdb0)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8121fdb0-ffffffff8122007b: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct *victim, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122ee90)
Location: mm/oom_kill.c:856
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff8122ee90-ffffffff8122f183: __oom_kill_process (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *message</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
