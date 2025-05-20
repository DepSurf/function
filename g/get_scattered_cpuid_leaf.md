# Function: <code>get_scattered_cpuid_leaf</code>

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
u32 get_scattered_cpuid_leaf(unsigned int level, unsigned int sub_leaf, enum cpuid_regs_idx reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103f6b0)
Location: arch/x86/kernel/cpu/scattered.c:59
Inline: False
```
**Symbols:**

```
ffffffff8103f6b0-ffffffff8103f724: get_scattered_cpuid_leaf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 get_scattered_cpuid_leaf(unsigned int level, unsigned int sub_leaf, enum cpuid_regs_idx reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/scattered.c (ffffffff8103d5a0)
Location: arch/x86/kernel/cpu/scattered.c:60
Inline: False
```
**Symbols:**

```
ffffffff8103d5a0-ffffffff8103d614: get_scattered_cpuid_leaf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 get_scattered_cpuid_leaf(unsigned int level, unsigned int sub_leaf, enum cpuid_regs_idx reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/scattered.c (ffffffff81040120)
Location: arch/x86/kernel/cpu/scattered.c:59
Inline: False
```
**Symbols:**

```
ffffffff81040120-ffffffff810401be: get_scattered_cpuid_leaf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 get_scattered_cpuid_leaf(unsigned int level, unsigned int sub_leaf, enum cpuid_regs_idx reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/scattered.c (ffffffff81041950)
Location: arch/x86/kernel/cpu/scattered.c:60
Inline: False
```
**Symbols:**

```
ffffffff81041950-ffffffff810419ef: get_scattered_cpuid_leaf (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
