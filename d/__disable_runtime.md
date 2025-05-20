# Function: <code>__disable_runtime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c0e14)
Location: kernel/sched/rt.c:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c48a4)
Location: kernel/sched/rt.c:698
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ca8f4)
Location: kernel/sched/rt.c:698
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4408)
Location: kernel/sched/rt.c:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cb7f8)
Location: kernel/sched/rt.c:689
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d3138)
Location: kernel/sched/rt.c:688
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dcdd8)
Location: kernel/sched/rt.c:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e3d98)
Location: kernel/sched/rt.c:690
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ee9cc)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f89d0)
Location: kernel/sched/rt.c:732
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
```
**Symbols:**

```
ffffffff810f89d0-ffffffff810f8b8d: __disable_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f6be0)
Location: kernel/sched/rt.c:733
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
```
**Symbols:**

```
ffffffff810f6be0-ffffffff810f6d9d: __disable_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8720)
Location: kernel/sched/rt.c:733
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
```
**Symbols:**

```
ffffffff810f8720-ffffffff810f88f0: __disable_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81113ce0)
Location: kernel/sched/rt.c:744
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
```
**Symbols:**

```
ffffffff81113ce0-ffffffff81113ecc: __disable_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81130da0)
Location: kernel/sched/rt.c:780
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_rt
```
**Symbols:**

```
ffffffff81130da0-ffffffff81130f90: __disable_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115acb0)
Location: kernel/sched/rt.c:780
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_rt
```
**Symbols:**

```
ffffffff8115acb0-ffffffff8115aeb6: __disable_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116aec0)
Location: kernel/sched/rt.c:780
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_rt
```
**Symbols:**

```
ffffffff8116aec0-ffffffff8116b0c6: __disable_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __disable_runtime(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81178860)
Location: kernel/sched/rt.c:736
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_rt
```
**Symbols:**

```
ffffffff81178860-ffffffff81178a66: __disable_runtime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014ffb0)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039dd34)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a3ff8)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f8804)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e8228)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d7d8c)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4efc)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0ee8)
Location: kernel/sched/rt.c:691
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
