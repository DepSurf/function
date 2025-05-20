# Function: <code>srcu_notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a19a0)
Location: kernel/notifier.c:421
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
```
**Symbols:**

```
ffffffff810a19a0-ffffffff810a1a42: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a50c0)
Location: kernel/notifier.c:421
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810a50c0-ffffffff810a5162: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aad20)
Location: kernel/notifier.c:421
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810aad20-ffffffff810aadc2: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7890)
Location: kernel/notifier.c:421
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810a7890-ffffffff810a7934: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ae010)
Location: kernel/notifier.c:421
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810ae010-ffffffff810ae0b4: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4e80)
Location: kernel/notifier.c:421
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810b4e80-ffffffff810b4f24: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdfd0)
Location: kernel/notifier.c:421
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810bdfd0-ffffffff810be074: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3e30)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810c3e30-ffffffff810c3e92: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccf40)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810ccf40-ffffffff810ccfa2: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6a40)
Location: kernel/notifier.c:388
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810d6a40-ffffffff810d6aa2: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1540)
Location: kernel/notifier.c:430
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810d1540-ffffffff810d15a2: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3120)
Location: kernel/notifier.c:430
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810d3120-ffffffff810d3182: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6840)
Location: kernel/notifier.c:411
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810e6840-ffffffff810e6904: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100ab0)
Location: kernel/notifier.c:475
Inline: True
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff81100ab0-ffffffff81100b91: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125a40)
Location: kernel/notifier.c:475
Inline: True
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff81125a40-ffffffff81125b21: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132670)
Location: kernel/notifier.c:480
Inline: True
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff81132670-ffffffff811326e2: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d580)
Location: kernel/notifier.c:480
Inline: True
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff8113d580-ffffffff8113d5f2: srcu_notifier_chain_register (STB_GLOBAL)
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
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bd68)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffff80001012bd68-ffff80001012bdf0: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c27c)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
c037c27c-c037c2ec: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174ad0)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
c000000000174ad0-c000000000174b70: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0a5c)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffe0000e0a5c-ffffffe0000e0ad8: srcu_notifier_chain_register (STB_GLOBAL)
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
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c72c0)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810c72c0-ffffffff810c7322: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5ae0)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810b5ae0-ffffffff810b5b42: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6810)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810c6810-ffffffff810c6872: srcu_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int srcu_notifier_chain_register(struct srcu_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cecd0)
Location: kernel/notifier.c:423
Inline: False
Direct callers:
  - fs/locks.c:lease_register_notifier
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/devfreq/devfreq.c:devm_devfreq_register_notifier
```
**Symbols:**

```
ffffffff810cecd0-ffffffff810ced32: srcu_notifier_chain_register (STB_GLOBAL)
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
