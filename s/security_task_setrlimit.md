# Function: <code>security_task_setrlimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e690)
Location: security/security.c:966
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8133e690-ffffffff8133e6eb: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373ca0)
Location: security/security.c:990
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81373ca0-ffffffff81373cfb: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a5d0)
Location: security/security.c:1011
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8138a5d0-ffffffff8138a62b: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139fb20)
Location: security/security.c:1654
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8139fb20-ffffffff8139fb7b: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5750)
Location: security/security.c:1616
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff813c5750-ffffffff813c57b1: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5780)
Location: security/security.c:1120
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff813f5780-ffffffff813f57ce: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410db0)
Location: security/security.c:1728
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81410db0-ffffffff81410dfe: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e5b0)
Location: security/security.c:1747
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8143e5b0-ffffffff8143e609: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457ff0)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81457ff0-ffffffff8145803e: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aae80)
Location: security/security.c:1982
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff814aae80-ffffffff814aaece: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8480)
Location: security/security.c:1999
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff814c8480-ffffffff814c84ce: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ceac0)
Location: security/security.c:2062
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff814ceac0-ffffffff814ceb0e: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527780)
Location: security/security.c:2070
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81527780-ffffffff815277ce: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc600)
Location: security/security.c:2076
Inline: False
```
**Symbols:**

```
ffffffff815bc600-ffffffff815bc66d: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668650)
Location: security/security.c:2128
Inline: False
```
**Symbols:**

```
ffffffff81668650-ffffffff816686bd: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0ca0)
Location: security/security.c:3493
Inline: False
```
**Symbols:**

```
ffffffff816a0ca0-ffffffff816a0d0d: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd670)
Location: security/security.c:3552
Inline: False
```
**Symbols:**

```
ffffffff816dd670-ffffffff816dd6dd: security_task_setrlimit (STB_GLOBAL)
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
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543d90)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffff800010543d90-ffff800010543df4: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9ce0)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
c06f9ce0-c06f9d44: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006984d0)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
c0000000006984d0-c0000000006985a0: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a00e8)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffe0003a00e8-ffffffe0003a0134: security_task_setrlimit (STB_GLOBAL)
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
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814505d0)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff814505d0-ffffffff8145061e: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441020)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81441020-ffffffff8144106e: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c670)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff8144c670-ffffffff8144c6be: security_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_task_setrlimit(struct task_struct *p, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463a40)
Location: security/security.c:1786
Inline: False
Direct callers:
  - kernel/sys.c:do_prlimit
```
**Symbols:**

```
ffffffff81463a40-ffffffff81463a8e: security_task_setrlimit (STB_GLOBAL)
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
