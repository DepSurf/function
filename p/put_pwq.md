# Function: <code>put_pwq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81098680)
Location: kernel/workqueue.c:1054
Inline: True
Direct callers:
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:put_pwq_unlocked
  - kernel/workqueue.c:rescuer_thread
```
**Symbols:**

```
ffffffff81098680-ffffffff810986db: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109bc40)
Location: kernel/workqueue.c:1073
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:put_pwq_unlocked
```
**Symbols:**

```
ffffffff8109bc40-ffffffff8109bc9c: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0c80)
Location: kernel/workqueue.c:1075
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:put_pwq_unlocked
```
**Symbols:**

```
ffffffff810a0c80-ffffffff810a0cdc: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e220)
Location: kernel/workqueue.c:1075
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff8109e220-ffffffff8109e25b: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4a80)
Location: kernel/workqueue.c:1077
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810a4a80-ffffffff810a4abc: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac270)
Location: kernel/workqueue.c:1075
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810ac270-ffffffff810ac2ab: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b5150)
Location: kernel/workqueue.c:1095
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810b5150-ffffffff810b518b: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810baf60)
Location: kernel/workqueue.c:1103
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810baf60-ffffffff810baf9a: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c11c0)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810c11c0-ffffffff810c11fa: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810cc0d7)
Location: kernel/workqueue.c:1101
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810c94f0-ffffffff810c9523: put_pwq.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7217)
Location: kernel/workqueue.c:1101
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810c4630-ffffffff810c4663: put_pwq.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c899c)
Location: kernel/workqueue.c:1102
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810c5ec0-ffffffff810c5ef3: put_pwq.part.0 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810d9648)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:pwq_dec_nr_in_flight
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
In kernel/workqueue.c (ffffffff810f2ac3)
Location: kernel/workqueue.c:1124
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:pwq_dec_nr_in_flight
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
In kernel/workqueue.c (ffffffff81114d93)
Location: kernel/workqueue.c:1124
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:pwq_dec_nr_in_flight
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
In kernel/workqueue.c (ffffffff81121c4c)
Location: kernel/workqueue.c:1322
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:pwq_dec_nr_in_flight
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
In kernel/workqueue.c (ffffffff8112e7b3)
Location: kernel/workqueue.c:1425
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_pod
  - kernel/workqueue.c:wq_update_pod
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:pwq_dec_nr_in_flight
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
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011f0d8)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffff80001011f0d8-ffff80001011f138: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0372414)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
c0372414-c037249c: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000165ba0)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
c000000000165ba0-c000000000165bf0: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d95a2)
Location: kernel/workqueue.c:1104
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffe0000d8af0-ffffffe0000d8b5a: put_pwq.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb530)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810bb530-ffffffff810bb56a: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa000)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810aa000-ffffffff810aa03a: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810baa90)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810baa90-ffffffff810baaca: put_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3540)
Location: kernel/workqueue.c:1104
Inline: True
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
**Symbols:**

```
ffffffff810c3540-ffffffff810c357a: put_pwq (STB_LOCAL)
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
