# Function: <code>audit_filter</code>

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
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112d6d0)
Location: kernel/auditfilter.c:1293
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8112d6d0-ffffffff8112d8cf: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137400)
Location: kernel/auditfilter.c:1294
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81137400-ffffffff811375ff: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81138960)
Location: kernel/auditfilter.c:1292
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81138960-ffffffff81138b5e: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81145660)
Location: kernel/auditfilter.c:1317
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81145660-ffffffff8114584b: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81153ff0)
Location: kernel/auditfilter.c:1314
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81153ff0-ffffffff811541db: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81160db0)
Location: kernel/auditfilter.c:1312
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81160db0-ffffffff81160ffc: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116d450)
Location: kernel/auditfilter.c:1315
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8116d450-ffffffff8116d6b6: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811792f0)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811792f0-ffffffff81179556: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118c340)
Location: kernel/auditfilter.c:1321
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff8118c340-ffffffff8118c5cd: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81189560)
Location: kernel/auditfilter.c:1321
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff81189560-ffffffff811897eb: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a3d0)
Location: kernel/auditfilter.c:1321
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff8118a3d0-ffffffff8118a649: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:1321
Inline: False
Direct callers:
  - kernel/audit.c:audit_log
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_object_context
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff81cb3552-ffffffff81cb3581: audit_filter.cold (STB_LOCAL)
ffffffff811b2e90-ffffffff811b318a: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e52e0)
Location: kernel/auditfilter.c:1329
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811e52e0-ffffffff811e55db: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8122b360)
Location: kernel/auditfilter.c:1329
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8122b360-ffffffff8122b65b: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81241930)
Location: kernel/auditfilter.c:1329
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81241930-ffffffff81241c3b: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125b760)
Location: kernel/auditfilter.c:1330
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8125b760-ffffffff8125ba4e: audit_filter (STB_GLOBAL)
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
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ee610)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffff8000101ee610-ffff8000101ee874: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042e630)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
c042e630-c042e89c: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c0000000002612c0)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
c0000000002612c0-c0000000002616ac: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe00016275a)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffe00016275a-ffffffe0001628e8: audit_filter (STB_GLOBAL)
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
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81171910)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81171910-ffffffff81171b76: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81164ab0)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81164ab0-ffffffff81164d16: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116f6e0)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8116f6e0-ffffffff8116f946: audit_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_filter(int msgtype, unsigned int listtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8117ced0)
Location: kernel/auditfilter.c:1322
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8117ced0-ffffffff8117d14f: audit_filter (STB_GLOBAL)
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
