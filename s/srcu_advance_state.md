# Function: <code>srcu_advance_state</code>

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
In kernel/rcu/srcutree.c (ffffffff810f197c)
Location: kernel/rcu/srcutree.c:1066
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff810fb6ec)
Location: kernel/rcu/srcutree.c:1067
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff81103b7e)
Location: kernel/rcu/srcutree.c:1097
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff8110f53e)
Location: kernel/rcu/srcutree.c:1115
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff8111928e)
Location: kernel/rcu/srcutree.c:1090
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff8112565e)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811331e0)
Location: kernel/rcu/srcutree.c:1104
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff811331e0-ffffffff81133395: srcu_advance_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e9c0)
Location: kernel/rcu/srcutree.c:1093
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff8112e9c0-ffffffff8112eb75: srcu_advance_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112eff0)
Location: kernel/rcu/srcutree.c:1178
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff8112eff0-ffffffff8112f1a5: srcu_advance_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81150580)
Location: kernel/rcu/srcutree.c:1173
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff81150580-ffffffff81150735: srcu_advance_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81177aa0)
Location: kernel/rcu/srcutree.c:1466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff81177aa0-ffffffff81177c3c: srcu_advance_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811af130)
Location: kernel/rcu/srcutree.c:1535
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff811af130-ffffffff811af2cc: srcu_advance_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c1190)
Location: kernel/rcu/srcutree.c:1611
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff811c1190-ffffffff811c133c: srcu_advance_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void srcu_advance_state(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d1690)
Location: kernel/rcu/srcutree.c:1631
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff811d1690-ffffffff811d183c: srcu_advance_state (STB_LOCAL)
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
In kernel/rcu/srcutree.c (ffff80001018a9cc)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d9a30)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (c0000000001e5adc)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffe00011fd18)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff8111dc3e)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff8110ecce)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff8111bb2e)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
In kernel/rcu/srcutree.c (ffffffff81126cee)
Location: kernel/rcu/srcutree.c:1091
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
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
