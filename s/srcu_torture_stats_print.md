# Function: <code>srcu_torture_stats_print</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *sp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fa880)
Location: kernel/rcu/srcutree.c:1229
Inline: False
```
**Symbols:**

```
ffffffff810fa880-ffffffff810fa96e: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *sp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110455c)
Location: kernel/rcu/srcutree.c:1259
Inline: False
```
**Symbols:**

```
ffffffff8110455c-ffffffff81104644: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110ffac)
Location: kernel/rcu/srcutree.c:1276
Inline: False
```
**Symbols:**

```
ffffffff8110ffac-ffffffff811100a3: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811196fe)
Location: kernel/rcu/srcutree.c:1252
Inline: False
```
**Symbols:**

```
ffffffff811196fe-ffffffff811197f8: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125ace)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
ffffffff81125ace-ffffffff81125bd9: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811333dd)
Location: kernel/rcu/srcutree.c:1268
Inline: False
```
**Symbols:**

```
ffffffff811333dd-ffffffff811334eb: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81be1f28)
Location: kernel/rcu/srcutree.c:1257
Inline: False
```
**Symbols:**

```
ffffffff81be1f28-ffffffff81be2036: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81bd3fb8)
Location: kernel/rcu/srcutree.c:1345
Inline: False
```
**Symbols:**

```
ffffffff81bd3fb8-ffffffff81bd40c6: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81cae129)
Location: kernel/rcu/srcutree.c:1340
Inline: False
```
**Symbols:**

```
ffffffff81cae129-ffffffff81cae264: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:1664
Inline: False
```
**Symbols:**

```
ffffffff81e5e72c-ffffffff81e5e89d: srcu_torture_stats_print.cold (STB_LOCAL)
ffffffff81175a10-ffffffff81175a98: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ad730)
Location: kernel/rcu/srcutree.c:1733
Inline: False
```
**Symbols:**

```
ffffffff811ad730-ffffffff811ad96c: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811bf460)
Location: kernel/rcu/srcutree.c:1811
Inline: False
```
**Symbols:**

```
ffffffff811bf460-ffffffff811bf6a5: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811cf8d0)
Location: kernel/rcu/srcutree.c:1837
Inline: False
```
**Symbols:**

```
ffffffff811cf8d0-ffffffff811cfb15: srcu_torture_stats_print (STB_GLOBAL)
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
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018baac)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
ffff80001018baac-ffff80001018bbe0: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d9bc4)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
c03d9bc4-c03d9cd8: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e620c)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
c0000000001e620c-c0000000001e637c: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe000120214)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
ffffffe000120214-ffffffe000120334: srcu_torture_stats_print (STB_GLOBAL)
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
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111e0ae)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
ffffffff8111e0ae-ffffffff8111e1b9: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110f11a)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
ffffffff8110f11a-ffffffff8110f225: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111bf9e)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
ffffffff8111bf9e-ffffffff8111c0a9: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void srcu_torture_stats_print(struct srcu_struct *ssp, char *tt, char *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811276cc)
Location: kernel/rcu/srcutree.c:1253
Inline: False
```
**Symbols:**

```
ffffffff811276cc-ffffffff811277d7: srcu_torture_stats_print (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
