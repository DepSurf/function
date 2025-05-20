# Function: <code>__dequeue_rt_entity</code>

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
In kernel/sched/rt.c (ffffffff810c04ae)
Location: kernel/sched/rt.c:1194
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810c3e41)
Location: kernel/sched/rt.c:1254
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810c9ead)
Location: kernel/sched/rt.c:1253
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810c3b03)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810cb2a9)
Location: kernel/sched/rt.c:1255
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810d29c7)
Location: kernel/sched/rt.c:1264
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810dc337)
Location: kernel/sched/rt.c:1264
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810e32f7)
Location: kernel/sched/rt.c:1264
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810edba7)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f74a0)
Location: kernel/sched/rt.c:1306
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810f74a0-ffffffff810f766c: __dequeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f56a0)
Location: kernel/sched/rt.c:1308
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810f56a0-ffffffff810f586c: __dequeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f77e3)
Location: kernel/sched/rt.c:1308
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81111e22)
Location: kernel/sched/rt.c:1323
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112ef7b)
Location: kernel/sched/rt.c:1468
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81158d4b)
Location: kernel/sched/rt.c:1464
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116902b)
Location: kernel/sched/rt.c:1464
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81177127)
Location: kernel/sched/rt.c:1409
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffff80001014ebb0)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (c039cc08)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (c0000000001a2a68)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffe0000f7564)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810e7b23)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810d6ef7)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810e40d7)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
In kernel/sched/rt.c (ffffffff810f0333)
Location: kernel/sched/rt.c:1265
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
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
</ul>
