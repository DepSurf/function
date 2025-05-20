# Function: <code>refcount_error_report</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108b1a0)
Location: kernel/panic.c:651
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff8108b1a0-ffffffff8108b24c: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108e890)
Location: kernel/panic.c:642
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff8108e890-ffffffff8108e931: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81096bd0)
Location: kernel/panic.c:677
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff81096bd0-ffffffff81096c71: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b140)
Location: kernel/panic.c:680
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff8109b140-ffffffff8109b1eb: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a1660)
Location: kernel/panic.c:675
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff810a1660-ffffffff810a170b: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109af80)
Location: kernel/panic.c:675
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff8109af80-ffffffff8109b02b: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810899c0)
Location: kernel/panic.c:675
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff810899c0-ffffffff81089a6b: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109af30)
Location: kernel/panic.c:675
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff8109af30-ffffffff8109afdb: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void refcount_error_report(struct pt_regs *regs, const char *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a2ba0)
Location: kernel/panic.c:675
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_refcount
  - arch/x86/mm/extable.c:ex_handler_refcount
```
**Symbols:**

```
ffffffff810a2ba0-ffffffff810a2c4b: refcount_error_report (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
