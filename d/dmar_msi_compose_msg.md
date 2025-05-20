# Function: <code>dmar_msi_compose_msg</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dmar_msi_compose_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81074420)
Location: arch/x86/kernel/apic/msi.c:257
Inline: False
```
**Symbols:**

```
ffffffff81074420-ffffffff81074449: dmar_msi_compose_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dmar_msi_compose_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81074ed0)
Location: arch/x86/kernel/apic/msi.c:261
Inline: False
```
**Symbols:**

```
ffffffff81074ed0-ffffffff81074ef9: dmar_msi_compose_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dmar_msi_compose_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81082380)
Location: arch/x86/kernel/apic/msi.c:261
Inline: False
```
**Symbols:**

```
ffffffff81082380-ffffffff810823a9: dmar_msi_compose_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dmar_msi_compose_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81091f40)
Location: arch/x86/kernel/apic/msi.c:259
Inline: False
```
**Symbols:**

```
ffffffff81091f40-ffffffff81091f74: dmar_msi_compose_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dmar_msi_compose_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810a6f50)
Location: arch/x86/kernel/apic/msi.c:306
Inline: False
```
**Symbols:**

```
ffffffff810a6f50-ffffffff810a6f84: dmar_msi_compose_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dmar_msi_compose_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810aa1b0)
Location: arch/x86/kernel/apic/msi.c:306
Inline: False
```
**Symbols:**

```
ffffffff810aa1b0-ffffffff810aa1e4: dmar_msi_compose_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dmar_msi_compose_msg(struct irq_data *data, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810b1240)
Location: arch/x86/kernel/apic/msi.c:304
Inline: False
```
**Symbols:**

```
ffffffff810b1240-ffffffff810b1274: dmar_msi_compose_msg (STB_LOCAL)
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
