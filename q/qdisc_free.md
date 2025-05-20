# Function: <code>qdisc_free</code>

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
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187af90)
Location: net/sched/sch_generic.c:717
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff8187af90-ffffffff8187afca: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cd370)
Location: net/sched/sch_generic.c:934
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff818cd370-ffffffff818cd3a9: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f89d0)
Location: net/sched/sch_generic.c:945
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff818f89d0-ffffffff818f8a09: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819581a0)
Location: net/sched/sch_generic.c:937
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff819581a0-ffffffff819581d9: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198e650)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff8198e650-ffffffff8198e689: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a64a65)
Location: net/sched/sch_generic.c:937
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
Direct callers:
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81a663f0-ffffffff81a6642c: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6cbb2)
Location: net/sched/sch_generic.c:924
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
Direct callers:
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81a6e4c0-ffffffff81a6e503: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a55712)
Location: net/sched/sch_generic.c:968
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
Direct callers:
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81a56d50-ffffffff81a56d93: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0e292)
Location: net/sched/sch_generic.c:994
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
Direct callers:
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81b0fb80-ffffffff81b0fbc3: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c95cf2)
Location: net/sched/sch_generic.c:1036
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
```
**Symbols:**

```
ffffffff81c96d70-ffffffff81c96dbd: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e518b2)
Location: net/sched/sch_generic.c:1032
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
Direct callers:
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81e52b40-ffffffff81e52b8d: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81ead102)
Location: net/sched/sch_generic.c:1032
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
Direct callers:
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81eae3a0-ffffffff81eae3ed: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6fba2)
Location: net/sched/sch_generic.c:1034
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
Direct callers:
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff81f70e10-ffffffff81f70e5d: qdisc_free (STB_GLOBAL)
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
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c39ee8)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffff800010c39ee8-ffff800010c39f48: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4c1c8)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
c0d4c1c8-c0d4c210: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d32f00)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
c000000000d32f00-c000000000d32f9c: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007ab150)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffe0007ab150-ffffffe0007ab19c: qdisc_free (STB_GLOBAL)
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
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192e4c0)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff8192e4c0-ffffffff8192e4f9: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e7fc0)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff818e7fc0-ffffffff818e7ff9: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197f650)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff8197f650-ffffffff8197f689: qdisc_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void qdisc_free(struct Qdisc *qdisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a1bb0)
Location: net/sched/sch_generic.c:932
Inline: False
Direct callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_api.c:qdisc_create
```
**Symbols:**

```
ffffffff819a1bb0-ffffffff819a1be9: qdisc_free (STB_GLOBAL)
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
