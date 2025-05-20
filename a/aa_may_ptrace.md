# Function: <code>aa_may_ptrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81377e90)
Location: security/apparmor/ipc.c:114
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81377e90-ffffffff813780bd: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813b0b90)
Location: security/apparmor/ipc.c:114
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff813b0b90-ffffffff813b0deb: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813c7d10)
Location: security/apparmor/ipc.c:114
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff813c7d10-ffffffff813c7f6b: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813dd530)
Location: security/apparmor/ipc.c:115
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff813dd530-ffffffff813dd78c: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81403fd0)
Location: security/apparmor/ipc.c:123
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81403fd0-ffffffff814041a9: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814350c0)
Location: security/apparmor/ipc.c:123
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814350c0-ffffffff81435299: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81451cb0)
Location: security/apparmor/ipc.c:124
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81451cb0-ffffffff81451e86: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8147f6c0)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8147f6c0-ffffffff8147f897: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814993c0)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814993c0-ffffffff81499597: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814f1a90)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814f1a90-ffffffff814f1c67: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8150ecb0)
Location: security/apparmor/ipc.c:118
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8150ecb0-ffffffff8150ee87: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff815156a0)
Location: security/apparmor/ipc.c:118
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff815156a0-ffffffff81515877: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81573680)
Location: security/apparmor/ipc.c:118
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81573680-ffffffff81573857: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816105f0)
Location: security/apparmor/task.c:285
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff816105f0-ffffffff816107e8: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_may_ptrace(const struct cred *tracer_cred, struct aa_label *tracer, const struct cred *tracee_cred, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816c3060)
Location: security/apparmor/task.c:290
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff816c3060-ffffffff816c324a: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_may_ptrace(const struct cred *tracer_cred, struct aa_label *tracer, const struct cred *tracee_cred, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816fbc00)
Location: security/apparmor/task.c:290
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff816fbc00-ffffffff816fbdf2: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_may_ptrace(const struct cred *tracer_cred, struct aa_label *tracer, const struct cred *tracee_cred, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81738bc0)
Location: security/apparmor/task.c:286
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff81738bc0-ffffffff81738d95: aa_may_ptrace (STB_GLOBAL)
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
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffff80001058f128)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffff80001058f128-ffff80001058f2e8: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c073ff78)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
c073ff78-c0740138: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c0000000007021f0)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
c0000000007021f0-c000000000702458: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffe0003dceaa)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffe0003dceaa-ffffffe0003dd018: aa_may_ptrace (STB_GLOBAL)
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
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814919a0)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814919a0-ffffffff81491b77: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814823c0)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814823c0-ffffffff81482597: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8148da40)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff8148da40-ffffffff8148dc17: aa_may_ptrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_may_ptrace(struct aa_label *tracer, struct aa_label *tracee, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814a5950)
Location: security/apparmor/ipc.c:120
Inline: False
Direct callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
**Symbols:**

```
ffffffff814a5950-ffffffff814a5b27: aa_may_ptrace (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *tracer_cred</code>
</li>
<li>
<b>Param added. </b>
<code>const struct cred *tracee_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>tracer, tracee, request</code> ➡️ <code>tracer_cred, tracer, tracee_cred, tracee, request</code>
</li>
</ul>
</details>
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
