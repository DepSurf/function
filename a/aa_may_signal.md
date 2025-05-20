# Function: <code>aa_may_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813780c0)
Location: security/apparmor/ipc.c:213
Inline: False
```
**Symbols:**

```
ffffffff813780c0-ffffffff813782a1: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813b0df0)
Location: security/apparmor/ipc.c:213
Inline: False
```
**Symbols:**

```
ffffffff813b0df0-ffffffff813b103e: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813c7f70)
Location: security/apparmor/ipc.c:213
Inline: False
```
**Symbols:**

```
ffffffff813c7f70-ffffffff813c81be: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813dd790)
Location: security/apparmor/ipc.c:215
Inline: False
```
**Symbols:**

```
ffffffff813dd790-ffffffff813dd9b3: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814041b0)
Location: security/apparmor/ipc.c:211
Inline: False
```
**Symbols:**

```
ffffffff814041b0-ffffffff81404359: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814352a0)
Location: security/apparmor/ipc.c:211
Inline: False
```
**Symbols:**

```
ffffffff814352a0-ffffffff81435426: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81451e90)
Location: security/apparmor/ipc.c:212
Inline: False
```
**Symbols:**

```
ffffffff81451e90-ffffffff81452016: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8147f8a0)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffffffff8147f8a0-ffffffff8147fa22: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814995a0)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffffffff814995a0-ffffffff81499722: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814f1c70)
Location: security/apparmor/ipc.c:208
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
```
**Symbols:**

```
ffffffff814f1c70-ffffffff814f1df2: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8150ee90)
Location: security/apparmor/ipc.c:208
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
```
**Symbols:**

```
ffffffff8150ee90-ffffffff8150f012: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81515880)
Location: security/apparmor/ipc.c:208
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
```
**Symbols:**

```
ffffffff81515880-ffffffff81515a02: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81573860)
Location: security/apparmor/ipc.c:208
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
```
**Symbols:**

```
ffffffff81573860-ffffffff81573a0b: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81610d70)
Location: security/apparmor/ipc.c:103
Inline: False
```
**Symbols:**

```
ffffffff81610d70-ffffffff81610f33: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_may_signal(const struct cred *subj_cred, struct aa_label *sender, const struct cred *target_cred, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff816c37e0)
Location: security/apparmor/ipc.c:106
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
```
**Symbols:**

```
ffffffff816c37e0-ffffffff816c3981: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_may_signal(const struct cred *subj_cred, struct aa_label *sender, const struct cred *target_cred, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff816fc3d0)
Location: security/apparmor/ipc.c:106
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
```
**Symbols:**

```
ffffffff816fc3d0-ffffffff816fc57e: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_may_signal(const struct cred *subj_cred, struct aa_label *sender, const struct cred *target_cred, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81739920)
Location: security/apparmor/ipc.c:106
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
```
**Symbols:**

```
ffffffff81739920-ffffffff81739ace: aa_may_signal (STB_GLOBAL)
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
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffff80001058f2e8)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffff80001058f2e8-ffff80001058f474: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c0740138)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
c0740138-c07402b4: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c000000000702460)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
c000000000702460-c000000000702698: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffe0003dd018)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffffffe0003dd018-ffffffe0003dd158: aa_may_signal (STB_GLOBAL)
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
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81491b80)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffffffff81491b80-ffffffff81491d02: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814825a0)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffffffff814825a0-ffffffff81482722: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8148dc20)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffffffff8148dc20-ffffffff8148dda2: aa_may_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_may_signal(struct aa_label *sender, struct aa_label *target, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814a5b30)
Location: security/apparmor/ipc.c:208
Inline: False
```
**Symbols:**

```
ffffffff814a5b30-ffffffff814a5cb2: aa_may_signal (STB_GLOBAL)
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
<b>Param added. </b>
<code>const struct cred *target_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>sender, target, sig</code> ➡️ <code>subj_cred, sender, target_cred, target, sig</code>
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
