# Function: <code>notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a13c0)
Location: kernel/notifier.c:74
Inline: False
Direct callers:
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__blocking_notifier_call_chain
  - kernel/notifier.c:__srcu_notifier_call_chain
```
**Symbols:**

```
ffffffff810a13c0-ffffffff810a142a: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4ae0)
Location: kernel/notifier.c:74
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:__blocking_notifier_call_chain
```
**Symbols:**

```
ffffffff810a4ae0-ffffffff810a4b4a: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa740)
Location: kernel/notifier.c:74
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:__blocking_notifier_call_chain
```
**Symbols:**

```
ffffffff810aa740-ffffffff810aa7aa: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a72c0)
Location: kernel/notifier.c:74
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810a72c0-ffffffff810a732a: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ada40)
Location: kernel/notifier.c:74
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810ada40-ffffffff810adaac: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b48b0)
Location: kernel/notifier.c:74
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810b48b0-ffffffff810b491c: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bda00)
Location: kernel/notifier.c:74
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810bda00-ffffffff810bda6c: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3a50)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810c3a50-ffffffff810c3ac7: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccb60)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810ccb60-ffffffff810ccbd7: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6e90)
Location: kernel/notifier.c:64
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:raw_notifier_call_chain
Direct callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
**Symbols:**

```
ffffffff810d6720-ffffffff810d678c: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1930)
Location: kernel/notifier.c:64
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:atomic_notifier_call_chain_robust
  - kernel/notifier.c:atomic_notifier_call_chain_robust
```
**Symbols:**

```
ffffffff810d12f0-ffffffff810d135c: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3510)
Location: kernel/notifier.c:64
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:atomic_notifier_call_chain_robust
  - kernel/notifier.c:atomic_notifier_call_chain_robust
```
**Symbols:**

```
ffffffff810d2ed0-ffffffff810d2f3c: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e66a0)
Location: kernel/notifier.c:64
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:raw_notifier_call_chain_robust
```
**Symbols:**

```
ffffffff810e6010-ffffffff810e607c: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100738)
Location: kernel/notifier.c:68
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:raw_notifier_call_chain_robust
```
**Symbols:**

```
ffffffff810ffe80-ffffffff810ffefb: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125678)
Location: kernel/notifier.c:68
Inline: True
Inline callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:raw_notifier_call_chain_robust
```
**Symbols:**

```
ffffffff81124cc0-ffffffff81124d3b: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132720)
Location: kernel/notifier.c:73
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:raw_notifier_call_chain_robust
```
**Symbols:**

```
ffffffff81132720-ffffffff811327f9: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d630)
Location: kernel/notifier.c:73
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain_robust
  - kernel/notifier.c:raw_notifier_call_chain_robust
```
**Symbols:**

```
ffffffff8113d630-ffffffff8113d709: notifier_call_chain (STB_LOCAL)
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
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012b898)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffff80001012b898-ffff80001012b934: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037bd7c)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
c037bd7c-c037be10: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174430)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
c000000000174430-c000000000174530: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e05e2)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffe0000e05e2-ffffffe0000e065a: notifier_call_chain (STB_LOCAL)
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
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6ee0)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810c6ee0-ffffffff810c6f57: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5700)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810b5700-ffffffff810b5777: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6430)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:notify_die
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810c6430-ffffffff810c64a7: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int notifier_call_chain(struct notifier_block **nl, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ce880)
Location: kernel/notifier.c:76
Inline: False
Direct callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/notifier.c:raw_notifier_call_chain
  - kernel/notifier.c:atomic_notifier_call_chain
```
**Symbols:**

```
ffffffff810ce880-ffffffff810ce8f7: notifier_call_chain (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
