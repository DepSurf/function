# Function: <code>user_exc_vmm_communication</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void user_exc_vmm_communication(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81c2a670)
Location: arch/x86/kernel/sev.c:1439
Inline: False
```
**Symbols:**

```
ffffffff81c2a670-ffffffff81c2a6c4: user_exc_vmm_communication (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void user_exc_vmm_communication(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81d48c60)
Location: arch/x86/kernel/sev.c:1435
Inline: False
```
**Symbols:**

```
ffffffff81d48c60-ffffffff81d48cb4: user_exc_vmm_communication (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void user_exc_vmm_communication(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81f17f70)
Location: arch/x86/kernel/sev.c:1981
Inline: False
```
**Symbols:**

```
ffffffff81f17f70-ffffffff81f17fd9: user_exc_vmm_communication (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void user_exc_vmm_communication(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff820bf720)
Location: arch/x86/kernel/sev.c:1981
Inline: False
```
**Symbols:**

```
ffffffff820bf720-ffffffff820bf789: user_exc_vmm_communication (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void user_exc_vmm_communication(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff82141420)
Location: arch/x86/kernel/sev.c:1938
Inline: False
```
**Symbols:**

```
ffffffff82141420-ffffffff82141489: user_exc_vmm_communication (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void user_exc_vmm_communication(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff82223330)
Location: arch/x86/kernel/sev.c:1976
Inline: False
```
**Symbols:**

```
ffffffff82223330-ffffffff82223399: user_exc_vmm_communication (STB_GLOBAL)
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
