# Function: <code>yama_ptrace_access_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81395120)
Location: security/yama/yama_lsm.c:278
Inline: False
```
**Symbols:**

```
ffffffff81395120-ffffffff81395276: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813d1040)
Location: security/yama/yama_lsm.c:349
Inline: False
```
**Symbols:**

```
ffffffff813d1040-ffffffff813d1166: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813e8740)
Location: security/yama/yama_lsm.c:363
Inline: False
```
**Symbols:**

```
ffffffff813e8740-ffffffff813e8895: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff813f48b0)
Location: security/yama/yama_lsm.c:363
Inline: True
```
**Symbols:**

```
ffffffff813f48b0-ffffffff813f4a0c: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8141ccf0)
Location: security/yama/yama_lsm.c:363
Inline: True
```
**Symbols:**

```
ffffffff8141ccf0-ffffffff8141ce4c: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8144ef90)
Location: security/yama/yama_lsm.c:358
Inline: True
```
**Symbols:**

```
ffffffff8144ef90-ffffffff8144f0db: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8146bff0)
Location: security/yama/yama_lsm.c:358
Inline: True
```
**Symbols:**

```
ffffffff8146bff0-ffffffff8146c149: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81499000)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff81499000-ffffffff81499187: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814b2f30)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff814b2f30-ffffffff814b30b7: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff815123d0)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff815123d0-ffffffff815124c8: yama_ptrace_access_check.part.0 (STB_LOCAL)
ffffffff815124d0-ffffffff815124e9: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8152f270)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff8152f270-ffffffff8152f377: yama_ptrace_access_check.part.0 (STB_LOCAL)
ffffffff8152f380-ffffffff8152f399: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81535200)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff81535200-ffffffff81535391: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8159373b)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff81593710-ffffffff815938bc: yama_ptrace_access_check (STB_LOCAL)
ffffffff81cd6931-ffffffff81cd6956: yama_ptrace_access_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (0)
Location: security/yama/yama_lsm.c:354
Inline: False
```
**Symbols:**

```
ffffffff81635a00-ffffffff81635ba5: yama_ptrace_access_check (STB_LOCAL)
ffffffff81e898bc-ffffffff81e898d9: yama_ptrace_access_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (0)
Location: security/yama/yama_lsm.c:355
Inline: False
```
**Symbols:**

```
ffffffff816ec710-ffffffff816ec8b5: yama_ptrace_access_check (STB_LOCAL)
ffffffff82074e66-ffffffff82074e83: yama_ptrace_access_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (0)
Location: security/yama/yama_lsm.c:355
Inline: False
```
**Symbols:**

```
ffffffff81726b40-ffffffff81726ce5: yama_ptrace_access_check (STB_LOCAL)
ffffffff820f4a11-ffffffff820f4a2e: yama_ptrace_access_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/yama/yama_lsm.c (0)
Location: security/yama/yama_lsm.c:355
Inline: False
```
**Symbols:**

```
ffffffff81767d90-ffffffff81767f35: yama_ptrace_access_check (STB_LOCAL)
ffffffff821d1ea5-ffffffff821d1ec2: yama_ptrace_access_check.cold (STB_LOCAL)
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
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffff8000105aa7d8)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffff8000105aa7d8-ffff8000105aa940: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (c075a73c)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
c075a73c-c075a8d8: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (c000000000728640)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
c000000000728640-c000000000728844: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffe0003f36f0)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffe0003f36f0-ffffffe0003f3808: yama_ptrace_access_check (STB_LOCAL)
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
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814ab510)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff814ab510-ffffffff814ab697: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8149bf30)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff8149bf30-ffffffff8149c0b7: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814a75b0)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff814a75b0-ffffffff814a7737: yama_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int yama_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff814bff00)
Location: security/yama/yama_lsm.c:354
Inline: True
```
**Symbols:**

```
ffffffff814bff00-ffffffff814c00ad: yama_ptrace_access_check (STB_LOCAL)
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
