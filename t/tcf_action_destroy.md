# Function: <code>tcf_action_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcf_action_destroy(struct list_head *actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81747b90)
Location: net/sched/act_api.c:429
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff81747b90-ffffffff81747c4f: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcf_action_destroy(struct list_head *actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b4d60)
Location: net/sched/act_api.c:448
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff817b4d60-ffffffff817b4de7: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcf_action_destroy(struct list_head *actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e4620)
Location: net/sched/act_api.c:456
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff817e4620-ffffffff817e46a7: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcf_action_destroy(struct list_head *actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81804010)
Location: net/sched/act_api.c:507
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff81804010-ffffffff81804097: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcf_action_destroy(struct list_head *actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81882d20)
Location: net/sched/act_api.c:521
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff81882d20-ffffffff81882da2: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_action_destroy(struct list_head *actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d66d0)
Location: net/sched/act_api.c:541
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff818d66d0-ffffffff818d6752: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819029e0)
Location: net/sched/act_api.c:668
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff819029e0-ffffffff81902a62: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81963c40)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff81963c40-ffffffff81963cbe: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199a7c0)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff8199a7c0-ffffffff8199a83e: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a73a20)
Location: net/sched/act_api.c:715
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff81a73a20-ffffffff81a73a96: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7c620)
Location: net/sched/act_api.c:756
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81a7c620-ffffffff81a7c696: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a652b0)
Location: net/sched/act_api.c:769
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81a652b0-ffffffff81a65326: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1e570)
Location: net/sched/act_api.c:778
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81b1e570-ffffffff81b1e5e6: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca5f80)
Location: net/sched/act_api.c:1094
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ca5f80-ffffffff81ca5ffe: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e62420)
Location: net/sched/act_api.c:1120
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81e62420-ffffffff81e6249e: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebe4b0)
Location: net/sched/act_api.c:1115
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ebe4b0-ffffffff81ebe52e: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f81600)
Location: net/sched/act_api.c:1137
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81f81600-ffffffff81f8167e: tcf_action_destroy (STB_GLOBAL)
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
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c479e8)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffff800010c479e8-ffff800010c47a84: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d58ab4)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
c0d58ab4-c0d58b3c: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d44990)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
c000000000d44990-c000000000d44a74: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b56a2)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffe0007b56a2-ffffffe0007b5722: tcf_action_destroy (STB_GLOBAL)
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
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193a630)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff8193a630-ffffffff8193a6ae: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f4130)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff818f4130-ffffffff818f41ae: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198b7c0)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff8198b7c0-ffffffff8198b83e: tcf_action_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_action_destroy(struct tc_action **actions, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ae030)
Location: net/sched/act_api.c:699
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
**Symbols:**

```
ffffffff819ae030-ffffffff819ae0ae: tcf_action_destroy (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>struct list_head *actions</code> ➡️ <code>struct tc_action **actions</code>
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
