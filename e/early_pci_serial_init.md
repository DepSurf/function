# Function: <code>early_pci_serial_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff81f73be5)
Location: arch/x86/kernel/early_printk.c:217
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff81f9c410)
Location: arch/x86/kernel/early_printk.c:217
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff81fd795b)
Location: arch/x86/kernel/early_printk.c:217
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff820b878c)
Location: arch/x86/kernel/early_printk.c:218
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff826befd6)
Location: arch/x86/kernel/early_printk.c:219
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff826e8dcc)
Location: arch/x86/kernel/early_printk.c:219
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
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
In arch/x86/kernel/early_printk.c (ffffffff8289f93f)
Location: arch/x86/kernel/early_printk.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
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
In arch/x86/kernel/early_printk.c (ffffffff828b787d)
Location: arch/x86/kernel/early_printk.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
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
In arch/x86/kernel/early_printk.c (ffffffff828bdd7b)
Location: arch/x86/kernel/early_printk.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff82ce2053)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff82ce2053-ffffffff82ce2273: early_pci_serial_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff82fcf277)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff82fcf277-ffffffff82fcf497: early_pci_serial_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff831d9d0d)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff831d9d0d-ffffffff831d9f2e: early_pci_serial_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff832bcd8e)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff832bcd8e-ffffffff832bcfaf: early_pci_serial_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff8346e71f)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff8346e71f-ffffffff8346e955: early_pci_serial_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff83e948d0)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff83e948d0-ffffffff83e94b4b: early_pci_serial_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff836b8430)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff836b8430-ffffffff836b86b0: early_pci_serial_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_pci_serial_init(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early_printk.c (ffffffff838e8d40)
Location: arch/x86/kernel/early_printk.c:217
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
```
**Symbols:**

```
ffffffff838e8d40-ffffffff838e8fc0: early_pci_serial_init (STB_LOCAL)
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
In arch/x86/kernel/early_printk.c (ffffffff828a8d72)
Location: arch/x86/kernel/early_printk.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
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
In arch/x86/kernel/early_printk.c (ffffffff828a0e45)
Location: arch/x86/kernel/early_printk.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
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
In arch/x86/kernel/early_printk.c (ffffffff828bbc71)
Location: arch/x86/kernel/early_printk.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
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
In arch/x86/kernel/early_printk.c (ffffffff828beda8)
Location: arch/x86/kernel/early_printk.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
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
