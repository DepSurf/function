# Function: <code>__default_send_IPI_shortcut</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a594)
Location: arch/x86/include/asm/ipi.h:61
Inline: True
```
```
In arch/x86/kernel/apic/probe_64.c (ffffffff8105a8d6)
Location: arch/x86/include/asm/ipi.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054cd0)
Location: arch/x86/kernel/apic/ipi.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff81054cd0-ffffffff81054d0b: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057a90)
Location: arch/x86/kernel/apic/ipi.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff81057a90-ffffffff81057acb: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057210)
Location: arch/x86/kernel/apic/ipi.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff81057210-ffffffff8105724b: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105aea0)
Location: arch/x86/kernel/apic/ipi.c:21
Inline: False
Direct callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff8105aea0-ffffffff8105aedb: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105dea0)
Location: arch/x86/kernel/apic/ipi.c:21
Inline: False
Direct callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff8105dea0-ffffffff8105dedb: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81063b30)
Location: arch/x86/kernel/apic/ipi.c:21
Inline: False
Direct callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff81063b30-ffffffff81063b6b: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810671f0)
Location: arch/x86/kernel/apic/ipi.c:21
Inline: False
Direct callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff810671f0-ffffffff8106722b: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067d45)
Location: arch/x86/kernel/apic/ipi.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81067a30-ffffffff81067a74: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106ea95)
Location: arch/x86/kernel/apic/ipi.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8106e780-ffffffff8106e7c7: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106ff15)
Location: arch/x86/kernel/apic/ipi.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8106fc00-ffffffff8106fc47: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81070a65)
Location: arch/x86/kernel/apic/ipi.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81070730-ffffffff8107077b: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c6e5)
Location: arch/x86/kernel/apic/ipi.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8107c300-ffffffff8107c34b: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8108baa5)
Location: arch/x86/kernel/apic/ipi.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8108b6a0-ffffffff8108b6f5: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8109ff25)
Location: arch/x86/kernel/apic/ipi.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8109fa90-ffffffff8109fae5: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2ea5)
Location: arch/x86/kernel/apic/ipi.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810a2a20-ffffffff810a2a75: __default_send_IPI_shortcut (STB_GLOBAL)
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
In arch/x86/kernel/apic/ipi.c (ffffffff810a9dc5)
Location: arch/x86/kernel/apic/ipi.c:152
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
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
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067835)
Location: arch/x86/kernel/apic/ipi.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81067520-ffffffff81067564: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057ba5)
Location: arch/x86/kernel/apic/ipi.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810578e0-ffffffff81057924: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067ce5)
Location: arch/x86/kernel/apic/ipi.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810679d0-ffffffff81067a14: __default_send_IPI_shortcut (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_shortcut(unsigned int shortcut, int vector);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810692c5)
Location: arch/x86/kernel/apic/ipi.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81068fb0-ffffffff81068ff4: __default_send_IPI_shortcut (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int dest</code>
</li>
</ul>
</details>
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
