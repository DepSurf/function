# Function: <code>bind_ipi_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c95b8)
Location: drivers/xen/events/events_base.c:869
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a0c8)
Location: drivers/xen/events/events_base.c:880
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815465b8)
Location: drivers/xen/events/events_base.c:879
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155a3e8)
Location: drivers/xen/events/events_base.c:871
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815be828)
Location: drivers/xen/events/events_base.c:871
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f6e80)
Location: drivers/xen/events/events_base.c:869
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611f10)
Location: drivers/xen/events/events_base.c:869
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81645c60)
Location: drivers/xen/events/events_base.c:870
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816681f0)
Location: drivers/xen/events/events_base.c:870
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bind_ipi_to_irq(unsigned int ipi, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717650)
Location: drivers/xen/events/events_base.c:884
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
**Symbols:**

```
ffffffff81717650-ffffffff81717828: bind_ipi_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bind_ipi_to_irq(unsigned int ipi, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734880)
Location: drivers/xen/events/events_base.c:1216
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
**Symbols:**

```
ffffffff81734880-ffffffff81734a5e: bind_ipi_to_irq (STB_LOCAL)
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
In drivers/xen/events/events_base.c (ffffffff81719059)
Location: drivers/xen/events/events_base.c:1254
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
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
In drivers/xen/events/events_base.c (ffffffff81796ceb)
Location: drivers/xen/events/events_base.c:1260
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
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
In drivers/xen/events/events_base.c (ffffffff818cfc9c)
Location: drivers/xen/events/events_base.c:1260
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
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
In drivers/xen/events/events_base.c (ffffffff81a2140c)
Location: drivers/xen/events/events_base.c:1262
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6a79c)
Location: drivers/xen/events/events_base.c:1255
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
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
In drivers/xen/events/events_base.c (ffffffff81abca0b)
Location: drivers/xen/events/events_base.c:1250
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010832234)
Location: drivers/xen/events/events_base.c:870
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162df20)
Location: drivers/xen/events/events_base.c:874
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165c030)
Location: drivers/xen/events/events_base.c:870
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81676620)
Location: drivers/xen/events/events_base.c:870
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
