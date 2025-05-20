# Function: <code>set_tls_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d430)
Location: arch/x86/kernel/tls.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:do_set_thread_area
  - arch/x86/kernel/tls.c:regset_tls_set
```
**Symbols:**

```
ffffffff8103d430-ffffffff8103d5ba: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d180)
Location: arch/x86/kernel/tls.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff8103d180-ffffffff8103d323: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103ca70)
Location: arch/x86/kernel/tls.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff8103ca70-ffffffff8103cc13: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103aac0)
Location: arch/x86/kernel/tls.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff8103aac0-ffffffff8103ac5e: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103d4f0)
Location: arch/x86/kernel/tls.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff8103d4f0-ffffffff8103d684: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8103ea70)
Location: arch/x86/kernel/tls.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff8103ea70-ffffffff8103ebf6: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81040060)
Location: arch/x86/kernel/tls.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81040060-ffffffff810401e6: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81042700)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81042700-ffffffff8104288d: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81042e70)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81042e70-ffffffff81042ffd: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81046480)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81046480-ffffffff810465e8: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81045f20)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81045f20-ffffffff81046088: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81047940)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81047940-ffffffff81047aa6: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8104e1a0)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff8104e1a0-ffffffff8104e33b: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81059260)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81059260-ffffffff81059466: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81066ba0)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81066ba0-ffffffff81066d82: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff810682d0)
Location: arch/x86/kernel/tls.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff810682d0-ffffffff810684a0: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff8106f750)
Location: arch/x86/kernel/tls.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff8106f750-ffffffff8106f920: set_tls_desc (STB_LOCAL)
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
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81042ff0)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81042ff0-ffffffff8104317d: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81032600)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81032600-ffffffff81032791: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81042e30)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81042e30-ffffffff81042fbd: set_tls_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_tls_desc(struct task_struct *p, int idx, const struct user_desc *info, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tls.c (ffffffff81044300)
Location: arch/x86/kernel/tls.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:do_set_thread_area
```
**Symbols:**

```
ffffffff81044300-ffffffff810444a5: set_tls_desc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
