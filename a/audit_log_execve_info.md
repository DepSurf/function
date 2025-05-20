# Function: <code>audit_log_execve_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8112645d)
Location: kernel/auditsc.c:1137
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8112db10)
Location: kernel/auditsc.c:996
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8112db10-ffffffff8112e0ba: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81137840)
Location: kernel/auditsc.c:1001
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81137840-ffffffff81137df9: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81138ee0)
Location: kernel/auditsc.c:1002
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81138ee0-ffffffff8113948b: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81145bd0)
Location: kernel/auditsc.c:1002
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81145bd0-ffffffff8114617b: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811545c0)
Location: kernel/auditsc.c:1009
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811545c0-ffffffff81154b5d: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81161450)
Location: kernel/auditsc.c:965
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81161450-ffffffff811619ee: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116db10)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff8116db10-ffffffff8116e15c: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81179990)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff81179990-ffffffff81179fdc: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118ccf0)
Location: kernel/auditsc.c:992
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff8118ccf0-ffffffff8118d33c: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81189ec0)
Location: kernel/auditsc.c:1010
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff81189ec0-ffffffff8118a50c: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118aeb0)
Location: kernel/auditsc.c:1009
Inline: False
```
**Symbols:**

```
ffffffff8118aeb0-ffffffff8118b4e5: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b3a90)
Location: kernel/auditsc.c:1015
Inline: False
```
**Symbols:**

```
ffffffff811b3a90-ffffffff811b40df: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1138
Inline: False
```
**Symbols:**

```
ffffffff811e5f70-ffffffff811e65ef: audit_log_execve_info (STB_LOCAL)
ffffffff81e64387-ffffffff81e64393: audit_log_execve_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122c420)
Location: kernel/auditsc.c:1116
Inline: False
```
**Symbols:**

```
ffffffff8122c420-ffffffff8122caaf: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81242ae0)
Location: kernel/auditsc.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81242ae0-ffffffff81243175: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125ca60)
Location: kernel/auditsc.c:1118
Inline: False
```
**Symbols:**

```
ffffffff8125ca60-ffffffff8125d124: audit_log_execve_info (STB_LOCAL)
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
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101eec38)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffff8000101eec38-ffff8000101ef0dc: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042efbc)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
c042efbc-c042f51c: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000261b40)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
c000000000261b40-c0000000002620fc: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000162c3c)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffe000162c3c-ffffffe000162fd6: audit_log_execve_info (STB_LOCAL)
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
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81171fb0)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff81171fb0-ffffffff811725fc: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81165150)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff81165150-ffffffff8116579c: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116fd80)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff8116fd80-ffffffff811703cc: audit_log_execve_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_execve_info(struct audit_context *context, struct audit_buffer **ab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d580)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:show_special
```
**Symbols:**

```
ffffffff8117d580-ffffffff8117dbcc: audit_log_execve_info (STB_LOCAL)
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
