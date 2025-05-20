# Function: <code>__irq_disable</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9320)
Location: kernel/irq/chip.c:320
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
```
**Symbols:**

```
ffffffff810e9320-ffffffff810e9387: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f1790)
Location: kernel/irq/chip.c:343
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
```
**Symbols:**

```
ffffffff810f1790-ffffffff810f17fa: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f9a80)
Location: kernel/irq/chip.c:341
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
```
**Symbols:**

```
ffffffff810f9a80-ffffffff810f9ae8: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105240)
Location: kernel/irq/chip.c:341
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_shutdown
```
**Symbols:**

```
ffffffff81105240-ffffffff811052a8: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110e520)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffffffff8110e520-ffffffff8110e58c: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111a7e0)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffffffff8111a7e0-ffffffff8111a84c: __irq_disable (STB_LOCAL)
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
In kernel/irq/chip.c (ffffffff8112792c)
Location: kernel/irq/chip.c:347
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
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
In kernel/irq/chip.c (ffffffff8112352c)
Location: kernel/irq/chip.c:347
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
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
In kernel/irq/chip.c (ffffffff8112388c)
Location: kernel/irq/chip.c:350
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
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
In kernel/irq/chip.c (ffffffff81143e5c)
Location: kernel/irq/chip.c:350
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
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
In kernel/irq/chip.c (ffffffff811678dc)
Location: kernel/irq/chip.c:347
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
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
In kernel/irq/chip.c (ffffffff8119bccc)
Location: kernel/irq/chip.c:349
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811adb2c)
Location: kernel/irq/chip.c:350
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff811ace70-ffffffff811acf0d: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bd72c)
Location: kernel/irq/chip.c:350
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/chip.c:irq_shutdown_and_deactivate
```
**Symbols:**

```
ffffffff811bca70-ffffffff811bcb0d: __irq_disable (STB_LOCAL)
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
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017df08)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffff80001017df08-ffff80001017df94: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03ce7f8)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
c03ce7f8-c03ce884: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d8a80)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
c0000000001d8a80-c0000000001d8b44: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe000116a2a)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffffffe000116a2a-ffffffe000116aa6: __irq_disable (STB_LOCAL)
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
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112dc0)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffffffff81112dc0-ffffffff81112e2c: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81103ae0)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffffffff81103ae0-ffffffff81103b4c: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81110cb0)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffffffff81110cb0-ffffffff81110d1c: __irq_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __irq_disable(struct irq_desc *desc, bool mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111c480)
Location: kernel/irq/chip.c:347
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_disable
```
**Symbols:**

```
ffffffff8111c480-ffffffff8111c4ec: __irq_disable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
