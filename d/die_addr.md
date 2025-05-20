# Function: <code>die_addr</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037740)
Location: arch/x86/kernel/dumpstack.c:432
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81037740-ffffffff8103779b: die_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810387c0)
Location: arch/x86/kernel/dumpstack.c:449
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff810387c0-ffffffff8103881b: die_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103a2e0)
Location: arch/x86/kernel/dumpstack.c:449
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8103a2e0-ffffffff8103a33b: die_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103fc90)
Location: arch/x86/kernel/dumpstack.c:449
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8103fc90-ffffffff8103fceb: die_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81047440)
Location: arch/x86/kernel/dumpstack.c:443
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81047440-ffffffff810474a5: die_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051e60)
Location: arch/x86/kernel/dumpstack.c:449
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81051e60-ffffffff81051efc: die_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052ba0)
Location: arch/x86/kernel/dumpstack.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81052ba0-ffffffff81052c3c: die_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void die_addr(const char *str, struct pt_regs *regs, long int err, long int gp_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059dc0)
Location: arch/x86/kernel/dumpstack.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81059dc0-ffffffff81059e5c: die_addr (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
