# Function: <code>kvm_alloc_cpumask</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82ce2fc4)
Location: arch/x86/kernel/kvm.c:753
Inline: False
```
**Symbols:**

```
ffffffff82ce2fc4-ffffffff82ce304d: kvm_alloc_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff82fd02b6)
Location: arch/x86/kernel/kvm.c:797
Inline: False
```
**Symbols:**

```
ffffffff82fd02b6-ffffffff82fd033f: kvm_alloc_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff831dacc9)
Location: arch/x86/kernel/kvm.c:606
Inline: False
```
**Symbols:**

```
ffffffff831dacc9-ffffffff831dad54: kvm_alloc_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff832bdf1e)
Location: arch/x86/kernel/kvm.c:609
Inline: False
```
**Symbols:**

```
ffffffff832bdf1e-ffffffff832be004: kvm_alloc_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8346fac5)
Location: arch/x86/kernel/kvm.c:679
Inline: False
```
**Symbols:**

```
ffffffff8346fac5-ffffffff8346fbb4: kvm_alloc_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff83e96310)
Location: arch/x86/kernel/kvm.c:678
Inline: False
```
**Symbols:**

```
ffffffff83e96310-ffffffff83e9644f: kvm_alloc_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff836b9e90)
Location: arch/x86/kernel/kvm.c:678
Inline: False
```
**Symbols:**

```
ffffffff836b9e90-ffffffff836b9fcf: kvm_alloc_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kvm_alloc_cpumask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff838ea7c0)
Location: arch/x86/kernel/kvm.c:679
Inline: False
```
**Symbols:**

```
ffffffff838ea7c0-ffffffff838ea8ff: kvm_alloc_cpumask (STB_LOCAL)
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
