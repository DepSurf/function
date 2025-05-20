# Function: <code>security_ptrace_access_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133cbf0)
Location: security/security.c:156
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8133cbf0-ffffffff8133cc3f: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372220)
Location: security/security.c:157
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81372220-ffffffff8137226f: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388b50)
Location: security/security.c:157
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81388b50-ffffffff81388b9f: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139dec0)
Location: security/security.c:728
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8139dec0-ffffffff8139df0f: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3830)
Location: security/security.c:678
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff813c3830-ffffffff813c3885: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3f50)
Location: security/security.c:255
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff813f3f50-ffffffff813f3f94: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f380)
Location: security/security.c:741
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8140f380-ffffffff8140f3c4: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c7d0)
Location: security/security.c:740
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8143c7d0-ffffffff8143c81d: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456340)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81456340-ffffffff81456384: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9100)
Location: security/security.c:917
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff814a9100-ffffffff814a9144: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6700)
Location: security/security.c:919
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff814c6700-ffffffff814c6744: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc7f0)
Location: security/security.c:943
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff814cc7f0-ffffffff814cc834: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525970)
Location: security/security.c:943
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81525970-ffffffff815259b4: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9b70)
Location: security/security.c:942
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff815b9b70-ffffffff815b9bcd: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665370)
Location: security/security.c:940
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81665370-ffffffff816653cd: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169d8f0)
Location: security/security.c:998
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8169d8f0-ffffffff8169d94d: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816da220)
Location: security/security.c:1041
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff816da220-ffffffff816da27d: security_ptrace_access_check (STB_GLOBAL)
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
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541b48)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffff800010541b48-ffff800010541ba8: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7b34)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
c06f7b34-c06f7b90: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000694540)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
c000000000694540-c0000000006945fc: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e724)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffe00039e724-ffffffe00039e768: security_ptrace_access_check (STB_GLOBAL)
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
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e920)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8144e920-ffffffff8144e964: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f370)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8143f370-ffffffff8143f3b4: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a9c0)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8144a9c0-ffffffff8144aa04: security_ptrace_access_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461d90)
Location: security/security.c:774
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81461d90-ffffffff81461dd4: security_ptrace_access_check (STB_GLOBAL)
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
