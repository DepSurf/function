# Function: <code>umip_printk</code>

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
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8106cea0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:force_sig_info_umip_fault
```
**Symbols:**

```
ffffffff8106cea0-ffffffff8106cf84: umip_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:force_sig_info_umip_fault
```
**Symbols:**

```
ffffffff8106fd40-ffffffff8106fdcc: umip_printk (STB_LOCAL)
ffffffff8107035f-ffffffff810703be: umip_printk.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81075da0-ffffffff81075e2c: umip_printk (STB_LOCAL)
ffffffff81076335-ffffffff81076394: umip_printk.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810799a0-ffffffff81079a2c: umip_printk (STB_LOCAL)
ffffffff81079eed-ffffffff81079f4b: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff8107a9f0-ffffffff8107aa7c: umip_printk (STB_LOCAL)
ffffffff8107afde-ffffffff8107b03c: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81081e00-ffffffff81081e8c: umip_printk (STB_LOCAL)
ffffffff810823ec-ffffffff8108244a: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810818d0-ffffffff8108195c: umip_printk (STB_LOCAL)
ffffffff81bd82f5-ffffffff81bd8353: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810826f0-ffffffff8108277c: umip_printk (STB_LOCAL)
ffffffff81bca132-ffffffff81bca190: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810917b0-ffffffff8109183c: umip_printk (STB_LOCAL)
ffffffff81c9f499-ffffffff81c9f4f7: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810a2940-ffffffff810a2a11: umip_printk (STB_LOCAL)
ffffffff81e4ec44-ffffffff81e4eca2: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810baba0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810baba0-ffffffff810bacc6: umip_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810bdcf0)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810bdcf0-ffffffff810bde16: umip_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810c4e70)
Location: arch/x86/kernel/umip.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810c4e70-ffffffff810c4f96: umip_printk (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810799f0-ffffffff81079a7c: umip_printk (STB_LOCAL)
ffffffff81079fde-ffffffff8107a03c: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81069160-ffffffff810691ec: umip_printk (STB_LOCAL)
ffffffff81069713-ffffffff81069771: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810799a0-ffffffff81079a2c: umip_printk (STB_LOCAL)
ffffffff81079f8e-ffffffff81079fec: umip_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void umip_printk(const struct pt_regs *regs, const char *log_level, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff8107baa0-ffffffff8107bb2c: umip_printk (STB_LOCAL)
ffffffff8107c08e-ffffffff8107c0ec: umip_printk.cold (STB_LOCAL)
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
