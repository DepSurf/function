# Function: <code>dpc_handler</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8154ccf0)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffff8154ccf0-ffffffff8154ceef: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffff8157c8e0-ffffffff8157c964: dpc_handler (STB_LOCAL)
ffffffff8157cf21-ffffffff8157d0a3: dpc_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffff8159e340-ffffffff8159e3c4: dpc_handler (STB_LOCAL)
ffffffff8159e981-ffffffff8159eb03: dpc_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8163e430)
Location: drivers/pci/pcie/dpc.c:229
Inline: False
```
**Symbols:**

```
ffffffff8163e430-ffffffff8163e465: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81664b50)
Location: drivers/pci/pcie/dpc.c:232
Inline: False
```
**Symbols:**

```
ffffffff81664b50-ffffffff81664b85: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81647100)
Location: drivers/pci/pcie/dpc.c:296
Inline: False
```
**Symbols:**

```
ffffffff81647100-ffffffff81647135: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff816b89b0)
Location: drivers/pci/pcie/dpc.c:296
Inline: False
```
**Symbols:**

```
ffffffff816b89b0-ffffffff816b89e5: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff817dce90)
Location: drivers/pci/pcie/dpc.c:296
Inline: False
```
**Symbols:**

```
ffffffff817dce90-ffffffff817dcece: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff818ff380)
Location: drivers/pci/pcie/dpc.c:296
Inline: False
```
**Symbols:**

```
ffffffff818ff380-ffffffff818ff3be: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff819428f0)
Location: drivers/pci/pcie/dpc.c:295
Inline: False
```
**Symbols:**

```
ffffffff819428f0-ffffffff8194292e: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8198bbc0)
Location: drivers/pci/pcie/dpc.c:306
Inline: False
```
**Symbols:**

```
ffffffff8198bbc0-ffffffff8198bbfe: dpc_handler (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffff800010706658)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffff800010706658-ffff800010706860: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (c089d698)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
c089d698-c089d8b8: dpc_handler (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffe0004d42cc)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffe0004d42cc-ffffffe0004d44b2: dpc_handler (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffff81591b40-ffffffff81591bc4: dpc_handler (STB_LOCAL)
ffffffff81592191-ffffffff81592313: dpc_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffff81580ce0-ffffffff81580d64: dpc_handler (STB_LOCAL)
ffffffff81581321-ffffffff815814a3: dpc_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffff81592090-ffffffff81592114: dpc_handler (STB_LOCAL)
ffffffff815926d1-ffffffff81592853: dpc_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t dpc_handler(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:227
Inline: False
```
**Symbols:**

```
ffffffff815ac510-ffffffff815ac594: dpc_handler (STB_LOCAL)
ffffffff815acb51-ffffffff815accd3: dpc_handler.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
