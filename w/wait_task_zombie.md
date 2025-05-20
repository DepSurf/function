# Function: <code>wait_task_zombie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81082c5a)
Location: kernel/exit.c:971
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81085cc9)
Location: kernel/exit.c:1057
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108ac39)
Location: kernel/exit.c:1047
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81087b3f)
Location: kernel/exit.c:1052
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e8cf)
Location: kernel/exit.c:1051
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109242c)
Location: kernel/exit.c:1051
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109a73a)
Location: kernel/exit.c:1054
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e9e0)
Location: kernel/exit.c:1058
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8109e9e0-ffffffff8109ef27: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a4f70)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a4f70-ffffffff810a54b7: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810accc0)
Location: kernel/exit.c:978
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810accc0-ffffffff810ad2cf: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8380)
Location: kernel/exit.c:997
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a8380-ffffffff810a8998: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9240)
Location: kernel/exit.c:997
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a9240-ffffffff810a97ff: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bad30)
Location: kernel/exit.c:997
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810bad30-ffffffff810bb2ef: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d16f0)
Location: kernel/exit.c:1000
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810d16f0-ffffffff810d1cbe: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f0140)
Location: kernel/exit.c:1094
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810f0140-ffffffff810f070e: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fc100)
Location: kernel/exit.c:1099
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810fc100-ffffffff810fc6ce: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81105810)
Location: kernel/exit.c:1075
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff81105810-ffffffff81105dc2: wait_task_zombie (STB_LOCAL)
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
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fae70)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffff8000100fae70-ffff8000100fb45c: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0358cc4)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
c0358cc4-c0359438: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000142200)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
c000000000142200-c000000000142884: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c4bdc)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffe0000c4bdc-ffffffe0000c505a: wait_task_zombie (STB_LOCAL)
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
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e890)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8109e890-ffffffff8109edd7: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108d2c0)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8108d2c0-ffffffff8108d819: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e840)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff8109e840-ffffffff8109ed87: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wait_task_zombie(struct wait_opts *wo, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6760)
Location: kernel/exit.c:974
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a6760-ffffffff810a6ccc: wait_task_zombie (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
