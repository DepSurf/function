# Function: <code>audit_log_task_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81122930)
Location: kernel/audit.c:1875
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81122930-ffffffff81122b6c: audit_log_task_info.part.14 (STB_LOCAL)
ffffffff81122b70-ffffffff81122b86: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8112ba13)
Location: kernel/audit.c:1903
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff8112a910-ffffffff8112ab21: audit_log_task_info.part.14 (STB_LOCAL)
ffffffff8112ab30-ffffffff8112ab46: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81135733)
Location: kernel/audit.c:2042
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81134630-ffffffff81134841: audit_log_task_info.part.18 (STB_LOCAL)
ffffffff81134850-ffffffff81134866: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81136ce3)
Location: kernel/audit.c:2209
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81135aa0-ffffffff81135c8c: audit_log_task_info.part.18 (STB_LOCAL)
ffffffff81135c90-ffffffff81135ca7: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811439e3)
Location: kernel/audit.c:2217
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff811427e0-ffffffff811429d1: audit_log_task_info.part.19 (STB_LOCAL)
ffffffff811429e0-ffffffff811429f7: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81152423)
Location: kernel/audit.c:2270
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff811511c0-ffffffff811513b1: audit_log_task_info.part.18 (STB_LOCAL)
ffffffff811513c0-ffffffff811513d6: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8115f0d0)
Location: kernel/audit.c:2268
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff8115de70-ffffffff8115e062: audit_log_task_info.part.19 (STB_LOCAL)
ffffffff8115e070-ffffffff8115e086: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116b44e)
Location: kernel/audit.c:2121
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff8116a1a0-ffffffff8116a39e: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff8116a3a0-ffffffff8116a3b6: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8117732e)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81176040-ffffffff8117623e: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff81176240-ffffffff81176256: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8118a0a0)
Location: kernel/audit.c:2272
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81188840-ffffffff81188a75: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff81188a80-ffffffff81188a96: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811873b0)
Location: kernel/audit.c:2289
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81185b90-ffffffff81185dd4: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff81185de0-ffffffff81185df6: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811882e0)
Location: kernel/audit.c:2289
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81186b80-ffffffff81186dbe: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff81186dc0-ffffffff81186dd6: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811b0800)
Location: kernel/audit.c:2328
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff811aefb0-ffffffff811af1ee: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff811af1f0-ffffffff811af206: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e1240)
Location: kernel/audit.c:2374
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
**Symbols:**

```
ffffffff811e1240-ffffffff811e1504: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812270c0)
Location: kernel/audit.c:2372
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
**Symbols:**

```
ffffffff812270c0-ffffffff81227384: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123d6e0)
Location: kernel/audit.c:2372
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
**Symbols:**

```
ffffffff8123d6e0-ffffffff8123d9a7: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81257610)
Location: kernel/audit.c:2394
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_path_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
**Symbols:**

```
ffffffff81257610-ffffffff812578d3: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffff8000101ec2e4)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffff8000101eb0d8-ffff8000101eb2ec: audit_log_task_info.part.0 (STB_LOCAL)
ffff8000101eb2f0-ffff8000101eb320: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (c042bf0c)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
c042acbc-c042af34: audit_log_task_info.part.0 (STB_LOCAL)
c042af34-c042af58: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (c00000000025dc78)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
c00000000025c660-c00000000025c8e4: audit_log_task_info.part.0 (STB_LOCAL)
c00000000025c8f0-c00000000025c90c: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffe000160a06)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffe00015f962-ffffffe00015fb5a: audit_log_task_info.part.0 (STB_LOCAL)
ffffffe00015fb5a-ffffffe00015fb86: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116f94e)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff8116e660-ffffffff8116e85e: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff8116e860-ffffffff8116e876: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81162aee)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81161800-ffffffff811619fe: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff81161a00-ffffffff81161a16: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8116d71e)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff8116c430-ffffffff8116c62e: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff8116c630-ffffffff8116c646: audit_log_task_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_log_task_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8117af0e)
Location: kernel/audit.c:2123
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:audit_log_exit
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
**Symbols:**

```
ffffffff81179bf0-ffffffff81179df4: audit_log_task_info.part.0 (STB_LOCAL)
ffffffff81179e00-ffffffff81179e16: audit_log_task_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
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
