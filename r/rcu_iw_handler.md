# Function: <code>rcu_iw_handler</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc5e0)
Location: kernel/rcu/tree.c:1277
Inline: False
```
**Symbols:**

```
ffffffff810fc5e0-ffffffff810fc628: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81105d90)
Location: kernel/rcu/tree.c:1153
Inline: False
```
**Symbols:**

```
ffffffff81105d90-ffffffff81105dd8: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811118b0)
Location: kernel/rcu/tree.c:1030
Inline: False
```
**Symbols:**

```
ffffffff811118b0-ffffffff811118f8: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111afe0)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffffffff8111afe0-ffffffff8111b024: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811273d0)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffffffff811273d0-ffffffff81127414: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811350f0)
Location: kernel/rcu/tree_stall.h:179
Inline: False
```
**Symbols:**

```
ffffffff811350f0-ffffffff81135134: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81130930)
Location: kernel/rcu/tree_stall.h:185
Inline: False
```
**Symbols:**

```
ffffffff81130930-ffffffff81130974: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811310d0)
Location: kernel/rcu/tree_stall.h:185
Inline: False
```
**Symbols:**

```
ffffffff811310d0-ffffffff81131114: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:184
Inline: False
```
**Symbols:**

```
ffffffff81152f00-ffffffff81152f57: rcu_iw_handler (STB_LOCAL)
ffffffff81caedca-ffffffff81caeddf: rcu_iw_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:212
Inline: False
```
**Symbols:**

```
ffffffff81178c80-ffffffff81178cf6: rcu_iw_handler (STB_LOCAL)
ffffffff81e5ed64-ffffffff81e5ed79: rcu_iw_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:212
Inline: False
```
**Symbols:**

```
ffffffff811b0520-ffffffff811b0596: rcu_iw_handler (STB_LOCAL)
ffffffff82059f4f-ffffffff82059f64: rcu_iw_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:212
Inline: False
```
**Symbols:**

```
ffffffff811c24f0-ffffffff811c2566: rcu_iw_handler (STB_LOCAL)
ffffffff820d8755-ffffffff820d876a: rcu_iw_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:219
Inline: False
```
**Symbols:**

```
ffffffff811d2a60-ffffffff811d2ad6: rcu_iw_handler (STB_LOCAL)
ffffffff821b3a0b-ffffffff821b3a20: rcu_iw_handler.cold (STB_LOCAL)
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
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018c9f0)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffff80001018c9f0-ffff80001018ca9c: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03da16c)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
c03da16c-c03da1fc: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e6a10)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
c0000000001e6a10-c0000000001e6b00: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe00012210e)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffffffe00012210e-ffffffe000122194: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f9b0)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffffffff8111f9b0-ffffffff8111f9f4: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111440)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffffffff81111440-ffffffff81111484: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d8a0)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffffffff8111d8a0-ffffffff8111d8e4: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_iw_handler(struct irq_work *iwp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127a60)
Location: kernel/rcu/tree_stall.h:147
Inline: False
```
**Symbols:**

```
ffffffff81127a60-ffffffff81127aad: rcu_iw_handler (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
