# Function: <code>fill_prstatus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fill_prstatus(struct elf_prstatus *prstatus, struct task_struct *p, long int signr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8126711c)
Location: fs/binfmt_elf.c:1403
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81269810)
Location: fs/binfmt_elf.c:1403
Inline: False
```
**Symbols:**

```
ffffffff81269810-ffffffff812699a4: fill_prstatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fill_prstatus(struct elf_prstatus *prstatus, struct task_struct *p, long int signr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8129486d)
Location: fs/binfmt_elf.c:1411
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81295b10)
Location: fs/binfmt_elf.c:1411
Inline: False
```
**Symbols:**

```
ffffffff81295b10-ffffffff81295ca4: fill_prstatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fill_prstatus(struct elf_prstatus *prstatus, struct task_struct *p, long int signr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812a9525)
Location: fs/binfmt_elf.c:1411
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812aa760)
Location: fs/binfmt_elf.c:1411
Inline: False
```
**Symbols:**

```
ffffffff812aa760-ffffffff812aa8f4: fill_prstatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b5e82)
Location: fs/binfmt_elf.c:1469
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b8f0f)
Location: fs/binfmt_elf.c:1469
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d9726)
Location: fs/binfmt_elf.c:1483
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dc807)
Location: fs/binfmt_elf.c:1483
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81303fdc)
Location: fs/binfmt_elf.c:1495
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813078e9)
Location: fs/binfmt_elf.c:1495
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8131972c)
Location: fs/binfmt_elf.c:1495
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d0f9)
Location: fs/binfmt_elf.c:1495
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813423ee)
Location: fs/binfmt_elf.c:1498
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81345d34)
Location: fs/binfmt_elf.c:1498
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8135a824)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e037)
Location: fs/binfmt_elf.c:1472
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
void fill_prstatus(struct elf_prstatus *prstatus, struct task_struct *p, long int signr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139e8f0)
Location: fs/binfmt_elf.c:1590
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2a70)
Location: fs/binfmt_elf.c:1590
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff8139e8f0-ffffffff8139ea45: fill_prstatus (STB_LOCAL)
ffffffff813a2a70-ffffffff813a2bb0: fill_prstatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
void fill_prstatus(struct elf_prstatus *prstatus, struct task_struct *p, long int signr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813afed0)
Location: fs/binfmt_elf.c:1498
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3ae0)
Location: fs/binfmt_elf.c:1498
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
**Symbols:**

```
ffffffff813afed0-ffffffff813b002a: fill_prstatus (STB_LOCAL)
ffffffff813b3ae0-ffffffff813b3c25: fill_prstatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b73d8)
Location: fs/binfmt_elf.c:1501
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff813baad9)
Location: fs/binfmt_elf.c:1501
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff814070b8)
Location: fs/binfmt_elf.c:1501
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a7d9)
Location: fs/binfmt_elf.c:1501
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147bc18)
Location: fs/binfmt_elf.c:1536
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f539)
Location: fs/binfmt_elf.c:1536
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150e658)
Location: fs/binfmt_elf.c:1531
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff81512689)
Location: fs/binfmt_elf.c:1531
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81545e18)
Location: fs/binfmt_elf.c:1536
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a0c5)
Location: fs/binfmt_elf.c:1536
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157b2f9)
Location: fs/binfmt_elf.c:1471
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_thread_core_info
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f0d5)
Location: fs/binfmt_elf.c:1471
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041fe1c)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff80001042397c)
Location: fs/binfmt_elf.c:1472
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void fill_prstatus(struct elf_prstatus *prstatus, struct task_struct *p, long int signr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e8324)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (c05e93b0)
Location: fs/binfmt_elf_fdpic.c:1342
Inline: False
Direct callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
```
**Symbols:**

```
c05e93b0-c05e9544: fill_prstatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052ece8)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000532908)
Location: fs/binfmt_elf.c:1472
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffe0002c0df2)
Location: fs/binfmt_elf.c:1472
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81352e04)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81356617)
Location: fs/binfmt_elf.c:1472
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81343ae4)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813472d7)
Location: fs/binfmt_elf.c:1472
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813508d4)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813540e7)
Location: fs/binfmt_elf.c:1472
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81363e54)
Location: fs/binfmt_elf.c:1472
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813678a8)
Location: fs/binfmt_elf.c:1472
Inline: True
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
