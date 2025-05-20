# Function: <code>replenish_dl_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c1250)
Location: kernel/sched/deadline.c:379
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c1250-ffffffff810c1334: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c4ce0)
Location: kernel/sched/deadline.c:392
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c4ce0-ffffffff810c4dfb: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cad30)
Location: kernel/sched/deadline.c:380
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cad30-ffffffff810cae47: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c7420)
Location: kernel/sched/deadline.c:633
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c7420-ffffffff810c75f4: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ce9f0)
Location: kernel/sched/deadline.c:632
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ce9f0-ffffffff810cebbc: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:665
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810d56f0-ffffffff810d589c: replenish_dl_entity (STB_LOCAL)
ffffffff810d9019-ffffffff810d9039: replenish_dl_entity.cold.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:666
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810dfab0-ffffffff810dfc5c: replenish_dl_entity (STB_LOCAL)
ffffffff810e2b19-ffffffff810e2b39: replenish_dl_entity.cold.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:665
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810e7160-ffffffff810e730c: replenish_dl_entity (STB_LOCAL)
ffffffff810e96c9-ffffffff810e96e9: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810f2780-ffffffff810f292c: replenish_dl_entity (STB_LOCAL)
ffffffff810f50f9-ffffffff810f5119: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:700
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810faae0-ffffffff810fac78: replenish_dl_entity (STB_LOCAL)
ffffffff810fe819-ffffffff810fe839: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:777
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810f8fa0-ffffffff810f9129: replenish_dl_entity (STB_LOCAL)
ffffffff81bdc859-ffffffff81bdc871: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:763
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810faf50-ffffffff810fb0d9: replenish_dl_entity (STB_LOCAL)
ffffffff81bce9d4-ffffffff81bce9ec: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:763
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff811166f0-ffffffff811168e9: replenish_dl_entity (STB_LOCAL)
ffffffff81ca6956-ffffffff81ca69c2: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:826
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff81131860-ffffffff81131a68: replenish_dl_entity (STB_LOCAL)
ffffffff81e56101-ffffffff81e5616d: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:835
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff8115b880-ffffffff8115baa3: replenish_dl_entity (STB_LOCAL)
ffffffff82057332-ffffffff82057386: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:830
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff8116ba60-ffffffff8116bc72: replenish_dl_entity (STB_LOCAL)
ffffffff820d5b58-ffffffff820d5bac: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:831
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff81178460-ffffffff8117867f: replenish_dl_entity (STB_LOCAL)
ffffffff821b0bf0-ffffffff821b0c44: replenish_dl_entity.cold (STB_LOCAL)
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
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010154998)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffff800010154998-ffff800010154b60: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a1fa8)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c03a1fa8-c03a2224: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a89d0)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c0000000001a89d0-c0000000001a8cac: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fc706)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffe0000fc706-ffffffe0000fc8b0: replenish_dl_entity (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ebb80-ffffffff810ebd2c: replenish_dl_entity (STB_LOCAL)
ffffffff810ee4f9-ffffffff810ee519: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810dbba0-ffffffff810dbd4c: replenish_dl_entity (STB_LOCAL)
ffffffff810de589-ffffffff810de5a9: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810e8cb0-ffffffff810e8e5c: replenish_dl_entity (STB_LOCAL)
ffffffff810eb629-ffffffff810eb649: replenish_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void replenish_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:698
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810f3c60-ffffffff810f3e0c: replenish_dl_entity (STB_LOCAL)
ffffffff810f6689-ffffffff810f66a9: replenish_dl_entity.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sched_dl_entity *pi_se</code>
</li>
</ul>
</details>
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
