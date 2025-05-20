# Function: <code>noop_send_IPI_mask</code>

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
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: arch/x86/kernel/apic/apic_noop.c:33
Inline: False
```
**Symbols:**

```
ffffffff81054c90-ffffffff81054c9b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (0)
Location: arch/x86/kernel/apic/apic_noop.c:33
Inline: False
```
**Symbols:**

```
ffffffff81057a50-ffffffff81057a5b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81056fe0)
Location: arch/x86/kernel/apic/apic_noop.c:33
Inline: True
```
**Symbols:**

```
ffffffff81056fe0-ffffffff81056feb: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105ad10)
Location: arch/x86/kernel/apic/apic_noop.c:34
Inline: True
```
**Symbols:**

```
ffffffff8105ad10-ffffffff8105ad1b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105dd10)
Location: arch/x86/kernel/apic/apic_noop.c:34
Inline: True
```
**Symbols:**

```
ffffffff8105dd10-ffffffff8105dd1b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810639a0)
Location: arch/x86/kernel/apic/apic_noop.c:34
Inline: True
```
**Symbols:**

```
ffffffff810639a0-ffffffff810639ab: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067060)
Location: arch/x86/kernel/apic/apic_noop.c:34
Inline: False
```
**Symbols:**

```
ffffffff81067060-ffffffff8106706b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810676d0)
Location: arch/x86/kernel/apic/apic_noop.c:18
Inline: False
```
**Symbols:**

```
ffffffff810676d0-ffffffff810676db: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106e420)
Location: arch/x86/kernel/apic/apic_noop.c:18
Inline: True
```
**Symbols:**

```
ffffffff8106e420-ffffffff8106e42b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106f8a0)
Location: arch/x86/kernel/apic/apic_noop.c:19
Inline: True
```
**Symbols:**

```
ffffffff8106f8a0-ffffffff8106f8ab: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810703d0)
Location: arch/x86/kernel/apic/apic_noop.c:19
Inline: True
```
**Symbols:**

```
ffffffff810703d0-ffffffff810703db: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8107bf70)
Location: arch/x86/kernel/apic/apic_noop.c:19
Inline: True
```
**Symbols:**

```
ffffffff8107bf70-ffffffff8107bf7b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8108b210)
Location: arch/x86/kernel/apic/apic_noop.c:19
Inline: True
```
**Symbols:**

```
ffffffff8108b210-ffffffff8108b21f: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8109f4a0)
Location: arch/x86/kernel/apic/apic_noop.c:19
Inline: True
```
**Symbols:**

```
ffffffff8109f4a0-ffffffff8109f4af: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810a2430)
Location: arch/x86/kernel/apic/apic_noop.c:19
Inline: True
```
**Symbols:**

```
ffffffff810a2430-ffffffff810a243f: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810a91d0)
Location: arch/x86/kernel/apic/apic_noop.c:24
Inline: True
```
**Symbols:**

```
ffffffff810a91d0-ffffffff810a91df: noop_send_IPI_mask (STB_LOCAL)
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
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810671c0)
Location: arch/x86/kernel/apic/apic_noop.c:18
Inline: False
```
**Symbols:**

```
ffffffff810671c0-ffffffff810671cb: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81057580)
Location: arch/x86/kernel/apic/apic_noop.c:18
Inline: False
```
**Symbols:**

```
ffffffff81057580-ffffffff8105758b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067670)
Location: arch/x86/kernel/apic/apic_noop.c:18
Inline: False
```
**Symbols:**

```
ffffffff81067670-ffffffff8106767b: noop_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void noop_send_IPI_mask(const struct cpumask *cpumask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81068c50)
Location: arch/x86/kernel/apic/apic_noop.c:18
Inline: False
```
**Symbols:**

```
ffffffff81068c50-ffffffff81068c5b: noop_send_IPI_mask (STB_LOCAL)
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
