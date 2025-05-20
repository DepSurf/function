# Function: <code>process_one_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81099e90)
Location: kernel/workqueue.c:1961
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:rescuer_thread
```
**Symbols:**

```
ffffffff81099e90-ffffffff8109a30b: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109d420)
Location: kernel/workqueue.c:2017
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff8109d420-ffffffff8109d8c6: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1f90)
Location: kernel/workqueue.c:2019
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810a1f90-ffffffff810a2436: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f4a0)
Location: kernel/workqueue.c:2018
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff8109f4a0-ffffffff8109f8a2: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a5cd0)
Location: kernel/workqueue.c:2012
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810a5cd0-ffffffff810a60d5: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2046
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810ac860-ffffffff810acc20: process_one_work (STB_LOCAL)
ffffffff810b025f-ffffffff810b028f: process_one_work.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b58f0)
Location: kernel/workqueue.c:2066
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b58f0-ffffffff810b5cfe: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2162
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810bb7e0-ffffffff810bbb5a: process_one_work (STB_LOCAL)
ffffffff810befdb-ffffffff810bf00b: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c1a50-ffffffff810c1df5: process_one_work (STB_LOCAL)
ffffffff810c54d5-ffffffff810c5505: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2162
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c95e0-ffffffff810c9988: process_one_work (STB_LOCAL)
ffffffff810cd09e-ffffffff810cd0ce: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2168
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c4720-ffffffff810c4ad3: process_one_work (STB_LOCAL)
ffffffff81bdbef3-ffffffff81bdbf2f: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2169
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c5fb0-ffffffff810c6363: process_one_work (STB_LOCAL)
ffffffff81bce010-ffffffff81bce04c: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2198
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810d8c60-ffffffff810d9027: process_one_work (STB_LOCAL)
ffffffff81ca51ed-ffffffff81ca5229: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2181
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810f2470-ffffffff810f2862: process_one_work (STB_LOCAL)
ffffffff81e54acd-ffffffff81e54b09: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81113e10)
Location: kernel/workqueue.c:2181
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff81113e10-ffffffff8111423e: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811215b0)
Location: kernel/workqueue.c:2491
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff811215b0-ffffffff811219ef: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81129ae0)
Location: kernel/workqueue.c:2539
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff81129ae0-ffffffff81129e25: process_one_work (STB_LOCAL)
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
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011fe60)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffff80001011fe60-ffff8000101202bc: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0373c30)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
c0373c30-c037416c: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001682f0)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
c0000000001682f0-c000000000168838: process_one_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d8ce8)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffe0000d8ce8-ffffffe0000d905e: process_one_work (STB_LOCAL)
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
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810bbdc0-ffffffff810bc165: process_one_work (STB_LOCAL)
ffffffff810bf845-ffffffff810bf875: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810aa660-ffffffff810aa9ff: process_one_work (STB_LOCAL)
ffffffff810ae065-ffffffff810ae095: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810bb320-ffffffff810bb6c5: process_one_work (STB_LOCAL)
ffffffff810beda5-ffffffff810bedd5: process_one_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void process_one_work(struct worker *worker, struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2165
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c3700-ffffffff810c3ac9: process_one_work (STB_LOCAL)
ffffffff810c70f5-ffffffff810c7125: process_one_work.cold (STB_LOCAL)
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
