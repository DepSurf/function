# Function: <code>report_access</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813d0ee0)
Location: security/yama/yama_lsm.c:78
Inline: False
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff813d0ee0-ffffffff813d103b: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813e85e0)
Location: security/yama/yama_lsm.c:78
Inline: False
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff813e85e0-ffffffff813e873b: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813f44a0)
Location: security/yama/yama_lsm.c:78
Inline: False
```
**Symbols:**

```
ffffffff813f44a0-ffffffff813f45db: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8141cb90)
Location: security/yama/yama_lsm.c:78
Inline: False
```
**Symbols:**

```
ffffffff8141cb90-ffffffff8141cced: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8144ee20)
Location: security/yama/yama_lsm.c:78
Inline: False
```
**Symbols:**

```
ffffffff8144ee20-ffffffff8144ef87: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8146bdf0)
Location: security/yama/yama_lsm.c:78
Inline: False
```
**Symbols:**

```
ffffffff8146bdf0-ffffffff8146bf57: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81498de0)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff81498de0-ffffffff81498f58: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814b2d10)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff814b2d10-ffffffff814b2e88: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff815120e0)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff815120e0-ffffffff81512326: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8152ef80)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff8152ef80-ffffffff8152f1c6: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81534f10)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff81534f10-ffffffff81535153: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81593420)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff81593420-ffffffff81593663: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff816356e0)
Location: security/yama/yama_lsm.c:74
Inline: False
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff816356e0-ffffffff81635948: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff816ec3d0)
Location: security/yama/yama_lsm.c:75
Inline: False
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff816ec3d0-ffffffff816ec638: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81726800)
Location: security/yama/yama_lsm.c:75
Inline: False
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff81726800-ffffffff81726a68: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81767a20)
Location: security/yama/yama_lsm.c:75
Inline: False
Direct callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
**Symbols:**

```
ffffffff81767a20-ffffffff81767cb7: report_access (STB_LOCAL)
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
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffff8000105aa558)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffff8000105aa558-ffff8000105aa6f0: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (c075a4b4)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
c075a4b4-c075a670: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (c0000000007282a0)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
c0000000007282a0-c000000000728504: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffe0003f31fa)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffe0003f31fa-ffffffe0003f334e: report_access (STB_LOCAL)
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
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814ab2f0)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff814ab2f0-ffffffff814ab468: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8149bd10)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff8149bd10-ffffffff8149be88: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814a7390)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff814a7390-ffffffff814a7508: report_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void report_access(const char *access, struct task_struct *target, struct task_struct *agent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814bfcf0)
Location: security/yama/yama_lsm.c:74
Inline: False
```
**Symbols:**

```
ffffffff814bfcf0-ffffffff814bfe68: report_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
