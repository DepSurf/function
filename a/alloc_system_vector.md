# Function: <code>alloc_system_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void alloc_system_vector(int vector);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqinit.c (ffffffff8107cbd7)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f36d)
Location: arch/x86/include/asm/desc.h:382
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff814c9d81)
Location: arch/x86/include/asm/desc.h:382
Inline: True
```
**Symbols:**

```
ffffffff8107cbd7-ffffffff8107cc09: alloc_system_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void alloc_system_vector(int vector);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqinit.c (ffffffff8107e644)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f4bc)
Location: arch/x86/include/asm/desc.h:382
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8151a900)
Location: arch/x86/include/asm/desc.h:382
Inline: True
```
**Symbols:**

```
ffffffff8107e644-ffffffff8107e672: alloc_system_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void alloc_system_vector(int vector);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqinit.c (ffffffff81082c57)
Location: arch/x86/include/asm/desc.h:382
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051cbc)
Location: arch/x86/include/asm/desc.h:382
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81546dd2)
Location: arch/x86/include/asm/desc.h:382
Inline: True
```
**Symbols:**

```
ffffffff81082c57-ffffffff81082c85: alloc_system_vector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void alloc_system_vector(int vector);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irqinit.c (ffffffff81030961)
Location: arch/x86/include/asm/desc.h:489
Inline: True
Direct callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810517dc)
Location: arch/x86/include/asm/desc.h:489
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8155abc0)
Location: arch/x86/include/asm/desc.h:489
Inline: True
```
**Symbols:**

```
ffffffff81030961-ffffffff8103098f: alloc_system_vector (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
