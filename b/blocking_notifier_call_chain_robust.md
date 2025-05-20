# Function: <code>blocking_notifier_call_chain_robust</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain_robust(struct blocking_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1c70)
Location: kernel/notifier.c:290
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810d1c70-ffffffff810d1d44: blocking_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain_robust(struct blocking_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3850)
Location: kernel/notifier.c:290
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810d3850-ffffffff810d3924: blocking_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain_robust(struct blocking_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e69d0)
Location: kernel/notifier.c:271
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810e69d0-ffffffff810e6aa4: blocking_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain_robust(struct blocking_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811009d0)
Location: kernel/notifier.c:335
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811009d0-ffffffff81100aa7: blocking_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain_robust(struct blocking_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125950)
Location: kernel/notifier.c:335
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff81125950-ffffffff81125a27: blocking_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain_robust(struct blocking_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132810)
Location: kernel/notifier.c:341
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff81132810-ffffffff811328d2: blocking_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int blocking_notifier_call_chain_robust(struct blocking_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d720)
Location: kernel/notifier.c:341
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff8113d720-ffffffff8113d7e2: blocking_notifier_call_chain_robust (STB_GLOBAL)
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
