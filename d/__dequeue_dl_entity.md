# Function: <code>__dequeue_dl_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c1fd0)
Location: kernel/sched/deadline.c:912
Inline: False
Direct callers:
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810c1fd0-ffffffff810c2183: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c5a10)
Location: kernel/sched/deadline.c:892
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810c5a10-ffffffff810c5b60: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cb9e0)
Location: kernel/sched/deadline.c:881
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810cb9e0-ffffffff810cbb1d: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c5860)
Location: kernel/sched/deadline.c:1343
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810c5860-ffffffff810c5971: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ccf90)
Location: kernel/sched/deadline.c:1339
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810ccf90-ffffffff810cd080: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d4ef0)
Location: kernel/sched/deadline.c:1398
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810d4ef0-ffffffff810d4fdc: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810de8a0)
Location: kernel/sched/deadline.c:1397
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810de8a0-ffffffff810de98c: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:1396
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810e5a10-ffffffff810e5b0e: __dequeue_dl_entity (STB_LOCAL)
ffffffff810e9619-ffffffff810e9646: __dequeue_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f0e30)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810f0e30-ffffffff810f0f3d: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f9f20)
Location: kernel/sched/deadline.c:1431
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810f9f20-ffffffff810fa02d: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f82e0)
Location: kernel/sched/deadline.c:1508
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810f82e0-ffffffff810f8420: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa450)
Location: kernel/sched/deadline.c:1486
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810fa450-ffffffff810fa594: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff811155c0)
Location: kernel/sched/deadline.c:1486
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff811155c0-ffffffff81115720: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81135dd0)
Location: kernel/sched/deadline.c:1624
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
```
**Symbols:**

```
ffffffff81135dd0-ffffffff81135f41: __dequeue_dl_entity (STB_LOCAL)
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
In kernel/sched/build_policy.c (ffffffff811603d4)
Location: kernel/sched/deadline.c:1625
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
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
In kernel/sched/build_policy.c (ffffffff81170aed)
Location: kernel/sched/deadline.c:1616
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1690
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_server_stop
  - kernel/sched/build_policy.c:update_curr_dl_se
  - kernel/sched/build_policy.c:update_curr_dl_se
```
**Symbols:**

```
ffffffff8117e3d0-ffffffff8117e59c: __dequeue_dl_entity (STB_LOCAL)
ffffffff821b12c4-ffffffff821b12d9: __dequeue_dl_entity.cold (STB_LOCAL)
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
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010152e10)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffff800010152e10-ffff800010152f1c: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c039f818)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
c039f818-c039f94c: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a6320)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
c0000000001a6320-c0000000001a647c: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fa72e)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffe0000fa72e-ffffffe0000fa838: __dequeue_dl_entity (STB_LOCAL)
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
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ea230)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810ea230-ffffffff810ea33d: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810da1f0)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810da1f0-ffffffff810da36e: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7360)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810e7360-ffffffff810e746d: __dequeue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dequeue_dl_entity(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2320)
Location: kernel/sched/deadline.c:1429
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
**Symbols:**

```
ffffffff810f2320-ffffffff810f242d: __dequeue_dl_entity (STB_LOCAL)
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
