# Function: <code>aa_task_setrlimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813874e0)
Location: security/apparmor/resource.c:96
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff813874e0-ffffffff81387759: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813c1f80)
Location: security/apparmor/resource.c:96
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff813c1f80-ffffffff813c2212: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813d9420)
Location: security/apparmor/resource.c:96
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff813d9420-ffffffff813d96b2: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff813ea6d0)
Location: security/apparmor/resource.c:108
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff813ea6d0-ffffffff813ea873: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81411fd0)
Location: security/apparmor/resource.c:108
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff81411fd0-ffffffff814121cb: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81444190)
Location: security/apparmor/resource.c:108
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff81444190-ffffffff81444383: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81461240)
Location: security/apparmor/resource.c:108
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff81461240-ffffffff81461441: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff8148e530)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff8148e530-ffffffff8148e6fb: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814a83f0)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff814a83f0-ffffffff814a85bb: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81505780)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff81505780-ffffffff815059a8: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff815228b0)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff815228b0-ffffffff81522adf: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff81528a90)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff81528a90-ffffffff81528cb7: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/resource.c (0)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff81cd66d3-ffffffff81cd66f5: aa_task_setrlimit.cold (STB_LOCAL)
ffffffff81586d80-ffffffff81587005: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/resource.c (0)
Location: security/apparmor/resource.c:107
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff81e895fd-ffffffff81e89626: aa_task_setrlimit.cold (STB_LOCAL)
ffffffff81627170-ffffffff8162745a: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int aa_task_setrlimit(const struct cred *subj_cred, struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/resource.c (0)
Location: security/apparmor/resource.c:115
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff82074ca1-ffffffff82074cca: aa_task_setrlimit.cold (STB_LOCAL)
ffffffff816db180-ffffffff816db445: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int aa_task_setrlimit(const struct cred *subj_cred, struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/resource.c (0)
Location: security/apparmor/resource.c:115
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff820f48a6-ffffffff820f48cd: aa_task_setrlimit.cold (STB_LOCAL)
ffffffff81714870-ffffffff81714b29: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int aa_task_setrlimit(const struct cred *subj_cred, struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/resource.c (0)
Location: security/apparmor/resource.c:115
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff821d1d3a-ffffffff821d1d61: aa_task_setrlimit.cold (STB_LOCAL)
ffffffff81753280-ffffffff8175353c: aa_task_setrlimit (STB_GLOBAL)
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
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffff80001059eb08)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffff80001059eb08-ffff80001059ece8: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (c074f8a4)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
c074f8a4-c074fa7c: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (c000000000718610)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
c000000000718610-c00000000071890c: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffe0003e9fb0)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffe0003e9fb0-ffffffe0003ea132: aa_task_setrlimit (STB_GLOBAL)
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
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814a09d0)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff814a09d0-ffffffff814a0b9b: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814913f0)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff814913f0-ffffffff814915bb: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff8149ca70)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff8149ca70-ffffffff8149cc3b: aa_task_setrlimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_task_setrlimit(struct aa_label *label, struct task_struct *task, unsigned int resource, struct rlimit *new_rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/resource.c (ffffffff814b5000)
Location: security/apparmor/resource.c:104
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_setrlimit
```
**Symbols:**

```
ffffffff814b5000-ffffffff814b51dd: aa_task_setrlimit (STB_GLOBAL)
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
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, task, resource, new_rlim</code> ➡️ <code>subj_cred, label, task, resource, new_rlim</code>
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
