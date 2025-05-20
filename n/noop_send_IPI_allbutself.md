# Function: <code>noop_send_IPI_allbutself</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: arch/x86/kernel/apic/apic_noop.c:35
Inline: False
```
**Symbols:**

```
ffffffff81054ca0-ffffffff81054cab: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: arch/x86/kernel/apic/apic_noop.c:35
Inline: False
```
**Symbols:**

```
ffffffff81057a60-ffffffff81057a6b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81056ff0)
Location: arch/x86/kernel/apic/apic_noop.c:35
Inline: True
```
**Symbols:**

```
ffffffff81056ff0-ffffffff81056ffb: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105ad20)
Location: arch/x86/kernel/apic/apic_noop.c:36
Inline: True
```
**Symbols:**

```
ffffffff8105ad20-ffffffff8105ad2b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105dd20)
Location: arch/x86/kernel/apic/apic_noop.c:36
Inline: True
```
**Symbols:**

```
ffffffff8105dd20-ffffffff8105dd2b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810639b0)
Location: arch/x86/kernel/apic/apic_noop.c:36
Inline: True
```
**Symbols:**

```
ffffffff810639b0-ffffffff810639bb: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067080)
Location: arch/x86/kernel/apic/apic_noop.c:36
Inline: False
```
**Symbols:**

```
ffffffff81067080-ffffffff8106708b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810676f0)
Location: arch/x86/kernel/apic/apic_noop.c:20
Inline: False
```
**Symbols:**

```
ffffffff810676f0-ffffffff810676fb: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106e430)
Location: arch/x86/kernel/apic/apic_noop.c:20
Inline: True
```
**Symbols:**

```
ffffffff8106e430-ffffffff8106e43b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106f8b0)
Location: arch/x86/kernel/apic/apic_noop.c:21
Inline: True
```
**Symbols:**

```
ffffffff8106f8b0-ffffffff8106f8bb: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810703e0)
Location: arch/x86/kernel/apic/apic_noop.c:21
Inline: True
```
**Symbols:**

```
ffffffff810703e0-ffffffff810703eb: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8107bf80)
Location: arch/x86/kernel/apic/apic_noop.c:21
Inline: True
```
**Symbols:**

```
ffffffff8107bf80-ffffffff8107bf8b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8108b220)
Location: arch/x86/kernel/apic/apic_noop.c:21
Inline: True
```
**Symbols:**

```
ffffffff8108b220-ffffffff8108b22f: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8109f4c0)
Location: arch/x86/kernel/apic/apic_noop.c:21
Inline: True
```
**Symbols:**

```
ffffffff8109f4c0-ffffffff8109f4cf: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810a2450)
Location: arch/x86/kernel/apic/apic_noop.c:21
Inline: True
```
**Symbols:**

```
ffffffff810a2450-ffffffff810a245f: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810a91f0)
Location: arch/x86/kernel/apic/apic_noop.c:26
Inline: True
```
**Symbols:**

```
ffffffff810a91f0-ffffffff810a91ff: noop_send_IPI_allbutself (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810671e0)
Location: arch/x86/kernel/apic/apic_noop.c:20
Inline: False
```
**Symbols:**

```
ffffffff810671e0-ffffffff810671eb: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810575a0)
Location: arch/x86/kernel/apic/apic_noop.c:20
Inline: False
```
**Symbols:**

```
ffffffff810575a0-ffffffff810575ab: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067690)
Location: arch/x86/kernel/apic/apic_noop.c:20
Inline: False
```
**Symbols:**

```
ffffffff81067690-ffffffff8106769b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void noop_send_IPI_allbutself(int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81068c70)
Location: arch/x86/kernel/apic/apic_noop.c:20
Inline: False
```
**Symbols:**

```
ffffffff81068c70-ffffffff81068c7b: noop_send_IPI_allbutself (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
