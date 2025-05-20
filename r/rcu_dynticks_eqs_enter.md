# Function: <code>rcu_dynticks_eqs_enter</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5e39)
Location: kernel/rcu/tree.c:293
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff810ffcd9)
Location: kernel/rcu/tree.c:290
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff81107e6f)
Location: kernel/rcu/tree.c:277
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff811133ab)
Location: kernel/rcu/tree.c:233
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff8111cffb)
Location: kernel/rcu/tree.c:228
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff811294f7)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bbf850)
Location: kernel/rcu/tree.c:242
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
```
**Symbols:**

```
ffffffff81bbf850-ffffffff81bbf86d: rcu_dynticks_eqs_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c38630)
Location: kernel/rcu/tree.c:247
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
```
**Symbols:**

```
ffffffff81c38630-ffffffff81c3864d: rcu_dynticks_eqs_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c2aa40)
Location: kernel/rcu/tree.c:253
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
```
**Symbols:**

```
ffffffff81c2aa40-ffffffff81c2aa5d: rcu_dynticks_eqs_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81d49020)
Location: kernel/rcu/tree.c:269
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
```
**Symbols:**

```
ffffffff81d49020-ffffffff81d49030: rcu_dynticks_eqs_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81f183f0)
Location: kernel/rcu/tree.c:280
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
```
**Symbols:**

```
ffffffff81f183f0-ffffffff81f18408: rcu_dynticks_eqs_enter (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018c5f0)
Location: kernel/rcu/tree.c:229
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
ffff80001018c5f0-ffff80001018c640: rcu_dynticks_eqs_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_dynticks_eqs_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03d9cfc)
Location: kernel/rcu/tree.c:229
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
**Symbols:**

```
c03d9cfc-c03d9d48: rcu_dynticks_eqs_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ebe9c)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000123ffa)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
</details>
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
In kernel/rcu/tree.c (ffffffff81121ad7)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114147)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f9c7)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
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
In kernel/rcu/tree.c (ffffffff8112bb37)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_idle_enter
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
