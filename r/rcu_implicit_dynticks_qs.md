# Function: <code>rcu_implicit_dynticks_qs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp, bool *isidle, long unsigned int *maxj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4d30)
Location: kernel/rcu/tree.c:1089
Inline: True
```
**Symbols:**

```
ffffffff810e4d30-ffffffff810e4e98: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp, bool *isidle, long unsigned int *maxj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb130)
Location: kernel/rcu/tree.c:1143
Inline: True
```
**Symbols:**

```
ffffffff810eb130-ffffffff810eb292: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp, bool *isidle, long unsigned int *maxj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2ba0)
Location: kernel/rcu/tree.c:1144
Inline: True
```
**Symbols:**

```
ffffffff810f2ba0-ffffffff810f2d02: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f3a80)
Location: kernel/rcu/tree.c:1228
Inline: True
```
**Symbols:**

```
ffffffff810f3a80-ffffffff810f3c48: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fcc10)
Location: kernel/rcu/tree.c:1298
Inline: False
```
**Symbols:**

```
ffffffff810fcc10-ffffffff810fce9f: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81104d50)
Location: kernel/rcu/tree.c:1174
Inline: False
```
**Symbols:**

```
ffffffff81104d50-ffffffff81104ff9: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1051
Inline: False
```
**Symbols:**

```
ffffffff81110560-ffffffff81110794: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff811144e1-ffffffff8111456b: rcu_implicit_dynticks_qs.cold.71 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:992
Inline: False
```
**Symbols:**

```
ffffffff81119c80-ffffffff81119e71: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff8111e4c3-ffffffff8111e593: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
ffffffff81126010-ffffffff81126282: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff8112aa84-ffffffff8112ab13: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1195
Inline: False
```
**Symbols:**

```
ffffffff81134e90-ffffffff811350e2: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81138feb-ffffffff8113907c: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1262
Inline: False
```
**Symbols:**

```
ffffffff8112f010-ffffffff8112f1ec: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81be2446-ffffffff81be250f: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1266
Inline: False
```
**Symbols:**

```
ffffffff8112f570-ffffffff8112f74c: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81bd43e5-ffffffff81bd44ae: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1219
Inline: False
```
**Symbols:**

```
ffffffff81150d20-ffffffff81150f60: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81cae6d4-ffffffff81cae7d2: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81178d00-ffffffff81178f0d: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81e5ed79-ffffffff81e5ee61: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:816
Inline: False
```
**Symbols:**

```
ffffffff811b16f0-ffffffff811b1a09: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff82059faf-ffffffff82059fd9: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:758
Inline: False
```
**Symbols:**

```
ffffffff811c3380-ffffffff811c3827: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff820d87b5-ffffffff820d87df: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:767
Inline: False
```
**Symbols:**

```
ffffffff811d9620-ffffffff811d9b71: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff821b3cdd-ffffffff821b3d1c: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
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
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018caa0)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
ffff80001018caa0-ffff80001018cd70: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dab10)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
c03dab10-c03dadfc: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e7150)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
c0000000001e7150-c0000000001e74e0: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120a36)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
ffffffe000120a36-ffffffe000120cc6: rcu_implicit_dynticks_qs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
ffffffff8111e5f0-ffffffff8111e862: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81123064-ffffffff811230f3: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
ffffffff8110fe10-ffffffff811100da: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81115ba6-ffffffff81115c35: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
ffffffff8111c4e0-ffffffff8111c752: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff81120f54-ffffffff81120fe3: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rcu_implicit_dynticks_qs(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:1000
Inline: False
```
**Symbols:**

```
ffffffff81127d90-ffffffff81128002: rcu_implicit_dynticks_qs (STB_LOCAL)
ffffffff8112d2a7-ffffffff8112d336: rcu_implicit_dynticks_qs.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool *isidle</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *maxj</code>
</li>
</ul>
</details>
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
