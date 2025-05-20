# Function: <code>has_ns_capability_noaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108a7a0)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
Direct callers:
  - kernel/ptrace.c:ptrace_has_cap
```
**Symbols:**

```
ffffffff8108a7a0-ffffffff8108a7bc: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d7b6)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
Direct callers:
  - kernel/ptrace.c:ptrace_has_cap
```
**Symbols:**

```
ffffffff8108d790-ffffffff8108d7ac: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810926c6)
Location: kernel/capability.c:336
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810926a0-ffffffff810926bc: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f806)
Location: kernel/capability.c:336
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff8108f7e0-ffffffff8108f7fc: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810966c6)
Location: kernel/capability.c:337
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810966a0-ffffffff810966bc: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81099bd5)
Location: kernel/capability.c:337
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff81099bb0-ffffffff81099bcc: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1f65)
Location: kernel/capability.c:337
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810a1f30-ffffffff810a1f51: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6995)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810a6960-ffffffff810a6981: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810acf75)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810acf40-ffffffff810acf61: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b4a75)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810b4a40-ffffffff810b4a61: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810afc88)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810afc50-ffffffff810afc7d: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b1188)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810b1150-ffffffff810b117d: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c3248)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810c3210-ffffffff810c323d: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da4d1)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810da6e0-ffffffff810da732: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa491)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810fa790-ffffffff810fa7e2: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81106531)
Location: kernel/capability.c:321
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff81106830-ffffffff81106882: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110fe81)
Location: kernel/capability.c:321
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff81110180-ffffffff811101d2: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010106794)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffff800010106728-ffff800010106778: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c03614ac)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
c036146c-c0361498: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014db2c)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
c00000000014dac0-c00000000014db04: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb50a)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffe0000cb4ae-ffffffe0000cb4f0: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a72e5)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810a72b0-ffffffff810a72d1: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81095cc5)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff81095c90-ffffffff81095cb1: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6845)
Location: kernel/capability.c:335
Inline: True
Inline callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810a6810-ffffffff810a6831: has_ns_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool has_ns_capability_noaudit(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae930)
Location: kernel/capability.c:335
Inline: False
Direct callers:
  - kernel/capability.c:has_capability_noaudit
```
**Symbols:**

```
ffffffff810ae930-ffffffff810ae976: has_ns_capability_noaudit (STB_GLOBAL)
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
