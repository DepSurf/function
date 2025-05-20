# Function: <code>handle_irq_desc</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int handle_irq_desc(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113daf0)
Location: kernel/irq/irqdesc.c:635
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/irqdesc.c:generic_handle_irq
```
**Symbols:**

```
ffffffff8113daf0-ffffffff8113db34: handle_irq_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int handle_irq_desc(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161a20)
Location: kernel/irq/irqdesc.c:637
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
```
**Symbols:**

```
ffffffff81161a20-ffffffff81161a76: handle_irq_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int handle_irq_desc(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195120)
Location: kernel/irq/irqdesc.c:640
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
```
**Symbols:**

```
ffffffff81195120-ffffffff81195176: handle_irq_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int handle_irq_desc(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6ab0)
Location: kernel/irq/irqdesc.c:661
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
```
**Symbols:**

```
ffffffff811a6ab0-ffffffff811a6b06: handle_irq_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int handle_irq_desc(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b65d0)
Location: kernel/irq/irqdesc.c:661
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
```
**Symbols:**

```
ffffffff811b65d0-ffffffff811b6626: handle_irq_desc (STB_GLOBAL)
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
