# Function: <code>has_ns_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108a750)
Location: kernel/capability.c:295
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - kernel/ptrace.c:ptrace_has_cap
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff8108a750-ffffffff8108a76c: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d766)
Location: kernel/capability.c:295
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - kernel/ptrace.c:ptrace_has_cap
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff8108d740-ffffffff8108d75c: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81092146)
Location: kernel/capability.c:295
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff81092680-ffffffff8109269c: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f356)
Location: kernel/capability.c:295
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff8108f7c0-ffffffff8108f7dc: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81096216)
Location: kernel/capability.c:296
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff81096680-ffffffff8109669c: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81099715)
Location: kernel/capability.c:296
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff81099b90-ffffffff81099bac: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1aa5)
Location: kernel/capability.c:296
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810a1f10-ffffffff810a1f2e: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a64d5)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810a6940-ffffffff810a695e: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810acab5)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810acf20-ffffffff810acf3e: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b4825)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810b4a20-ffffffff810b4a3e: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810afa18)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810afc20-ffffffff810afc4a: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b0f88)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810b1120-ffffffff810b114a: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c3048)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810c31e0-ffffffff810c320a: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da481)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810da690-ffffffff810da6df: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa4f1)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810fa730-ffffffff810fa77f: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81106591)
Location: kernel/capability.c:280
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff811067d0-ffffffff8110681f: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110fee1)
Location: kernel/capability.c:280
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff81110120-ffffffff8111016f: has_ns_capability (STB_GLOBAL)
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
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010105a04)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffff8000101066d8-ffff800010106728: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0360e50)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
c0361440-c036146c: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014d16c)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
c00000000014da70-c00000000014dab4: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb002)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffe0000cb46c-ffffffe0000cb4ae: has_ns_capability (STB_GLOBAL)
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
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6e25)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810a7290-ffffffff810a72ae: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81095805)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff81095c70-ffffffff81095c8e: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6385)
Location: kernel/capability.c:294
Inline: True
Inline callers:
  - kernel/capability.c:has_capability
Direct callers:
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810a67f0-ffffffff810a680e: has_ns_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool has_ns_capability(struct task_struct *t, struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae8c0)
Location: kernel/capability.c:294
Inline: False
Direct callers:
  - kernel/capability.c:has_capability
  - security/commoncap.c:cap_ptrace_traceme
```
**Symbols:**

```
ffffffff810ae8c0-ffffffff810ae903: has_ns_capability (STB_GLOBAL)
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
