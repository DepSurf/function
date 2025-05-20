# Function: <code>srcutorture_get_gp_data</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *sp, int *flags, long unsigned int *gpnum, long unsigned int *completed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f0c90)
Location: kernel/rcu/srcutree.c:1217
Inline: True
```
**Symbols:**

```
ffffffff810f0c90-ffffffff810f0cc4: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *sp, int *flags, long unsigned int *gpnum, long unsigned int *completed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810faa50)
Location: kernel/rcu/srcutree.c:1217
Inline: True
```
**Symbols:**

```
ffffffff810faa50-ffffffff810faa84: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *sp, int *flags, long unsigned int *gpnum, long unsigned int *completed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81102ee0)
Location: kernel/rcu/srcutree.c:1247
Inline: True
```
**Symbols:**

```
ffffffff81102ee0-ffffffff81102f12: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e7a0)
Location: kernel/rcu/srcutree.c:1265
Inline: False
```
**Symbols:**

```
ffffffff8110e7a0-ffffffff8110e7c0: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81117e40)
Location: kernel/rcu/srcutree.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81117e40-ffffffff81117e60: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124200)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
ffffffff81124200-ffffffff81124220: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81131a90)
Location: kernel/rcu/srcutree.c:1257
Inline: False
```
**Symbols:**

```
ffffffff81131a90-ffffffff81131ab0: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d270)
Location: kernel/rcu/srcutree.c:1246
Inline: False
```
**Symbols:**

```
ffffffff8112d270-ffffffff8112d290: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d870)
Location: kernel/rcu/srcutree.c:1334
Inline: False
```
**Symbols:**

```
ffffffff8112d870-ffffffff8112d890: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114ea60)
Location: kernel/rcu/srcutree.c:1329
Inline: False
```
**Symbols:**

```
ffffffff8114ea60-ffffffff8114ea80: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81175720)
Location: kernel/rcu/srcutree.c:1640
Inline: False
```
**Symbols:**

```
ffffffff81175720-ffffffff8117574e: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ac8a0)
Location: kernel/rcu/srcutree.c:1709
Inline: False
```
**Symbols:**

```
ffffffff811ac8a0-ffffffff811ac8ce: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811be700)
Location: kernel/rcu/srcutree.c:1787
Inline: False
```
**Symbols:**

```
ffffffff811be700-ffffffff811be72f: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811cec20)
Location: kernel/rcu/srcutree.c:1813
Inline: False
```
**Symbols:**

```
ffffffff811cec20-ffffffff811cec4f: srcutorture_get_gp_data (STB_GLOBAL)
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
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff800010189750)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
ffff800010189750-ffff80001018979c: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d7f98)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
c03d7f98-c03d7fc4: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e3ad0)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
c0000000001e3ad0-c0000000001e3af4: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011e912)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
ffffffe00011e912-ffffffe00011e956: srcutorture_get_gp_data (STB_GLOBAL)
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
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111c7e0)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
ffffffff8111c7e0-ffffffff8111c800: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110d8a0)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
ffffffff8110d8a0-ffffffff8110d8c0: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111a6d0)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
ffffffff8111a6d0-ffffffff8111a6f0: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void srcutorture_get_gp_data(enum rcutorture_type test_type, struct srcu_struct *ssp, int *flags, long unsigned int *gp_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125e60)
Location: kernel/rcu/srcutree.c:1242
Inline: False
```
**Symbols:**

```
ffffffff81125e60-ffffffff81125e80: srcutorture_get_gp_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>long unsigned int *gp_seq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *gpnum</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *completed</code>
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
