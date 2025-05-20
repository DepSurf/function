# Function: <code>vmware_sev_es_hcall_prepare</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmware_sev_es_hcall_prepare(struct ghcb *ghcb, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069340)
Location: arch/x86/kernel/cpu/vmware.c:481
Inline: False
```
**Symbols:**

```
ffffffff81069340-ffffffff810693f6: vmware_sev_es_hcall_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmware_sev_es_hcall_prepare(struct ghcb *ghcb, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069dd0)
Location: arch/x86/kernel/cpu/vmware.c:484
Inline: False
```
**Symbols:**

```
ffffffff81069dd0-ffffffff81069e77: vmware_sev_es_hcall_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vmware_sev_es_hcall_prepare(struct ghcb *ghcb, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81074460)
Location: arch/x86/kernel/cpu/vmware.c:484
Inline: False
```
**Symbols:**

```
ffffffff81074460-ffffffff81074507: vmware_sev_es_hcall_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vmware_sev_es_hcall_prepare(struct ghcb *ghcb, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082cc0)
Location: arch/x86/kernel/cpu/vmware.c:484
Inline: False
```
**Symbols:**

```
ffffffff81082cc0-ffffffff81082d75: vmware_sev_es_hcall_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmware_sev_es_hcall_prepare(struct ghcb *ghcb, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff810957c0)
Location: arch/x86/kernel/cpu/vmware.c:484
Inline: False
```
**Symbols:**

```
ffffffff810957c0-ffffffff81095875: vmware_sev_es_hcall_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmware_sev_es_hcall_prepare(struct ghcb *ghcb, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81098730)
Location: arch/x86/kernel/cpu/vmware.c:484
Inline: False
```
**Symbols:**

```
ffffffff81098730-ffffffff810987e5: vmware_sev_es_hcall_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vmware_sev_es_hcall_prepare(struct ghcb *ghcb, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fcd0)
Location: arch/x86/kernel/cpu/vmware.c:484
Inline: False
```
**Symbols:**

```
ffffffff8109fcd0-ffffffff8109fd85: vmware_sev_es_hcall_prepare (STB_LOCAL)
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
