# Function: <code>init_rt_bandwidth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c1020)
Location: kernel/sched/rt.c:41
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810c1020-ffffffff810c105a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4ab0)
Location: kernel/sched/rt.c:41
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810c4ab0-ffffffff810c4aea: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cab00)
Location: kernel/sched/rt.c:41
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810cab00-ffffffff810cab3a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4e30)
Location: kernel/sched/rt.c:42
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810c4e30-ffffffff810c4e6a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cc4e0)
Location: kernel/sched/rt.c:43
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810cc4e0-ffffffff810cc51a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d4420)
Location: kernel/sched/rt.c:39
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810d4420-ffffffff810d445a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dde50)
Location: kernel/sched/rt.c:41
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810dde50-ffffffff810dde8a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4e60)
Location: kernel/sched/rt.c:41
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e4e60-ffffffff810e4e9a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f00b3)
Location: kernel/sched/rt.c:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810efe60-ffffffff810efe9a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f97b0)
Location: kernel/sched/rt.c:43
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f97b0-ffffffff810f97ed: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7b70)
Location: kernel/sched/rt.c:43
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f7b70-ffffffff810f7bad: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9ce0)
Location: kernel/sched/rt.c:43
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f9ce0-ffffffff810f9d1d: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81114a90)
Location: kernel/sched/rt.c:43
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81114a90-ffffffff81114acd: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81133960)
Location: kernel/sched/rt.c:90
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81133960-ffffffff811339a7: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115ddc0)
Location: kernel/sched/rt.c:90
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8115ddc0-ffffffff8115de07: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116e4a0)
Location: kernel/sched/rt.c:90
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8116e4a0-ffffffff8116e4e7: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117ba70)
Location: kernel/sched/rt.c:94
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff8117ba70-ffffffff8117bab7: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff8000101516c4)
Location: kernel/sched/rt.c:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffff800010151418-ffff800010151470: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039e99c)
Location: kernel/sched/rt.c:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
c039e724-c039e76c: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a4f60)
Location: kernel/sched/rt.c:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
c0000000001a4c50-c0000000001a4cc0: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f999a)
Location: kernel/sched/rt.c:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffe0000f9712-ffffffe0000f9764: init_rt_bandwidth (STB_GLOBAL)
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
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e9750)
Location: kernel/sched/rt.c:41
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e9750-ffffffff810e978a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d9473)
Location: kernel/sched/rt.c:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810d9220-ffffffff810d925a: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e65e3)
Location: kernel/sched/rt.c:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e6390-ffffffff810e63ca: init_rt_bandwidth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_rt_bandwidth(struct rt_bandwidth *rt_b, u64 period, u64 runtime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f17b0)
Location: kernel/sched/rt.c:41
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810f17b0-ffffffff810f17ea: init_rt_bandwidth (STB_GLOBAL)
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
