# Function: <code>rcu_softirq_qs</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811131e0)
Location: kernel/rcu/tree.c:223
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff811131e0-ffffffff81113212: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111cd80)
Location: kernel/rcu/tree.c:218
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff8111cd80-ffffffff8111cd90: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129260)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81129260-ffffffff81129270: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137c50)
Location: kernel/rcu/tree.c:230
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81137c50-ffffffff81137ca9: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811334b0)
Location: kernel/rcu/tree.c:235
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff811334b0-ffffffff81133509: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133fd0)
Location: kernel/rcu/tree.c:241
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81133fd0-ffffffff81134029: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:247
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81caf5c5-ffffffff81caf5d9: rcu_softirq_qs.cold (STB_LOCAL)
ffffffff81156550-ffffffff811565ef: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:258
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81e60269-ffffffff81e6027d: rcu_softirq_qs.cold (STB_LOCAL)
ffffffff8117f500-ffffffff8117f5d2: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b97d0)
Location: kernel/rcu/tree.c:261
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff811b97d0-ffffffff811b98b5: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cc0e0)
Location: kernel/rcu/tree.c:242
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff811cc0e0-ffffffff811cc1c5: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811e0c50)
Location: kernel/rcu/tree.c:243
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff811e0c50-ffffffff811e0d35: rcu_softirq_qs (STB_GLOBAL)
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
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff8000101907e0)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffff8000101907e0-ffff8000101907fc: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03de348)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
c03de348-c03de364: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ebaf0)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
c0000000001ebaf0-c0000000001ebb20: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000123e14)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffe000123e14-ffffffe000123e36: rcu_softirq_qs (STB_GLOBAL)
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
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81121840)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81121840-ffffffff81121850: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113f20)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81113f20-ffffffff81113f30: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f730)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff8111f730-ffffffff8111f740: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_softirq_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112b860)
Location: kernel/rcu/tree.c:219
Inline: False
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff8112b860-ffffffff8112b88b: rcu_softirq_qs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
