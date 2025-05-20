# Function: <code>force_sig_info_umip_fault</code>

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
void force_sig_info_umip_fault(void *addr, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8106d41d)
Location: arch/x86/kernel/umip.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff8106d41d-ffffffff8106d4ed: force_sig_info_umip_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void force_sig_info_umip_fault(void *addr, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8106fdd0)
Location: arch/x86/kernel/umip.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff8106fdd0-ffffffff8106fec7: force_sig_info_umip_fault (STB_LOCAL)
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
In arch/x86/kernel/umip.c (ffffffff8107622f)
Location: arch/x86/kernel/umip.c:272
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
In arch/x86/kernel/umip.c (ffffffff81079ddf)
Location: arch/x86/kernel/umip.c:272
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
In arch/x86/kernel/umip.c (ffffffff8107aebd)
Location: arch/x86/kernel/umip.c:283
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810822cd)
Location: arch/x86/kernel/umip.c:283
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff81081e59)
Location: arch/x86/kernel/umip.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff81082c79)
Location: arch/x86/kernel/umip.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff81091d2f)
Location: arch/x86/kernel/umip.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810a2f4b)
Location: arch/x86/kernel/umip.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810bb21b)
Location: arch/x86/kernel/umip.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810be358)
Location: arch/x86/kernel/umip.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810c54d8)
Location: arch/x86/kernel/umip.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff81079ebd)
Location: arch/x86/kernel/umip.c:283
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
In arch/x86/kernel/umip.c (ffffffff810695f2)
Location: arch/x86/kernel/umip.c:283
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
In arch/x86/kernel/umip.c (ffffffff81079e6d)
Location: arch/x86/kernel/umip.c:283
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8107bf6d)
Location: arch/x86/kernel/umip.c:283
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
</ul>
