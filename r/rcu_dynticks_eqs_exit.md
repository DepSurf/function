# Function: <code>rcu_dynticks_eqs_exit</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2310)
Location: kernel/rcu/tree.c:316
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff810f2310-ffffffff810f233e: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc090)
Location: kernel/rcu/tree.c:313
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff810fc090-ffffffff810fc0be: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104670)
Location: kernel/rcu/tree.c:300
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81104670-ffffffff8110469e: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811100f0)
Location: kernel/rcu/tree.c:256
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff811100f0-ffffffff81110124: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811198a0)
Location: kernel/rcu/tree.c:251
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff811198a0-ffffffff811198d4: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81125c30)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81125c30-ffffffff81125c64: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bbf870)
Location: kernel/rcu/tree.c:267
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81bbf870-ffffffff81bbf89a: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c38650)
Location: kernel/rcu/tree.c:272
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81c38650-ffffffff81c3867a: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c2aa60)
Location: kernel/rcu/tree.c:278
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81c2aa60-ffffffff81c2aa8a: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:289
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81d49020-ffffffff81d49030: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:300
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81f183f0-ffffffff81f18408: rcu_dynticks_eqs_exit (STB_LOCAL)
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
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018c6a8)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffff80001018c6a8-ffff80001018c72c: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03d9d48)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
c03d9d48-c03d9db8: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e63a0)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
c0000000001e63a0-c0000000001e6404: rcu_dynticks_eqs_exit (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffe000124160)
Location: kernel/rcu/tree.c:252
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_idle_exit
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
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e210)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff8111e210-ffffffff8111e244: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f270)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff8110f270-ffffffff8110f2a4: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c100)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff8111c100-ffffffff8111c134: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_dynticks_eqs_exit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127830)
Location: kernel/rcu/tree.c:252
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
**Symbols:**

```
ffffffff81127830-ffffffff81127864: rcu_dynticks_eqs_exit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
