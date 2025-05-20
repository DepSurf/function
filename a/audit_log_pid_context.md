# Function: <code>audit_log_pid_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81125bd0)
Location: kernel/auditsc.c:959
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81125bd0-ffffffff81125d09: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8112e0c0)
Location: kernel/auditsc.c:964
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8112e0c0-ffffffff8112e1fc: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81137e00)
Location: kernel/auditsc.c:969
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81137e00-ffffffff81137f3c: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81138da0)
Location: kernel/auditsc.c:970
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81138da0-ffffffff81138edc: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81145a90)
Location: kernel/auditsc.c:970
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81145a90-ffffffff81145bcc: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81154480)
Location: kernel/auditsc.c:977
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81154480-ffffffff811545bc: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81161310)
Location: kernel/auditsc.c:933
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81161310-ffffffff8116144c: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116d9d0)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8116d9d0-ffffffff8116db0c: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81179850)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81179850-ffffffff8117998c: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118cc20)
Location: kernel/auditsc.c:969
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118cc20-ffffffff8118cce1: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81189df0)
Location: kernel/auditsc.c:987
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81189df0-ffffffff81189eb1: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118adf0)
Location: kernel/auditsc.c:986
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118adf0-ffffffff8118aead: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b39d0)
Location: kernel/auditsc.c:992
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811b39d0-ffffffff811b3a8d: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e8b20)
Location: kernel/auditsc.c:1117
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811e8b20-ffffffff811e8c46: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122ebb0)
Location: kernel/auditsc.c:1095
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8122ebb0-ffffffff8122ecd6: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81244aa0)
Location: kernel/auditsc.c:1096
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81244aa0-ffffffff81244bc6: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, struct lsmblob *blob, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125e9e0)
Location: kernel/auditsc.c:1095
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8125e9e0-ffffffff8125eb18: audit_log_pid_context (STB_LOCAL)
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
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101eead0)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffff8000101eead0-ffff8000101eec38: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042ee68)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
c042ee68-c042efbc: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000261960)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
c000000000261960-c000000000261b38: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000162b0e)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffe000162b0e-ffffffe000162c3c: audit_log_pid_context (STB_LOCAL)
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
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81171e70)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81171e70-ffffffff81171fac: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81165010)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff81165010-ffffffff8116514c: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116fc40)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8116fc40-ffffffff8116fd7c: audit_log_pid_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_log_pid_context(struct audit_context *context, pid_t pid, kuid_t auid, kuid_t uid, unsigned int sessionid, u32 sid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d440)
Location: kernel/auditsc.c:955
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8117d440-ffffffff8117d57c: audit_log_pid_context (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 sid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
