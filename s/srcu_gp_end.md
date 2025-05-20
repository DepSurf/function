# Function: <code>srcu_gp_end</code>

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
In kernel/rcu/srcutree.c (ffffffff810f1a3a)
Location: kernel/rcu/srcutree.c:498
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
In kernel/rcu/srcutree.c (ffffffff810fb7aa)
Location: kernel/rcu/srcutree.c:499
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
In kernel/rcu/srcutree.c (ffffffff81103cba)
Location: kernel/rcu/srcutree.c:529
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
In kernel/rcu/srcutree.c (ffffffff8110f67a)
Location: kernel/rcu/srcutree.c:537
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
In kernel/rcu/srcutree.c (ffffffff811193cd)
Location: kernel/rcu/srcutree.c:512
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
In kernel/rcu/srcutree.c (ffffffff8112579d)
Location: kernel/rcu/srcutree.c:512
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
void srcu_gp_end(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132cc0)
Location: kernel/rcu/srcutree.c:525
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff81132cc0-ffffffff81133057: srcu_gp_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_gp_end(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e4a0)
Location: kernel/rcu/srcutree.c:514
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff8112e4a0-ffffffff8112e837: srcu_gp_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_gp_end(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112ec50)
Location: kernel/rcu/srcutree.c:517
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff8112ec50-ffffffff8112efe7: srcu_gp_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void srcu_gp_end(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:509
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff81150140-ffffffff81150579: srcu_gp_end (STB_LOCAL)
ffffffff81cae2d7-ffffffff81cae2f6: srcu_gp_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:740
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff811775e0-ffffffff81177a97: srcu_gp_end.constprop.0 (STB_LOCAL)
ffffffff81e5e924-ffffffff81e5e943: srcu_gp_end.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:803
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff811aec20-ffffffff811af114: srcu_gp_end.constprop.0 (STB_LOCAL)
ffffffff82059f30-ffffffff82059f4f: srcu_gp_end.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void srcu_gp_end(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:851
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff811c0c20-ffffffff811c1175: srcu_gp_end (STB_LOCAL)
ffffffff820d873c-ffffffff820d8755: srcu_gp_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void srcu_gp_end(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:842
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_advance_state
```
**Symbols:**

```
ffffffff811d1130-ffffffff811d167d: srcu_gp_end (STB_LOCAL)
ffffffff821b39f2-ffffffff821b3a0b: srcu_gp_end.cold (STB_LOCAL)
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
In kernel/rcu/srcutree.c (ffff80001018ab3c)
Location: kernel/rcu/srcutree.c:512
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcu_gp_end(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d9610)
Location: kernel/rcu/srcutree.c:512
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
c03d9610-c03d9a10: srcu_gp_end (STB_LOCAL)
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
In kernel/rcu/srcutree.c (c0000000001e5d2c)
Location: kernel/rcu/srcutree.c:512
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
In kernel/rcu/srcutree.c (ffffffe00011fe9e)
Location: kernel/rcu/srcutree.c:512
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
In kernel/rcu/srcutree.c (ffffffff8111dd7d)
Location: kernel/rcu/srcutree.c:512
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
In kernel/rcu/srcutree.c (ffffffff8110ee01)
Location: kernel/rcu/srcutree.c:512
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
In kernel/rcu/srcutree.c (ffffffff8111bc6d)
Location: kernel/rcu/srcutree.c:512
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
In kernel/rcu/srcutree.c (ffffffff81126df7)
Location: kernel/rcu/srcutree.c:512
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
