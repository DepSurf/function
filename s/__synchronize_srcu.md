# Function: <code>__synchronize_srcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct *sp, int trycount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e3fb0)
Location: kernel/rcu/srcu.c:410
Inline: False
Direct callers:
  - kernel/rcu/srcu.c:synchronize_srcu
  - kernel/rcu/srcu.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff810e3fb0-ffffffff810e40e0: __synchronize_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct *sp, int trycount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810ea2b0)
Location: kernel/rcu/srcu.c:410
Inline: False
Direct callers:
  - kernel/rcu/srcu.c:synchronize_srcu_expedited
  - kernel/rcu/srcu.c:synchronize_srcu
  - kernel/rcu/srcu.c:synchronize_srcu
```
**Symbols:**

```
ffffffff810ea2b0-ffffffff810ea3e0: __synchronize_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct *sp, int trycount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f1190)
Location: kernel/rcu/srcu.c:410
Inline: False
Direct callers:
  - kernel/rcu/srcu.c:synchronize_srcu_expedited
  - kernel/rcu/srcu.c:synchronize_srcu
  - kernel/rcu/srcu.c:synchronize_srcu
```
**Symbols:**

```
ffffffff810f1190-ffffffff810f12c0: __synchronize_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f2222)
Location: kernel/rcu/srcutree.c:880
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff810f2160-ffffffff810f220b: __synchronize_srcu.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fbf92)
Location: kernel/rcu/srcutree.c:881
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff810fbed0-ffffffff810fbf7e: __synchronize_srcu.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81104462)
Location: kernel/rcu/srcutree.c:911
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff811043b0-ffffffff81104449: __synchronize_srcu.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110feb2)
Location: kernel/rcu/srcutree.c:929
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff8110fdf0-ffffffff8110fe95: __synchronize_srcu.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118d73)
Location: kernel/rcu/srcutree.c:904
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff81118cb0-ffffffff81118d55: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125143)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff81125080-ffffffff81125125: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132aa0)
Location: kernel/rcu/srcutree.c:918
Inline: True
```
**Symbols:**

```
ffffffff81132aa0-ffffffff81132b78: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e280)
Location: kernel/rcu/srcutree.c:907
Inline: True
```
**Symbols:**

```
ffffffff8112e280-ffffffff8112e358: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e7f0)
Location: kernel/rcu/srcutree.c:921
Inline: True
```
**Symbols:**

```
ffffffff8112e7f0-ffffffff8112e8d2: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114fcd0)
Location: kernel/rcu/srcutree.c:913
Inline: True
```
**Symbols:**

```
ffffffff8114fcd0-ffffffff8114fdb2: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct *ssp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81177020)
Location: kernel/rcu/srcutree.c:1198
Inline: False
```
**Symbols:**

```
ffffffff81177020-ffffffff811770e5: __synchronize_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct *ssp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae5e0)
Location: kernel/rcu/srcutree.c:1267
Inline: False
```
**Symbols:**

```
ffffffff811ae5e0-ffffffff811ae6a5: __synchronize_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct *ssp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c05c0)
Location: kernel/rcu/srcutree.c:1341
Inline: False
```
**Symbols:**

```
ffffffff811c05c0-ffffffff811c0685: __synchronize_srcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __synchronize_srcu(struct srcu_struct *ssp, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0aa0)
Location: kernel/rcu/srcutree.c:1361
Inline: False
```
**Symbols:**

```
ffffffff811d0aa0-ffffffff811d0b65: __synchronize_srcu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018b774)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffff80001018b6a0-ffff80001018b754: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (c03d9508)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
c03d9434-c03d94ec: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e5204)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
c0000000001e50f0-c0000000001e51c8: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011fa20)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffe00011f978-ffffffe00011fa02: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d723)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff8111d660-ffffffff8111d705: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e7d3)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff8110e710-ffffffff8110e7b5: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b613)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff8111b550-ffffffff8111b5f5: __synchronize_srcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811275d3)
Location: kernel/rcu/srcutree.c:905
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff81127520-ffffffff811275bc: __synchronize_srcu.part.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
