# Function: <code>irq_sysfs_add</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5a40)
Location: kernel/irq/irqdesc.c:257
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff810e5a40-ffffffff810e5a8a: irq_sysfs_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5050)
Location: kernel/irq/irqdesc.c:269
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff810e5050-ffffffff810e5099: irq_sysfs_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ed2b0)
Location: kernel/irq/irqdesc.c:267
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff810ed2b0-ffffffff810ed2f9: irq_sysfs_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:284
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff810f5680-ffffffff810f56bc: irq_sysfs_add (STB_LOCAL)
ffffffff810f61e2-ffffffff810f61f5: irq_sysfs_add.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:284
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff81100e10-ffffffff81100e4c: irq_sysfs_add (STB_LOCAL)
ffffffff81101950-ffffffff81101963: irq_sysfs_add.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff81109610-ffffffff81109650: irq_sysfs_add (STB_LOCAL)
ffffffff8110a160-ffffffff8110a174: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff811159e0-ffffffff81115a20: irq_sysfs_add (STB_LOCAL)
ffffffff81116530-ffffffff81116544: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121acf)
Location: kernel/irq/irqdesc.c:286
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff81121380-ffffffff811213c2: irq_sysfs_add (STB_LOCAL)
ffffffff81122130-ffffffff81122144: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111db2f)
Location: kernel/irq/irqdesc.c:286
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff8111d380-ffffffff8111d3c2: irq_sysfs_add (STB_LOCAL)
ffffffff81be1563-ffffffff81be1577: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111de3f)
Location: kernel/irq/irqdesc.c:286
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff8111d700-ffffffff8111d742: irq_sysfs_add (STB_LOCAL)
ffffffff81bd361e-ffffffff81bd3632: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e28b)
Location: kernel/irq/irqdesc.c:286
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff8113daa0-ffffffff8113dae2: irq_sysfs_add (STB_LOCAL)
ffffffff81cad48c-ffffffff81cad4a0: irq_sysfs_add.cold (STB_LOCAL)
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
In kernel/irq/irqdesc.c (ffffffff8116185e)
Location: kernel/irq/irqdesc.c:286
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
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
In kernel/irq/irqdesc.c (ffffffff81194eee)
Location: kernel/irq/irqdesc.c:286
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
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
In kernel/irq/irqdesc.c (ffffffff811a6736)
Location: kernel/irq/irqdesc.c:318
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
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
In kernel/irq/irqdesc.c (ffffffff811b6259)
Location: kernel/irq/irqdesc.c:318
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
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
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff8000101771d8)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffff8000101771d8-ffff800010177238: irq_sysfs_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c8e3c)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
c03c8e3c-c03c8ea0: irq_sysfs_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d0ac0)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
c0000000001d0ac0-c0000000001d0b48: irq_sysfs_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe0001120b4)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffe0001120b4-ffffffe000112110: irq_sysfs_add (STB_LOCAL)
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
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff8110dfc0-ffffffff8110e000: irq_sysfs_add (STB_LOCAL)
ffffffff8110eb10-ffffffff8110eb24: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff810fed20-ffffffff810fed60: irq_sysfs_add (STB_LOCAL)
ffffffff810ff860-ffffffff810ff874: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff8110beb0-ffffffff8110bef0: irq_sysfs_add (STB_LOCAL)
ffffffff8110ca00-ffffffff8110ca14: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:286
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
```
**Symbols:**

```
ffffffff811173e0-ffffffff81117420: irq_sysfs_add (STB_LOCAL)
ffffffff81117f2a-ffffffff81117f3e: irq_sysfs_add.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
