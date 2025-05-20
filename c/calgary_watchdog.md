# Function: <code>calgary_watchdog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void calgary_watchdog(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067b00)
Location: arch/x86/kernel/pci-calgary_64.c:892
Inline: False
```
**Symbols:**

```
ffffffff81067b00-ffffffff81067bb8: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void calgary_watchdog(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067860)
Location: arch/x86/kernel/pci-calgary_64.c:892
Inline: False
```
**Symbols:**

```
ffffffff81067860-ffffffff8106791f: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void calgary_watchdog(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b4b0)
Location: arch/x86/kernel/pci-calgary_64.c:892
Inline: False
```
**Symbols:**

```
ffffffff8106b4b0-ffffffff8106b56f: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void calgary_watchdog(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106a8e0)
Location: arch/x86/kernel/pci-calgary_64.c:901
Inline: False
```
**Symbols:**

```
ffffffff8106a8e0-ffffffff8106a995: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106f1f0)
Location: arch/x86/kernel/pci-calgary_64.c:901
Inline: True
```
**Symbols:**

```
ffffffff8106f1f0-ffffffff8106f299: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81071db0)
Location: arch/x86/kernel/pci-calgary_64.c:900
Inline: True
```
**Symbols:**

```
ffffffff81071db0-ffffffff81071e60: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81077df0)
Location: arch/x86/kernel/pci-calgary_64.c:884
Inline: True
```
**Symbols:**

```
ffffffff81077df0-ffffffff81077ea0: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b980)
Location: arch/x86/kernel/pci-calgary_64.c:872
Inline: True
```
**Symbols:**

```
ffffffff8107b980-ffffffff8107ba26: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107ca70)
Location: arch/x86/kernel/pci-calgary_64.c:874
Inline: True
```
**Symbols:**

```
ffffffff8107ca70-ffffffff8107cb16: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107ba70)
Location: arch/x86/kernel/pci-calgary_64.c:874
Inline: True
```
**Symbols:**

```
ffffffff8107ba70-ffffffff8107bb16: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b1a0)
Location: arch/x86/kernel/pci-calgary_64.c:874
Inline: True
```
**Symbols:**

```
ffffffff8106b1a0-ffffffff8106b246: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107ba20)
Location: arch/x86/kernel/pci-calgary_64.c:874
Inline: True
```
**Symbols:**

```
ffffffff8107ba20-ffffffff8107bac6: calgary_watchdog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void calgary_watchdog(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107db20)
Location: arch/x86/kernel/pci-calgary_64.c:874
Inline: True
```
**Symbols:**

```
ffffffff8107db20-ffffffff8107dbc6: calgary_watchdog (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timer_list *t</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int data</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
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
