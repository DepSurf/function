# Function: <code>ptrace_has_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *tcred, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108a7f0)
Location: kernel/ptrace.c:210
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8108a7f0-ffffffff8108a8b2: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *tcred, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108d7e0)
Location: kernel/ptrace.c:209
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8108d7e0-ffffffff8108d8a2: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ptrace_has_cap(struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81092a20)
Location: kernel/ptrace.c:247
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81092a20-ffffffff81092a56: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ptrace_has_cap(struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108fb60)
Location: kernel/ptrace.c:262
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff8108fb60-ffffffff8108fb96: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ptrace_has_cap(struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096a20)
Location: kernel/ptrace.c:262
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81096a20-ffffffff81096a67: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ptrace_has_cap(struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81099ce0)
Location: kernel/ptrace.c:262
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81099ce0-ffffffff81099d27: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ptrace_has_cap(struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2120)
Location: kernel/ptrace.c:262
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff810a2120-ffffffff810a2167: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ptrace_has_cap(struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6dd0)
Location: kernel/ptrace.c:267
Inline: True
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff810a6dd0-ffffffff810a6e06: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ad130)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff810ad130-ffffffff810ad167: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b504f)
Location: kernel/ptrace.c:267
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b026b)
Location: kernel/ptrace.c:267
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b17df)
Location: kernel/ptrace.c:284
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c38cf)
Location: kernel/ptrace.c:284
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810db03b)
Location: kernel/ptrace.c:278
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fb18b)
Location: kernel/ptrace.c:278
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8110744b)
Location: kernel/ptrace.c:279
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110d9b)
Location: kernel/ptrace.c:268
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
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
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff8000101068e0)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffff8000101068e0-ffff800010106958: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c03615ac)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
c03615ac-c03615dc: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014de10)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
c00000000014de10-c00000000014de88: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cb632)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffe0000cb632-ffffffe0000cb698: ptrace_has_cap (STB_LOCAL)
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
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a74a0)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff810a74a0-ffffffff810a74d7: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81095e80)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff81095e80-ffffffff81095eb7: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6a00)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff810a6a00-ffffffff810a6a37: ptrace_has_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred *cred, struct user_namespace *ns, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810aeb50)
Location: kernel/ptrace.c:267
Inline: False
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
```
**Symbols:**

```
ffffffff810aeb50-ffffffff810aeb87: ptrace_has_cap (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *ns</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cred *tcred</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>ns, mode</code> ➡️ <code>cred, ns, mode</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
