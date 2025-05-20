# Function: <code>__x2apic_send_IPI_shorthand</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106de35)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8106ded0-ffffffff8106defd: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810752e5)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810753a0-ffffffff810753cd: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075945)
Location: arch/x86/kernel/apic/x2apic_phys.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81075a00-ffffffff81075a30: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810763e5)
Location: arch/x86/kernel/apic/x2apic_phys.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810764a0-ffffffff810764d0: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083a35)
Location: arch/x86/kernel/apic/x2apic_phys.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81083af0-ffffffff81083b20: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093a15)
Location: arch/x86/kernel/apic/x2apic_phys.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81093b00-ffffffff81093b49: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a9145)
Location: arch/x86/kernel/apic/x2apic_phys.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810a9200-ffffffff810a9249: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac305)
Location: arch/x86/kernel/apic/x2apic_phys.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810ac420-ffffffff810ac469: __x2apic_send_IPI_shorthand (STB_GLOBAL)
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2ec5)
Location: arch/x86/kernel/apic/x2apic_phys.c:86
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cdd5)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8106ce70-ffffffff8106ce9d: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105d0f5)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8105d260-ffffffff8105d29b: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d285)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8106d320-ffffffff8106d34d: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f505)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8106f5a0-ffffffff8106f5cd: __x2apic_send_IPI_shorthand (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
