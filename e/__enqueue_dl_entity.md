# Function: <code>__enqueue_dl_entity</code>

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
In kernel/sched/deadline.c (ffffffff810c1c63)
Location: kernel/sched/deadline.c:882
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810c57ac)
Location: kernel/sched/deadline.c:862
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810cb798)
Location: kernel/sched/deadline.c:851
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810c7746)
Location: kernel/sched/deadline.c:1313
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810ced3d)
Location: kernel/sched/deadline.c:1312
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810d6635)
Location: kernel/sched/deadline.c:1371
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810e0b75)
Location: kernel/sched/deadline.c:1370
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810e75e6)
Location: kernel/sched/deadline.c:1369
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810f2c06)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __enqueue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa030)
Location: kernel/sched/deadline.c:1404
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810fa030-ffffffff810fa18d: __enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __enqueue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f8420)
Location: kernel/sched/deadline.c:1481
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810f8420-ffffffff810f85e0: __enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __enqueue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa5a0)
Location: kernel/sched/deadline.c:1475
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810fa5a0-ffffffff810fa761: __enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __enqueue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff811152c0)
Location: kernel/sched/deadline.c:1475
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff811152c0-ffffffff811154a0: __enqueue_dl_entity (STB_LOCAL)
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
In kernel/sched/build_policy.c (ffffffff8113508a)
Location: kernel/sched/deadline.c:1613
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/build_policy.c (ffffffff8115f5da)
Location: kernel/sched/deadline.c:1614
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/build_policy.c (ffffffff8116fd53)
Location: kernel/sched/deadline.c:1605
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/build_policy.c (ffffffff8117d336)
Location: kernel/sched/deadline.c:1679
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffff800010154e78)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (c03a22c8)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (c0000000001a8d1c)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffe0000fc93a)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810ec006)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810dc026)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810e9136)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
In kernel/sched/deadline.c (ffffffff810f40e6)
Location: kernel/sched/deadline.c:1402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
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
</ul>
