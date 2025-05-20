# Function: <code>get_kernel_gp_address</code>

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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81034100)
Location: arch/x86/kernel/traps.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81034100-ffffffff81034223: get_kernel_gp_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81034b00)
Location: arch/x86/kernel/traps.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81034b00-ffffffff81034c23: get_kernel_gp_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81036580)
Location: arch/x86/kernel/traps.c:496
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81036580-ffffffff8103668e: get_kernel_gp_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8103b820)
Location: arch/x86/kernel/traps.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8103b820-ffffffff8103b92e: get_kernel_gp_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810426a0)
Location: arch/x86/kernel/traps.c:574
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff810426a0-ffffffff810427c6: get_kernel_gp_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104c030)
Location: arch/x86/kernel/traps.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8104c030-ffffffff8104c15a: get_kernel_gp_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104c8a0)
Location: arch/x86/kernel/traps.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8104c8a0-ffffffff8104c9ca: get_kernel_gp_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs *regs, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81053b20)
Location: arch/x86/kernel/traps.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81053b20-ffffffff81053c4a: get_kernel_gp_address (STB_LOCAL)
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
