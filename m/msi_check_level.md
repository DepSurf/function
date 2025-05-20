# Function: <code>msi_check_level</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810ffe50)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff810ffe50-ffffffff810ffe89: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110b610)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff8110b610-ffffffff8110b649: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/msi.c (ffffffff8111554f)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff81114cf0-ffffffff81114d33: msi_check_level (STB_LOCAL)
ffffffff8111554f-ffffffff81115562: msi_check_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81120ef0)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff81120ef0-ffffffff81120f2a: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8112d4d0)
Location: kernel/irq/msi.c:79
Inline: True
Direct callers:
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff8112d4d0-ffffffff8112d50a: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81128fd0)
Location: kernel/irq/msi.c:79
Inline: True
Direct callers:
  - kernel/irq/msi.c:msi_domain_activate
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff81128fd0-ffffffff8112900a: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811292b0)
Location: kernel/irq/msi.c:79
Inline: True
Direct callers:
  - kernel/irq/msi.c:msi_domain_activate
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff811292b0-ffffffff811292ea: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811494f0)
Location: kernel/irq/msi.c:215
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_activate
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff811494f0-ffffffff8114952a: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116e0e0)
Location: kernel/irq/msi.c:469
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_activate
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff8116e0e0-ffffffff8116e128: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a3420)
Location: kernel/irq/msi.c:623
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_activate
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff811a3420-ffffffff811a346b: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b52f0)
Location: kernel/irq/msi.c:623
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_activate
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff811b52f0-ffffffff811b533b: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c5170)
Location: kernel/irq/msi.c:623
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_activate
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
ffffffff811c5170-ffffffff811c51bb: msi_check_level (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffff800010187070)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffff800010187070-ffff8000101870d4: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (c03d5c50)
Location: kernel/irq/msi.c:79
Inline: True
Direct callers:
  - kernel/irq/msi.c:msi_domain_set_affinity
```
**Symbols:**

```
c03d5c50-c03d5cc8: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffe00011cd8a)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffe00011cd8a-ffffffe00011cdd8: msi_check_level (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811194d0)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff811194d0-ffffffff8111950a: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110a540)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff8110a540-ffffffff8110a57a: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811173c0)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff811173c0-ffffffff811173fa: msi_check_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void msi_check_level(struct irq_domain *domain, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81122a50)
Location: kernel/irq/msi.c:79
Inline: True
```
**Symbols:**

```
ffffffff81122a50-ffffffff81122a8a: msi_check_level (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
