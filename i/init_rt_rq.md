# Function: <code>init_rt_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c1060)
Location: kernel/sched/rt.c:71
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810c1060-ffffffff810c1136: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4af0)
Location: kernel/sched/rt.c:79
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810c4af0-ffffffff810c4bc6: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cab40)
Location: kernel/sched/rt.c:79
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810cab40-ffffffff810cac16: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4e70)
Location: kernel/sched/rt.c:80
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810c4e70-ffffffff810c4f3a: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cc520)
Location: kernel/sched/rt.c:77
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810cc520-ffffffff810cc5b4: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d4460)
Location: kernel/sched/rt.c:73
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810d4460-ffffffff810d44f4: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dde90)
Location: kernel/sched/rt.c:75
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810dde90-ffffffff810ddf24: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4ea0)
Location: kernel/sched/rt.c:75
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e4ea0-ffffffff810e4f34: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810efea0)
Location: kernel/sched/rt.c:76
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810efea0-ffffffff810eff34: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f97f0)
Location: kernel/sched/rt.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f97f0-ffffffff810f9884: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7bb0)
Location: kernel/sched/rt.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f7bb0-ffffffff810f7c44: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9d20)
Location: kernel/sched/rt.c:78
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f9d20-ffffffff810f9db4: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81114ad0)
Location: kernel/sched/rt.c:83
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81114ad0-ffffffff81114b63: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811339b0)
Location: kernel/sched/rt.c:130
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff811339b0-ffffffff81133a4d: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115de20)
Location: kernel/sched/rt.c:130
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8115de20-ffffffff8115debd: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116e500)
Location: kernel/sched/rt.c:130
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8116e500-ffffffff8116e59d: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117bad0)
Location: kernel/sched/rt.c:134
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8117bad0-ffffffff8117bb63: init_rt_rq (STB_GLOBAL)
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
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010151470)
Location: kernel/sched/rt.c:76
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/rt.c:alloc_rt_sched_group
```
**Symbols:**

```
ffff800010151470-ffff80001015150c: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039e76c)
Location: kernel/sched/rt.c:76
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/rt.c:alloc_rt_sched_group
```
**Symbols:**

```
c039e76c-c039e80c: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a4cc0)
Location: kernel/sched/rt.c:76
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/rt.c:alloc_rt_sched_group
```
**Symbols:**

```
c0000000001a4cc0-c0000000001a4d60: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f9764)
Location: kernel/sched/rt.c:76
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/rt.c:alloc_rt_sched_group
```
**Symbols:**

```
ffffffe0000f9764-ffffffe0000f97e8: init_rt_rq (STB_GLOBAL)
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
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e9790)
Location: kernel/sched/rt.c:76
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e9790-ffffffff810e9824: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d9260)
Location: kernel/sched/rt.c:76
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810d9260-ffffffff810d92f4: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e63d0)
Location: kernel/sched/rt.c:76
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e63d0-ffffffff810e6464: init_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_rt_rq(struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f17f0)
Location: kernel/sched/rt.c:76
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f17f0-ffffffff810f1884: init_rt_rq (STB_GLOBAL)
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
