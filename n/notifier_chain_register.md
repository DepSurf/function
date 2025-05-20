# Function: <code>notifier_chain_register</code>

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
In kernel/notifier.c (ffffffff810a144f)
Location: kernel/notifier.c:21
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
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
In kernel/notifier.c (ffffffff810a4bfc)
Location: kernel/notifier.c:21
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
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
In kernel/notifier.c (ffffffff810aa85c)
Location: kernel/notifier.c:21
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
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
In kernel/notifier.c (ffffffff810a73dc)
Location: kernel/notifier.c:21
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
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
In kernel/notifier.c (ffffffff810adb5c)
Location: kernel/notifier.c:21
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
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
In kernel/notifier.c (ffffffff810b49c5)
Location: kernel/notifier.c:21
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
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
In kernel/notifier.c (ffffffff810bdb15)
Location: kernel/notifier.c:21
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3bf0)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffffffff810c3bf0-ffffffff810c3c64: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccd00)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffffffff810ccd00-ffffffff810ccd74: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6930)
Location: kernel/notifier.c:22
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
```
**Symbols:**

```
ffffffff810d6930-ffffffff810d6979: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1430)
Location: kernel/notifier.c:22
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
```
**Symbols:**

```
ffffffff810d1430-ffffffff810d1479: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3010)
Location: kernel/notifier.c:22
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
```
**Symbols:**

```
ffffffff810d3010-ffffffff810d3059: notifier_chain_register (STB_LOCAL)
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
In kernel/notifier.c (ffffffff810e6475)
Location: kernel/notifier.c:22
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n, bool unique_priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100685)
Location: kernel/notifier.c:22
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register_unique_prio
  - kernel/notifier.c:atomic_notifier_chain_register_unique_prio
Direct callers:
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
```
**Symbols:**

```
ffffffff811001b0-ffffffff8110022f: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n, bool unique_priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811255b5)
Location: kernel/notifier.c:22
Inline: True
Inline callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register_unique_prio
  - kernel/notifier.c:atomic_notifier_chain_register_unique_prio
Direct callers:
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
```
**Symbols:**

```
ffffffff81125050-ffffffff811250cf: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n, bool unique_priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132410)
Location: kernel/notifier.c:25
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register_unique_prio
```
**Symbols:**

```
ffffffff81132410-ffffffff811324db: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n, bool unique_priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d320)
Location: kernel/notifier.c:25
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register_unique_prio
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register_unique_prio
```
**Symbols:**

```
ffffffff8113d320-ffffffff8113d3eb: notifier_chain_register (STB_LOCAL)
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
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bb80)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffff80001012bb80-ffff80001012bc28: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037bfc0)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
c037bfc0-c037c070: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c0000000001746d0)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
c0000000001746d0-c0000000001747b8: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e07c8)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffffffe0000e07c8-ffffffe0000e084e: notifier_chain_register (STB_LOCAL)
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
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7080)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffffffff810c7080-ffffffff810c70f4: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b58a0)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffffffff810b58a0-ffffffff810b5914: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c65d0)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffffffff810c65d0-ffffffff810c6644: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int notifier_chain_register(struct notifier_block **nl, struct notifier_block *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ce980)
Location: kernel/notifier.c:22
Inline: False
Direct callers:
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:srcu_notifier_chain_register
  - kernel/notifier.c:raw_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:blocking_notifier_chain_register
  - kernel/notifier.c:atomic_notifier_chain_register
```
**Symbols:**

```
ffffffff810ce980-ffffffff810ce9f4: notifier_chain_register (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
