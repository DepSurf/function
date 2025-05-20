# Function: <code>qdisc_put_stab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817429f0)
Location: net/sched/sch_api.c:509
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff817429f0-ffffffff81742a62: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817af8a0)
Location: net/sched/sch_api.c:507
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff817af8a0-ffffffff817af912: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817def90)
Location: net/sched/sch_api.c:512
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff817def90-ffffffff817df002: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81801439)
Location: net/sched/sch_api.c:512
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff817fef40-ffffffff817fef7e: qdisc_put_stab.part.26 (STB_LOCAL)
ffffffff817fef80-ffffffff817fef9d: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187f172)
Location: net/sched/sch_api.c:507
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff8187cbd0-ffffffff8187cc0e: qdisc_put_stab.part.27 (STB_LOCAL)
ffffffff8187cc10-ffffffff8187cc2d: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818d1d3f)
Location: net/sched/sch_api.c:519
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff818cf440-ffffffff818cf47e: qdisc_put_stab.part.30 (STB_LOCAL)
ffffffff818cf480-ffffffff818cf49c: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fd0c3)
Location: net/sched/sch_api.c:534
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff818faa10-ffffffff818faa4e: qdisc_put_stab.part.33 (STB_LOCAL)
ffffffff818faa50-ffffffff818faa6c: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195ca6c)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff8195a2c0-ffffffff8195a2f7: qdisc_put_stab.part.0 (STB_LOCAL)
ffffffff8195a300-ffffffff8195a31c: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81992fbc)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81990760-ffffffff81990797: qdisc_put_stab.part.0 (STB_LOCAL)
ffffffff819907a0-ffffffff819907bc: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a69b77)
Location: net/sched/sch_api.c:528
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
```
**Symbols:**

```
ffffffff81a68030-ffffffff81a68073: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a71d87)
Location: net/sched/sch_api.c:530
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
```
**Symbols:**

```
ffffffff81a70740-ffffffff81a70783: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a5c10f)
Location: net/sched/sch_api.c:530
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
```
**Symbols:**

```
ffffffff81a59050-ffffffff81a59093: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b152bf)
Location: net/sched/sch_api.c:536
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
```
**Symbols:**

```
ffffffff81b121f0-ffffffff81b12233: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9c919)
Location: net/sched/sch_api.c:537
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
```
**Symbols:**

```
ffffffff81c994b0-ffffffff81c9950b: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e58ddd)
Location: net/sched/sch_api.c:539
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
```
**Symbols:**

```
ffffffff81e55740-ffffffff81e5579b: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb4522)
Location: net/sched/sch_api.c:540
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:__qdisc_destroy
```
**Symbols:**

```
ffffffff81eb0fd0-ffffffff81eb102c: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f771f2)
Location: net/sched/sch_api.c:540
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:__qdisc_destroy
```
**Symbols:**

```
ffffffff81f73a70-ffffffff81f73acc: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3f384)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffff800010c3c748-ffff800010c3c798: qdisc_put_stab.part.0 (STB_LOCAL)
ffff800010c3c798-ffff800010c3c7e4: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (c0d50e8c)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
c0d4e650-c0d4e690: qdisc_put_stab.part.0 (STB_LOCAL)
c0d4e690-c0d4e6c8: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (c000000000d399f0)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
c000000000d364e0-c000000000d36558: qdisc_put_stab.part.0 (STB_LOCAL)
c000000000d36560-c000000000d36590: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007af1d8)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffe0007acfb0-ffffffe0007acff0: qdisc_put_stab.part.0 (STB_LOCAL)
ffffffe0007acff0-ffffffe0007ad030: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81932e2c)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff819305d0-ffffffff81930607: qdisc_put_stab.part.0 (STB_LOCAL)
ffffffff81930610-ffffffff8193062c: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818ec92c)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff818ea0d0-ffffffff818ea107: qdisc_put_stab.part.0 (STB_LOCAL)
ffffffff818ea110-ffffffff818ea12c: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81983fbc)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81981760-ffffffff81981797: qdisc_put_stab.part.0 (STB_LOCAL)
ffffffff819817a0-ffffffff819817bc: qdisc_put_stab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void qdisc_put_stab(struct qdisc_size_table *tab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a64fc)
Location: net/sched/sch_api.c:526
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff819a3ce0-ffffffff819a3d17: qdisc_put_stab.part.0 (STB_LOCAL)
ffffffff819a3d20-ffffffff819a3d3c: qdisc_put_stab (STB_GLOBAL)
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
