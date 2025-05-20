# Function: <code>get_cmdline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ac200)
Location: mm/util.c:402
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff811ac200-ffffffff811ac2ea: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4f50)
Location: mm/util.c:603
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff811c4f50-ffffffff811c5092: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d5060)
Location: mm/util.c:606
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff811d5060-ffffffff811d51a8: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ddeb0)
Location: mm/util.c:690
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff811ddeb0-ffffffff811de00d: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3930)
Location: mm/util.c:690
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff811f3930-ffffffff811f3a8d: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214c60)
Location: mm/util.c:733
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81214c60-ffffffff81214dbd: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227b40)
Location: mm/util.c:735
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81227b40-ffffffff81227c9d: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:738
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff812379c6-ffffffff812379d2: get_cmdline.cold (STB_LOCAL)
ffffffff81237860-ffffffff812379ba: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81245c84-ffffffff81245c90: get_cmdline.cold (STB_LOCAL)
ffffffff81245ab0-ffffffff81245c0a: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:865
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_proctitle
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81273a07-ffffffff81273a13: get_cmdline.cold (STB_LOCAL)
ffffffff81273830-ffffffff8127398f: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:924
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_proctitle
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81be6f03-ffffffff81be6f0f: get_cmdline.cold (STB_LOCAL)
ffffffff8127e0c0-ffffffff8127e21f: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:914
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81bd8cad-ffffffff81bd8cb9: get_cmdline.cold (STB_LOCAL)
ffffffff81283230-ffffffff8128338f: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:945
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81cbaac4-ffffffff81cbaad0: get_cmdline.cold (STB_LOCAL)
ffffffff812c13f0-ffffffff812c154f: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:1070
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81e6c3e2-ffffffff81e6c3ee: get_cmdline.cold (STB_LOCAL)
ffffffff8131e3d0-ffffffff8131e547: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391ea0)
Location: mm/util.c:965
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff81391ea0-ffffffff8139201a: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c48a0)
Location: mm/util.c:988
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff813c48a0-ffffffff813c4a1a: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ef320)
Location: mm/util.c:996
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_proctitle
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff813ef320-ffffffff813ef49a: get_cmdline (STB_GLOBAL)
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
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d9138)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffff8000102d9138-ffff8000102d92fc: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c050030c)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
c050030c-c050047c: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000398cc0)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
c000000000398cc0-c000000000398ef4: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f354a)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffe0001f354a-ffffffe0001f369a: get_cmdline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff8123e2d4-ffffffff8123e2e0: get_cmdline.cold (STB_LOCAL)
ffffffff8123e100-ffffffff8123e25a: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff812312d4-ffffffff812312e0: get_cmdline.cold (STB_LOCAL)
ffffffff81231100-ffffffff8123125a: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff8123c074-ffffffff8123c080: get_cmdline.cold (STB_LOCAL)
ffffffff8123bea0-ffffffff8123bffa: get_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int get_cmdline(struct task_struct *task, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/util.c (0)
Location: mm/util.c:843
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
**Symbols:**

```
ffffffff8124b7cc-ffffffff8124b7d8: get_cmdline.cold (STB_LOCAL)
ffffffff8124b5b0-ffffffff8124b716: get_cmdline (STB_GLOBAL)
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
