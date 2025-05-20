# Function: <code>dump_stack_print_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d9e90)
Location: kernel/printk/printk.c:3150
Inline: False
Direct callers:
  - kernel/printk/printk.c:show_regs_print_info
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810d9e90-ffffffff810d9f3e: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810df060)
Location: kernel/printk/printk.c:3292
Inline: False
Direct callers:
  - kernel/printk/printk.c:show_regs_print_info
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810df060-ffffffff810df10e: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e55d0)
Location: kernel/printk/printk.c:3118
Inline: False
Direct callers:
  - kernel/printk/printk.c:show_regs_print_info
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810e55d0-ffffffff810e567e: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4950)
Location: kernel/printk/printk.c:3125
Inline: False
Direct callers:
  - kernel/printk/printk.c:show_regs_print_info
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810e4950-ffffffff810e49f4: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ecc10)
Location: kernel/printk/printk.c:3119
Inline: False
Direct callers:
  - kernel/printk/printk.c:show_regs_print_info
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810ecc10-ffffffff810eccb4: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: True
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff819ce30b-ffffffff819ce33d: dump_stack_print_info.cold.2 (STB_LOCAL)
ffffffff819ce260-ffffffff819ce2f3: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81a077db-ffffffff81a077f6: dump_stack_print_info.cold.1 (STB_LOCAL)
ffffffff81a07720-ffffffff81a077ca: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81a7716b-ffffffff81a77186: dump_stack_print_info.cold (STB_LOCAL)
ffffffff81a770b0-ffffffff81a77159: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81aae54b-ffffffff81aae566: dump_stack_print_info.cold (STB_LOCAL)
ffffffff81aae490-ffffffff81aae539: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff815e82a8-ffffffff815e82c3: dump_stack_print_info.cold (STB_LOCAL)
ffffffff815e81e0-ffffffff815e8289: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:46
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81bf49a8-ffffffff81bf49c3: dump_stack_print_info.cold (STB_LOCAL)
ffffffff8160d370-ffffffff8160d427: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:46
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81be68a0-ffffffff81be68bb: dump_stack_print_info.cold (STB_LOCAL)
ffffffff815f0ad0-ffffffff815f0b87: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:55
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81cdf13b-ffffffff81cdf156: dump_stack_print_info.cold (STB_LOCAL)
ffffffff8165dc10-ffffffff8165dccc: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:55
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81ea5909-ffffffff81ea5924: dump_stack_print_info.cold (STB_LOCAL)
ffffffff81777230-ffffffff81777301: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dump_stack.c (ffffffff8201fcd0)
Location: lib/dump_stack.c:55
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff8201fcd0-ffffffff8201fdb5: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dump_stack.c (ffffffff8209fbe0)
Location: lib/dump_stack.c:55
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff8209fbe0-ffffffff8209fcc5: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dump_stack.c (ffffffff82177bb0)
Location: lib/dump_stack.c:55
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - lib/dump_stack.c:dump_stack_lvl
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff82177bb0-ffffffff82177c95: dump_stack_print_info (STB_GLOBAL)
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
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dump_stack.c (ffff800010d84a30)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffff800010d84a30-ffff800010d84b28: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dump_stack.c (c0e7fd24)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
c0e7fd24-c0e7fe14: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dump_stack.c (c000000000ec3c40)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
c000000000ec3c40-c000000000ec3d68: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dump_stack.c (ffffffe0008aed74)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffe0008aed74-ffffffe0008aee2e: dump_stack_print_info (STB_GLOBAL)
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
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81a4d39b-ffffffff81a4d3b6: dump_stack_print_info.cold (STB_LOCAL)
ffffffff81a4d2e0-ffffffff81a4d389: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81a0a4cb-ffffffff81a0a4e6: dump_stack_print_info.cold (STB_LOCAL)
ffffffff81a0a410-ffffffff81a0a4b9: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81ab978b-ffffffff81ab97a6: dump_stack_print_info.cold (STB_LOCAL)
ffffffff81ab96d0-ffffffff81ab9779: dump_stack_print_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dump_stack_print_info(const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dump_stack.c (0)
Location: lib/dump_stack.c:45
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:show_regs_print_info
```
**Symbols:**

```
ffffffff81ac5bdb-ffffffff81ac5bf6: dump_stack_print_info.cold (STB_LOCAL)
ffffffff81ac5b20-ffffffff81ac5bc9: dump_stack_print_info (STB_GLOBAL)
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
