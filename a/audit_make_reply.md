# Function: <code>audit_make_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(__u32 portid, int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81121c00)
Location: kernel/audit.c:561
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81121c00-ffffffff81121cd8: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(__u32 portid, int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81129b40)
Location: kernel/audit.c:558
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
```
**Symbols:**

```
ffffffff81129b40-ffffffff81129c1d: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(__u32 portid, int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133860)
Location: kernel/audit.c:697
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
```
**Symbols:**

```
ffffffff81133860-ffffffff8113393d: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134d50)
Location: kernel/audit.c:875
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81134d50-ffffffff81134e1d: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81141aa0)
Location: kernel/audit.c:875
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81141aa0-ffffffff81141b6d: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150430)
Location: kernel/audit.c:918
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81150430-ffffffff81150503: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d0f0)
Location: kernel/audit.c:914
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff8115d0f0-ffffffff8115d1c0: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169810)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81169810-ffffffff811698f2: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811756b0)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff811756b0-ffffffff81175792: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187db0)
Location: kernel/audit.c:903
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
```
**Symbols:**

```
ffffffff81187db0-ffffffff81187e8d: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185130)
Location: kernel/audit.c:908
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
```
**Symbols:**

```
ffffffff81185130-ffffffff8118520d: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185fc0)
Location: kernel/audit.c:908
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81185fc0-ffffffff8118609a: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ae3b0)
Location: kernel/audit.c:930
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff811ae3b0-ffffffff811ae48a: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e02a0)
Location: kernel/audit.c:931
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff811e02a0-ffffffff811e038f: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81226030)
Location: kernel/audit.c:929
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81226030-ffffffff8122611f: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123c610)
Location: kernel/audit.c:929
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff8123c610-ffffffff8123c6ff: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812564f0)
Location: kernel/audit.c:940
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff812564f0-ffffffff812565df: audit_make_reply (STB_GLOBAL)
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
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101ea4f0)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffff8000101ea4f0-ffff8000101ea5e4: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a268)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
c042a268-c042a32c: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025b6f0)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
c00000000025b6f0-c00000000025b834: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015ef52)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
```
**Symbols:**

```
ffffffe00015ef52-ffffffe00015f010: audit_make_reply (STB_GLOBAL)
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
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116dcd0)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff8116dcd0-ffffffff8116ddb2: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81160e70)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81160e70-ffffffff81160f52: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116baa0)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff8116baa0-ffffffff8116bb82: audit_make_reply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *audit_make_reply(int seq, int type, int done, int multi, const void *payload, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179260)
Location: kernel/audit.c:901
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
```
**Symbols:**

```
ffffffff81179260-ffffffff81179342: audit_make_reply (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__u32 portid</code>
</li>
<li>
<b>Param reordered. </b>
<code>portid, seq, type, done, multi, payload, size</code> ➡️ <code>seq, type, done, multi, payload, size</code>
</li>
</ul>
</details>
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
