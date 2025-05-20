# Function: <code>rseq_ip_fixup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff811ea2e3)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff811fae53)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81212550)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff8121fd30)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff8124c120)
Location: kernel/rseq.c:221
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff8124c120-ffffffff8124c2c6: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff812565a0)
Location: kernel/rseq.c:221
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff812565a0-ffffffff8125671a: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff8125aa50)
Location: kernel/rseq.c:237
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff8125aa50-ffffffff8125abaf: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81296840)
Location: kernel/rseq.c:237
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff81296840-ffffffff812969a0: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff812ec870)
Location: kernel/rseq.c:237
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff812ec870-ffffffff812eca36: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81356bb0)
Location: kernel/rseq.c:245
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff81356bb0-ffffffff81356da0: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81388680)
Location: kernel/rseq.c:274
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff81388680-ffffffff8138886c: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff813b20e0)
Location: kernel/rseq.c:274
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff813b20e0-ffffffff813b22cc: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffff8000102ac75c)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (c04d9510)
Location: kernel/rseq.c:221
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
c04d9510-c04d99d4: rseq_ip_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (c0000000003607e4)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81218380)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff8120b590)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rseq.c (ffffffff81216120)
Location: kernel/rseq.c:221
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rseq_ip_fixup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rseq.c (0)
Location: kernel/rseq.c:221
Inline: False
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
**Symbols:**

```
ffffffff81224d90-ffffffff8122518d: rseq_ip_fixup (STB_LOCAL)
ffffffff81225599-ffffffff812255bf: rseq_ip_fixup.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
