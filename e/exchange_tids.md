# Function: <code>exchange_tids</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce1d0)
Location: kernel/pid.c:367
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810ce1d0-ffffffff810ce237: exchange_tids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8ca0)
Location: kernel/pid.c:368
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c8ca0-ffffffff810c8d07: exchange_tids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca740)
Location: kernel/pid.c:368
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810ca740-ffffffff810ca7a7: exchange_tids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd630)
Location: kernel/pid.c:368
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810dd630-ffffffff810dd697: exchange_tids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f6f40)
Location: kernel/pid.c:368
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810f6f40-ffffffff810f6fbb: exchange_tids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119670)
Location: kernel/pid.c:368
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81119670-ffffffff811196eb: exchange_tids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126b50)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81126b50-ffffffff81126bcb: exchange_tids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exchange_tids(struct task_struct *left, struct task_struct *right);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81131130)
Location: kernel/pid.c:371
Inline: False
Direct callers:
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81131130-ffffffff811311ab: exchange_tids (STB_GLOBAL)
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
