# Function: <code>refcount_dec_and_rtnl_lock</code>

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
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c8f60)
Location: net/core/rtnetlink.c:133
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff818c8f60-ffffffff818c8f77: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81915f30)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff81915f30-ffffffff81915f47: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81948560)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff81948560-ffffffff81948577: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a183a0)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff81a183a0-ffffffff81a183b7: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18470)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff81a18470-ffffffff81a18487: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ff340)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff819ff340-ffffffff819ff357: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab1530)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff81ab1530-ffffffff81ab1547: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2a6e0)
Location: net/core/rtnetlink.c:163
Inline: False
```
**Symbols:**

```
ffffffff81c2a6e0-ffffffff81c2a6ff: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ddd480)
Location: net/core/rtnetlink.c:164
Inline: False
```
**Symbols:**

```
ffffffff81ddd480-ffffffff81ddd49f: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4e1d0)
Location: net/core/rtnetlink.c:167
Inline: False
```
**Symbols:**

```
ffffffff81e4e1d0-ffffffff81e4e1ef: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0cf30)
Location: net/core/rtnetlink.c:168
Inline: False
```
**Symbols:**

```
ffffffff81f0cf30-ffffffff81f0cf4f: refcount_dec_and_rtnl_lock (STB_GLOBAL)
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
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bea130)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffff800010bea130-ffff800010bea168: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d02a90)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
c0d02a90-c0d02ab4: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccc580)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
c000000000ccc580-c000000000ccc5bc: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076d9e0)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffe00076d9e0-ffffffe00076da12: refcount_dec_and_rtnl_lock (STB_GLOBAL)
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
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e8530)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff818e8530-ffffffff818e8547: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a2370)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff818a2370-ffffffff818a2387: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81939560)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff81939560-ffffffff81939577: refcount_dec_and_rtnl_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool refcount_dec_and_rtnl_lock(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195ac40)
Location: net/core/rtnetlink.c:128
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_put_unlocked
```
**Symbols:**

```
ffffffff8195ac40-ffffffff8195ac57: refcount_dec_and_rtnl_lock (STB_GLOBAL)
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
