# Function: <code>synchronize_srcu_expedited</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e4120)
Location: kernel/rcu/srcu.c:508
Inline: False
```
**Symbols:**

```
ffffffff810e4120-ffffffff810e4135: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810ea430)
Location: kernel/rcu/srcu.c:508
Inline: False
```
**Symbols:**

```
ffffffff810ea430-ffffffff810ea445: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f1310)
Location: kernel/rcu/srcu.c:508
Inline: False
```
**Symbols:**

```
ffffffff810f1310-ffffffff810f1325: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f2210)
Location: kernel/rcu/srcutree.c:920
Inline: False
```
**Symbols:**

```
ffffffff810f2210-ffffffff810f223a: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fbf80)
Location: kernel/rcu/srcutree.c:921
Inline: False
```
**Symbols:**

```
ffffffff810fbf80-ffffffff810fbfaa: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81104450)
Location: kernel/rcu/srcutree.c:951
Inline: False
```
**Symbols:**

```
ffffffff81104450-ffffffff8110447a: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110fea0)
Location: kernel/rcu/srcutree.c:969
Inline: False
```
**Symbols:**

```
ffffffff8110fea0-ffffffff8110feca: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118d60)
Location: kernel/rcu/srcutree.c:944
Inline: False
```
**Symbols:**

```
ffffffff81118d60-ffffffff81118d8c: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125130)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
ffffffff81125130-ffffffff8112515c: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132b80)
Location: kernel/rcu/srcutree.c:958
Inline: True
```
**Symbols:**

```
ffffffff81132b80-ffffffff81132bae: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e360)
Location: kernel/rcu/srcutree.c:947
Inline: True
```
**Symbols:**

```
ffffffff8112e360-ffffffff8112e38e: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e8e0)
Location: kernel/rcu/srcutree.c:961
Inline: True
```
**Symbols:**

```
ffffffff8112e8e0-ffffffff8112e90e: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114fdc0)
Location: kernel/rcu/srcutree.c:953
Inline: True
```
**Symbols:**

```
ffffffff8114fdc0-ffffffff8114fdee: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811770f0)
Location: kernel/rcu/srcutree.c:1238
Inline: True
```
**Symbols:**

```
ffffffff811770f0-ffffffff8117711d: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae6c0)
Location: kernel/rcu/srcutree.c:1307
Inline: True
```
**Symbols:**

```
ffffffff811ae6c0-ffffffff811ae6ed: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c06a0)
Location: kernel/rcu/srcutree.c:1383
Inline: True
```
**Symbols:**

```
ffffffff811c06a0-ffffffff811c06cd: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0b80)
Location: kernel/rcu/srcutree.c:1403
Inline: True
```
**Symbols:**

```
ffffffff811d0b80-ffffffff811d0bad: synchronize_srcu_expedited (STB_GLOBAL)
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
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018b758)
Location: kernel/rcu/srcutree.c:945
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_io_bus_unregister_dev
  - virt/kvm/kvm_main.c:kvm_io_bus_register_dev
  - virt/kvm/irqchip.c:kvm_set_irq_routing
```
**Symbols:**

```
ffff80001018b758-ffff80001018b798: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d94ec)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
c03d94ec-c03d952c: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e51d0)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
c0000000001e51d0-c0000000001e524c: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011fa02)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
ffffffe00011fa02-ffffffe00011fa40: synchronize_srcu_expedited (STB_GLOBAL)
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
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d710)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
ffffffff8111d710-ffffffff8111d73c: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e7c0)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
ffffffff8110e7c0-ffffffff8110e7ec: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b600)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
ffffffff8111b600-ffffffff8111b62c: synchronize_srcu_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void synchronize_srcu_expedited(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811275c0)
Location: kernel/rcu/srcutree.c:945
Inline: False
```
**Symbols:**

```
ffffffff811275c0-ffffffff811275ec: synchronize_srcu_expedited (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
</ul>
</details>
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
