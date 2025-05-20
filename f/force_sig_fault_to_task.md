# Function: <code>force_sig_fault_to_task</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae7d8)
Location: kernel/signal.c:1651
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810ae730-ffffffff810ae7a3: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4de8)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810b4d40-ffffffff810b4db3: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bda80)
Location: kernel/signal.c:1652
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810bd9f0-ffffffff810bda4e: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8d90)
Location: kernel/signal.c:1653
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810b8d00-ffffffff810b8d5e: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba380)
Location: kernel/signal.c:1655
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810ba2f0-ffffffff810ba34e: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ccbe0)
Location: kernel/signal.c:1702
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810cca40-ffffffff810ccaa0: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e3f20)
Location: kernel/signal.c:1703
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810e3d30-ffffffff810e3db0: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104580)
Location: kernel/signal.c:1704
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff81104360-ffffffff811043e0: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110800)
Location: kernel/signal.c:1710
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff811105e0-ffffffff81110660: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111a150)
Location: kernel/signal.c:1716
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff81119f30-ffffffff81119fb0: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110f90)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffff800010110ec0-ffff800010110f4c: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368794)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
c03686c0-c0368748: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158868)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
c0000000001587a0-c00000000015882c: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0940)
Location: kernel/signal.c:1656
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffe0000d0940-ffffffe0000d09a0: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af158)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810af0b0-ffffffff810af123: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109daa8)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff8109da00-ffffffff8109da73: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae6b8)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810ae610-ffffffff810ae683: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int force_sig_fault_to_task(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6928)
Location: kernel/signal.c:1656
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_fault
```
**Symbols:**

```
ffffffff810b6880-ffffffff810b68f3: force_sig_fault_to_task (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
