# Function: <code>has_capability_noaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108a7c0)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:oom_score_adj_write
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff8108a7c0-ffffffff8108a7e5: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d7b0)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8108d7b0-ffffffff8108d7d5: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810926c0)
Location: kernel/capability.c:360
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff810926c0-ffffffff810926e5: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f800)
Location: kernel/capability.c:360
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8108f800-ffffffff8108f825: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810966c0)
Location: kernel/capability.c:361
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810966c0-ffffffff810966e5: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81099bd0)
Location: kernel/capability.c:361
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81099bd0-ffffffff81099bf5: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1f60)
Location: kernel/capability.c:361
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810a1f60-ffffffff810a1f8a: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6990)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810a6990-ffffffff810a69ba: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810acf70)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810acf70-ffffffff810acf9a: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b4a70)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810b4a70-ffffffff810b4a9a: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810afc80)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810afc80-ffffffff810afcb6: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b1180)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810b1180-ffffffff810b11b6: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c3240)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810c3240-ffffffff810c3276: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da4c0)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810da4c0-ffffffff810da50e: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa480)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810fa480-ffffffff810fa4ce: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81106520)
Location: kernel/capability.c:345
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81106520-ffffffff8110656e: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110fe70)
Location: kernel/capability.c:345
Inline: False
Direct callers:
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff8110fe70-ffffffff8110febe: has_capability_noaudit (STB_GLOBAL)
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
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010106778)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffff800010106778-ffff8000101067c0: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0361498)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
c0361498-c03614d0: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014db10)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
c00000000014db10-c00000000014db60: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb4f0)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffe0000cb4f0-ffffffe0000cb532: has_capability_noaudit (STB_GLOBAL)
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
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a72e0)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810a72e0-ffffffff810a730a: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81095cc0)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81095cc0-ffffffff81095cea: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6840)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810a6840-ffffffff810a686a: has_capability_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct *t, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae980)
Location: kernel/capability.c:359
Inline: False
Direct callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff810ae980-ffffffff810ae999: has_capability_noaudit (STB_GLOBAL)
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
