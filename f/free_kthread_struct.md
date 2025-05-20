# Function: <code>free_kthread_struct</code>

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
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9a90)
Location: kernel/kthread.c:72
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810a9a90-ffffffff810a9ad2: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6710)
Location: kernel/kthread.c:75
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810a6710-ffffffff810a673d: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ace80)
Location: kernel/kthread.c:77
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810ace80-ffffffff810aceaf: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3bf0)
Location: kernel/kthread.c:76
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810b3bf0-ffffffff810b3c1f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bcd40)
Location: kernel/kthread.c:76
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810bcd40-ffffffff810bcd6f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810c338f-ffffffff810c33a2: free_kthread_struct.cold (STB_LOCAL)
ffffffff810c2c00-ffffffff810c2c34: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c91e0)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810c91e0-ffffffff810c920f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d1600)
Location: kernel/kthread.c:86
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810d1600-ffffffff810d162f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc030)
Location: kernel/kthread.c:87
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810cc030-ffffffff810cc05f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cdb10)
Location: kernel/kthread.c:112
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810cdb10-ffffffff810cdb3f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0cf0)
Location: kernel/kthread.c:112
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810e0cf0-ffffffff810e0d1f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fafc0)
Location: kernel/kthread.c:129
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810fafc0-ffffffff810fb013: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111de60)
Location: kernel/kthread.c:129
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8111de60-ffffffff8111deb3: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112b060)
Location: kernel/kthread.c:130
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8112b060-ffffffff8112b0b3: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811357b0)
Location: kernel/kthread.c:130
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff811357b0-ffffffff81135803: free_kthread_struct (STB_GLOBAL)
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
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128df0)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffff800010128df0-ffff800010128e3c: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b350)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
c037b350-c037b3e4: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001735f0)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
c0000000001735f0-c000000000173650: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfd26)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffe0000dfd26-ffffffe0000dfd68: free_kthread_struct (STB_GLOBAL)
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
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3560)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810c3560-ffffffff810c358f: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1d90)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810b1d90-ffffffff810b1dbf: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2ab0)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810c2ab0-ffffffff810c2adf: free_kthread_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_kthread_struct(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caef0)
Location: kernel/kthread.c:79
Inline: False
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff810caef0-ffffffff810caf1f: free_kthread_struct (STB_GLOBAL)
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
